# Principal Components Analysis on the RSV L Protein

## This project compares different conformations of L using PCA and the coordinates of the atoms.

The PDB structures used for this project are 6UEN, 6PZK, 8SNX, 8SNY, 8FPI, and 8FU3. We extracted the x, y, and z coordinate data from 6 different conformations of L this gives us a total of 18 features (6 structures, 3 dimensions). We filter the atoms to focus on the alpha carbons and remove any missing residues, giving us a total of 1356 atoms. We then project our data onto a new coordinate system and identify the top 100 atoms with the most variance between the structures.

## To run it yourself
1. Clone this project using  `git clone https://github.com/nlkeung/pca-protein-structures.git`
2. Install the Biopython, NumPy, and MatPlotLib using `pip install biopython numpy matplotlib`
