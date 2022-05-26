# PDBarrows

Use this notebook to generate a file in chimera that draws arrows between two PDB models.

1. [Prereqs](#prereqs)
2. [Instructions](#instruct)
3. [License](#license)

## Prereqs<a name="prereqs"></a>

* Set up a fresh conda environment with Python >= 3.7: **`conda create -n arrows python=3.7`**

* Activate the environment: **`conda activate arrows`**.

* Install jupyter, biopandas, and biopython: **`pip install notebook biopandas Bio`**.

* Start jupyter notebook: **`jupyter notebook`**.

* Open the notebook **PDBArrows.ipynb**.

## Instructions<a name="instruct"></a>

* Open the notebook to see the instructions. Briefly, the PDB files are parsed and a fasta-format output is generated for you to run a sequence alignment. This is then input to the second part of the notebook to generate a chimera bild file.

* There should only be one chain in each PDB file.

## License<a name="license"></a>

This project is licensed under the MIT License - see the [LICENSE.txt](https://github.com/sami-chaaban/PDBarrows/blob/main/LICENSE.txt) file for details.
