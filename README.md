# TopER: Topological Embeddings in Graph Representation Learning

This Algorithm is used to get the results for our paper: TopER: Topological Embeddings in Graph Representation Learning.

The folder 'functions_to_calculate_[a,b]' contains the main algorithms to get vectors [a,b] for each graph for an entered benchmark dataset.
The python code 'Main.py' calculates the vectors X and Y for each filtration function, and saves them in .csv files.
Then, the code 'features_main.py' calculates [a,b] vectors and saves them in a .csv file using the .csv files calculated previously.

The folder 'classification_codes' contains the codes to do graph classification employing the last .csv file
