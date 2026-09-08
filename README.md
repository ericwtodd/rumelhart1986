# rumelhart1986

Reproduction of the family-tree network from Rumelhart, Hinton & Williams (1986),
*Learning representations by back-propagating errors* (Nature **323**, 533–536).

One self-contained notebook: builds the two isomorphic family trees, trains the
five-layer network with the paper's recipe (batch gradient descent, ½·SSE with a
0.2/0.8 tolerance band, momentum schedule), and visualizes the learned unit
activations (Fig. 3) and person representations (Fig. 4) using
[NNsight](https://nnsight.net).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ericwtodd/rumelhart1986/blob/main/family_tree.ipynb)
