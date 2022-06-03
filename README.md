# Python_Project2_Final
**Scientific Question**: How do the functional domains and predicted protein structures of human tafazzin compare with other orthologs and related phospholipid acyltransferases?

**Scientific Hypothesis**: If tafazzin is a phospholipid acyltransferase that is integral to mitochondrial function, then the important functional domains of tafazzin, such as the acyltransferase domain, must be highly conserved across species and similar to other phospholipid acyltransferases.

To run the code, you will need:

1) The Jupyter Notebook (Project2C.ipynb)
2) The fasta file containing the TAZ and related acyltransferase amino acid sequences
3) The pdb files for each TAZ ortholog and related acyltransferase

**Information on where the fasta file is found**: I compiled amino acid sequences of different tafazzin orthologs from NCBI onto the same fasta file. Using the dropdown menu on the search bar, I set the category to gene and typed in "tafazzin" in the search bar. Once navigating to the page of the tafazzin protein I wanted (for example, human tafazzin is the first entry), I scrolled down to the "NCBI Reference Sequences (RefSeq)" header and clicked on the link for tafazzin isoform 1 under the "mRNA and Protein(s)" subheader. This will show information on the protein. I clicked on "FASTA" to view it in FASTA format, then clicked "send to" --> "file" to download it as a FASTA file.

**Information on where the pdb files are found**: I went onto UniProt and typed in "tafazzin" in the search bar. Then, I clicked on the entry that I wanted to view or download the pdb file from. I scrolled down to the "Structure" heading and downloaded the pdb file (most were from AlphaFold).

**List of files**
- *TAZ.fasta* --> fasta file containing all the analyzed tafazzin sequences and related acyltransferase sequences. Used for multiple sequence alignment and phylogenetic clustering
- *TAZ_human.pdb* --> pdb file containing information to construct a 3D protein structure of the human tafazzin (exon 5 deletion) protein. Used for structural bioinformatics and 3D protein analysis
- *TAZ_mouse.pdb* --> pdb file containing information to construct a 3D protein structure of the mouse tafazzin protein. Used for structural bioinformatics and 3D protein analysis
- *TAZ_chimp.pdb* --> pdb file containing information to construct a 3D protein structure of the chimpanzee tafazzin protein. Used for structural bioinformatics and 3D protein analysis
- *TAZ_fly.pdb* --> pdb file containing information to construct a 3D protein structure of the fruit fly tafazzin protein. Used for structural bioinformatics and 3D protein analysis
- *TAZ_yeast.pdb* --> pdb file containing information to construct a 3D protein structure of the yeast tafazzin protein. Used for structural bioinformatics and 3D protein analysis
- *TAZ_zebrafish.pdb* --> pdb file containing information to construct a 3D protein structure of the zebrafish tafazzin protein. Used for structural bioinformatics and 3D protein analysis
- *GPAT1.pdb* --> pdb file containing information to construct a 3D protein structure of the human GPAT1 protein. Used for structural bioinformatics and 3D protein analysis
- *hTFPa.pdb* --> pdb file containing information to construct a 3D protein structure of the human TFPa protein. Used for structural bioinformatics and 3D protein analysis
- *LGPAT1.pdb* --> pdb file containing information to construct a 3D protein structure of the human LGPAT1 protein. Used for structural bioinformatics and 3D protein analysis
- *PLCD.pdb* --> pdb file containing information to construct a 3D protein structure of the human PLCD protein. Used for structural bioinformatics and 3D protein analysis
