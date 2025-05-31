This folder contains notebooks on converting csv files of emissions from the oscilloscope into numpy files for much faster upload into verious notebooks.

Convert2Numpy-Re: This notebook reads from the folders and file locations containing the electromagnetic (EM) emissions of specific programs and saves the full signals (including the emissions of code used to set consistant values during program loops and extract the exact program start and end locations) and the segment corresponding to the actual program being captured.
Creating Arrays containing all program instructions: This notebook is simple to create numpy arrays of the assembly instructions contained in every program used in the experiments for quick access later on.
Results: Contains graphical samples of every program used in the experiment's full and segment signal.

note: 
	full signals corresponds to the entire emissions of code, including not only the programs but the code used to set consistant values during program loops and extract the exact program start and end locations.
	segment corresponds to the emissions of the code of the actual program used in the experiments.