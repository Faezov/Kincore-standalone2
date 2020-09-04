# Kincore-standalone
# Use the following command to create a virtual enviroment and install the necessary packages.

$conda create --name 'kincore-standalone' python=3.8 pandas numpy biopython hmmer --channel conda-forge --channel bioconda

$conda activate kincore-standalone

$python3 kinase_state.py -h
