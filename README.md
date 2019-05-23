
## Project Overview

It is the TV Script Generation project from the Deep Learning Nanodegree program of Udacity. This project is based on Recurrent Neural Networks (RNNs) and it can be used to generate fake Seinfeld TV scripts. The datasets used in the proyect are the scripts of the 9 seasons of this television comedy series.


## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
	git clone https://github.com/HebertoMadrigalSastre/DLND_P3_TV_Script_Generation.git

	cd DLND_P3_TV_Script_Generation
	```

2. Verify that you have already installed the required Python packages:

	- jupyter notebook
	- pytorch
	- numpy


3. Open the notebook dlnd_tv_script_generation.ipynb file.
	
	```
	jupyter notebook dlnd_tv_script_generation.ipynb
	```

The dataset is already included within the repository

## Project content

Content: 

- Get the Data
- Explore the Data
- Implement Pre-processing Functions
    - Lookup Table
    - Tokenize Punctuation
- Pre-process all the data and save it
- Build the Neural Network
    - Input
        - Batching
        - Test your dataloader
    - Define forward and backpropagation
- Neural Network Training
    - Train Loop
    - Hyperparameters
    - Train
- Generate TV Script
    - Generate text
    - Generate a new script


## (Optionally) Accelerating the Training Process

If the execution of the code is taking too long, you'd like to use a GPU. You can use Amazon Web Services to launch an EC2 GPU instance.