# graph-jades
Attempting to use the struc2vec algorithm (https://github.com/sebkaz/struc2vec) to learn about spatial galaxy structures.

A guide to files:
- `*.txt` files are edge lists
- `*.emb` files are node embeddings
- low-redshift analysis is in `make_graph_bigger.ipynb`
- high-redshift analysis is in `make_graph_bigger_farz.ipynb`
- similarity graph analysis is in `nearest_neighbors.ipynb`

This code uses the astropy, numpy, networkx, matplotlib, and scikit-learn packages.
