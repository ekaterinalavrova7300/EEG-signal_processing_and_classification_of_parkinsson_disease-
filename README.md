# EEG-signal_processing_and_classification_of_parkinsson_disease-

**Installation instructions:**  
If you are installing the code from github, pull down the repository to desired directory and open the EEG_analysis file in Jupyter notebook. Run the code from top to bottom and enter the file path to the input files where asked. 
If you are running it from canvas submission then then download the bdf files provided in one single folder. Download the ipynb file in the directory where you want your results to end up and open it in Jupyter notebook. Run the code cells from top to bottom in order. Under the Import data title, you will be asked to enter a file path. Enter the file path to where you have downloaded the bdf files provided.  Required packages are specified and downloaded inside the program.   

**How to set parameters?**  
The largest parameters are already set but can be changed within the code if wished for.     

*Number of epochs:* Under the “Apply feature extraction” title below the feature_extaction function the “epoch_duration” can be set to any number wished for. But for this model I would recommend keeping 20s epoch as it is best for classification statistics.   

*K value:*  Under the title “Validate classifier”, the k-NN classifier is applied in the variable   y_pred_temp. Here k I defined as 11 but can be changed if wished for. K is also defined inside the function parameters but does not need to be changed there as it is overwritten by the function use.     

**How to provide input files?**  
Download the files provided. And specify the file path to the folder with the files where asked in the notebook. 

**File Manifest:**  
	EEG_analysis.ipynb  - The program and code documentation   
	Requirements.txt - Version requirements of the program  
	README.md   
	EEG_features.csv - Output from Feature extraction cell (example_results)
	Input_data/ - Folder with input files  
	
