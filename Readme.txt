Steps to Run the HACK_ML script

Note: Follow the same process for all badnets from B1, B2....Bn

1. Load the Validation dataset, Test Dataset, Backdoored Model
	Loading can be done by altering the paths of the required model and dataset files in the HACK_ML Script.  
	
2. Now run the entire script.
	Output 1: It is the class prediction of a Single Vanilla test image. (Unpreprocessed)
	Output 2: It is the accuracy of Backdoored(N + 1) Class prediction on Poisoned Test Dataset.
	Output 3: It is the accuracy of Clean Class predictions on Clean Test Dataset.
