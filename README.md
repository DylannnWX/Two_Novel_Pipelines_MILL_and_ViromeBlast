# Two_Novel_Pipelines_MILL_and_ViromeBlast
Hi friends, welcome to my Github page!

A quick introduction, my name is Xi Wang but feel free to call me Dylan - I go by this name so that it's easier for people to pronounce, and also easier for me to recognize. As of today (08/12/2021), I'm a 5th year Ph.D. candidate in Joshua Obar laboratory, Geisel School of Medicine, Dartmouth College. I'd want to tell you about all the fun stories I had during the past five years, but that's probably not the reason why you're here. Perhaps another time! 

I'm the first author of the article "Computational pipelines to screen for unknown viral infections in RNAseq datasets and dsRNA forming elements in genome to identify sources of Mda5 stimulating dsRNA in Aspergillus fumigatus", and in this repository you'll find the walkthrough of the two pipelines - my goal is that anyone can do this on their own computer. The language is R but you don't have to be an R expert to do it: all you need to do is copy & paste the codes in this repository to your own machine. 

Although you'd find the same message in the article, here's a brief intro of the two pipelines:

1. MILL (Mda5 Internal Ligand Locator)

Tests the entire genome CDS sequences, or any given set of sequences in a FASTA file, for potential Mda5-stimulating secondary structures. Basically screens for reverse complementary elements that can form dsRNA long enough to stimulate Mda5. On my own Asus laptop, it computes 10k sequences in about 7 minutes. The minimal binding requirement is >30nts, <20% mismatch rate. This is from the impressive Mda5 binding kinetics work from Sun Hur lab (if you're from Hur lab, please tell your PI I'm a fan!).

2. Virome Blast 

Tests and quantifies any known or unknown viral infections in a given RNAseq dataset. This is a highly versatile tool and can be applied to organisms other than Aspergillus and mycoviruses - for instance, human Balf (bronchoalveolar lavage fluid) RNAseq samples and potential viral infections, tumor RNAseq samples and potential tumor-inducing viruses, bacteria RNAseq samples and bacteriophages... in the article there is also an example of Covid discovery in a Wuhan patient Balf. Use your imagination!

That would be all. Oh and most importantly, have fun!
