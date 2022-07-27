# Authors
1. Chong Jing Ting 
2. Alun Owen
3. Adrian Pintille
4. Vilius Kaulinskas

# Folders
There are a total of 6 folders: 
1. Dataset
	* Contains the original dataset and the split dataset for train and test. 
	* This data is available locally at /afs/inf.ed.ac.uk/group/ANC/IRDS/miniproject-data/recipes, and was collected by Facundo Bellosi.
2. Exploratory_data_analysis
	* **Exploratory-data-analysis.ipynb** - The file starts with loading the dataset and basic data inspection using pandas, followed by removing duplicates. Further analysis are done on the most/least frequent ingredients for each cuisine, number of ingredients, and correlation between the top 10 most frequent ingredients. The dataset is also split for train and test. 
3. Dimensionality_reduction 
	* **Dimensionality reduction.ipynb** - Contains all the dimensionality reduction codes.
4. Memory_based_approach
	* **Collab filtering-User based.ipynb** - Code for collaborative filtering using user-based approach. It loads the data from the Dataset folder. Afterwards cross validation is performed for Cosine, Hamming and Jaccard similarity measures respectively. Using best configuration (jaccard), the test set evaluation is performed finally.
	* **Collab filtering-Item based.ipynb** - Code for collaborative filtering using item-based approach. It loads the data from the Dataset folder. Afterwards cross validation is performed for Cosine, Hamming and Jaccard similarity measures respectively. Using best configuration (cosine), the test set evaluation is performed finally.
	* The csv files are the saved cross validation results and generalization performance. 