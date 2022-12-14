# Percolation in a lattice
When coffee has strained through a series of filters, it has successfully percolated. Like coffee, other things also percolate (water, diseases, blood, polymers, networks of neurons, etc). Read this great Scientific American article for a fun intro: https://www.scientificamerican.com/article/the-mathematics-of-how-connections-become-global/. 

Physicists care about percolation because it typically marks a phase transition, where the nature of microscopic interactions fundamentally change to allow long range correlations. 

"main.py" uses a .txt file of indices as its input, converts those indices to 3D coordinates. From the coordinates, the burning algorithm is used to identify separate networks. The code will go through each of the networks and identify whether any of them has spanned from wall to wall. 


<img width="400" alt="percolation_path" src="https://user-images.githubusercontent.com/5424353/202331558-4bc29c8e-ff5d-4ce8-977d-b5b5120bd38e.png">
