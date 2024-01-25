# Geilo Winter School Graph Course

Material for the course on graphs and graph signal processing given during the [Geilo Winter School on graphs and applications](https://www.sintef.no/projectweb/geilowinterschool/2024-winter-school/), January 2024.

## Summary 
The course is a guided tour inside the world of graphs and data over graphs. We will go through some of the theory and practive to discover the key concepts behind graph data mining and graph machine learning. We will see the central role played by the Graph Laplacian matrix and get a sharper view on the connection between the graph structure and the data. The lectures will be a mix of theory and practice. For the practice we will use jupyter notebooks, Python and the networkx module. Some graph visualizations may be done with the open-source software Gephi.

1. Graph: spectral graph theory

As a first step, we will explore the properties of the Laplacian matrix of a graph, its eigenvalues and eigenvectors. We will see some connection with Physics and with two powerful Data Science methods: Laplacian eigenmaps and spectral clustering. The aim is to understand better the information embedded in a graph and how to make use of it. This will prepare us for the next step.

2. Graphs and data: graph signal processing and graph Fourier transform

Graph signal processing starts when you add values to the nodes of a graph and combine the values with the graph structure. This can be generalized to vector of features associated to each node, which is at the heart of graph machine learning and graph neural networks. We will see what is the Graph Fourier transformation, the important differences with the standard setting and its relationship with graph machine learning.

3. Graphs, data and evolution: variation in data and variation in the graph

In this lecture we will cover some dynamical processes over graphs. We will start with standard ones such as PageRank and label propagation, where information is diffused over the graph. These methods are tightly connected to the topics of the first two lectures. We will then see how to deal with evolving data and evolving graphs. this will be connected to some of the recent advances in graph machine learning.

## Material

* The pdf files in this repository are the lecture slides for each part. 
* Part 1 exercise on label propagation: An example of label propagation coded in Python can be found in my previous tutorial for the Web Conf here: [https://github.com/bricaud/WebConfTuto](https://github.com/bricaud/WebConfTuto) inside the Jupyter notebook `04_ML_on_graphs.ipynb`.
* Part 2 exercise on eigendecomposition of the Graph Laplacian: see the Jupyter notebook `GraphEigenvaluesGeilo.ipynb`.
* Part 3 exercise on heat diffusion on a graph: See the files in the repository [https://github.com/bricaud/heat_diff_ex](https://github.com/bricaud/heat_diff_ex) (Forked from my Student Tobias). The main file is `heat_diffusion_simpler.py`.


