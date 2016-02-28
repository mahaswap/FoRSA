###########################################################################################################
# Written by Swapnil MAHAJAN on 28 Feb. 2016
# FoRSA
FoRSA: Fold Recognition using a Structural Alphabet.

Fold recognition is an important step in structural annotation of proteins with no homologue of known 3-D structure identified using sequence-search methods. FoRSA provides a unique fold recognition algorithm which is based on calculation of conditional probability for the amino acid sequence of a protein to fit to a particular fold.

We use a structural alphabet, known as “Protein Blocks” (PBs) which is a library of 16 local structural prototypes named a to p based on a sliding window of pentapeptides, to encode existing folds into PB sequences. The method relies on the usage of 16 amino acid occurrence matrices, one for each PB, to calculate conditional probability of a window of 15 residues to have a local structure corresponding to a particular PB.

These probabilities were used to score dynamic programming based global and local alignments of query amino acid sequences to PB sequences derived from a library of known folds.

To cite this application :
Use of a structural alphabet to find compatible folds for amino acid sequences.
Mahajan S, de Brevern AG, Sanejouand YH, Srinivasan N, Offmann B.
Protein Sci. 2015 Jan;24(1):145-53. doi: 10.1002/pro.2581. Epub 2014 Oct 25.
PMID: 25297700
Link : http://onlinelibrary.wiley.com/doi/10.1002/pro.2581/abstract
###########################################################################################################

