**Some open questions**:
* Why not just compile DNA -> Protein? Why the RNA step at all? Computationally seems like you're just swapping out the thymine for the uracil...
    * Seems like part of the answer here is that DNA is just the template, RNA is the messenger molecule because it's more reactive chemically, so it economizes on energy; DNA, being more stable, is a better and more reliable "store of information", RNA is a better "doer of things"
* How does the -1 ribosomal frameshifting work, mechanistically?
    * Relies on what's called a "slippage sequence", 8 bases long, usually X XXY YYZ
    * 5-9 bases downstream there is a "pseudoknot" structure which stalls the ribosome on the slippage sequence
    * This causes the ribosome to backtrack by one base 
    * All coronaviruses have these, one example is the cleavage of orf1ab into orf1a and orf1b
* Why is orf1ab so large / what's the advantage of a polyprotein vs. many individual proteins?
    * The virus is an mRNA-like molecule that needs to be translated by its host cell
    * Since we're eukaryotes, this means our ribosomes translate one gene at a time before dropping off
    * (Technical term for this is monocistronic - cistron is old name for a gene)
    * Virus therefore needs to smuggle in a ton of proteins into that "one protein" to get replicated
    * Hence, bundles them into one large polyprotein which then gets broken down afterwards to start getting itself replicated. The polyprotein contains several "nsps" (non-structural proteins)
    * nsps1-3 adapt a lot, appear to adapt to the host, nsp1 disables host mRNA translation in favor of viral.
    * nsps4-16 are pretty similar across coronaviruses
    * "Papain-like proteases" cut orf1ab into 16 non-structural proteins (nsps)
    * These nsps then assemble into "RTC" (Replication-Transcription Complexes") & help replicate the virus 
* What is the point of all the random little proteins? 
    * Still unclear for many, each of them does some stuff in vivo to help the virus (e.g. interferon-B antagonists, for example, delay the immune response).
* How does one learn what each protein does, apart from observing the virus do its thing? Preusmably one can guess from previous studies of the virus, but how did they originally figure this out. 
    * Can knock out the protein-coding region of RNA and observe the virus do its thing in an animal
    * Like deleting a region of code and re-running the program to see what happens...
    * Since bodies don't have stacktraces, though, it's hard to go beyond "appears to play a role in X" level of detail
    * Cryo-EM is used to visualize the proteins at the molecular level

**TODOS**:
* Something to automatically parse the genome and grab the proteins, throw into a table sorted descending by length - DONE
* Sequence comparison tool so you can see insertions/deletions from previous coronaviruses
* Phylogenomic analysis based on the many genomes in GENEBANK and GISAID; look at transmission chains geographically 

**HELPFUL RESOURCES**
* Great lecture on the molecular virology of coronaviruses: https://www.youtube.com/watch?v=8_bOhZd6ieM
