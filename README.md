# protein_struct_lib

What is a Structural Library?
A structural library is a database that stores information about protein structures, such as their 3D coordinates, chemical composition, and other structural features. These libraries can be used to compare new protein structures against known ones, to identify potential functional or structural similarities, or to aid in the design of new proteins.

Why are we making a Structural Library?
We are making a structural library in order to advance bioinformatics. By having a database of known protein structures, we can perform comparative analyses of new protein structures and infer their functions, identify potential targets for drug design, and gain insights into the evolution of protein structures.

How are we making the Structural Library?
In our case, we are making the structural library by generating surface descriptors for a set of protein structures and storing them in a CSV file. These descriptors are generated using PyMOL to visualize and extract the surface of the protein structures, and OpenBabel to calculate a set of surface descriptors that capture information about the chemical composition and shape of the surface. Once the descriptors are calculated, they can be stored in a CSV file and used as a basis for comparing new protein structures against the known ones. When a new protein structure is introduced, we can generate its surface descriptors and compare them to the descriptors in the structural library to identify the closest matches. This can help us to infer potential functional or structural similarities between the new protein structure and the known ones.

<a href="https://imgur.com/JGOGEPk"><img src="https://i.imgur.com/JGOGEPk.png" title="source: imgur.com" /></a>
