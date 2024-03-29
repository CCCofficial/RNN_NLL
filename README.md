# A deep learning model for analyzing noisy biological systems
This project uses deep learning to map the varying input conditions (growth rate, degradation rate, transcription/translation rate, ect.) to the conditional probability distributions of the observations. 
The conditional probability distribution is automatically generated by the deep learning algorithms with the help of negative log likelihood loss function. This is the state-of-art since it does not require pre-assumption of the distribution (previous work all needs to pre-assume a gaussian, exponential or other distribution). During the training process, as few as one noisy data is needed per input condition.

If you find this code useful in your research, please consider citing. 	
Wang, Shangying, Sara Capponi, and Simone Bianco. "Inferring Conditional Probability Distributions of Noisy Gene Expression from Limited Observations by Deep Learning." GEN Biotechnology 1.6 (2022): 504-513. 
https://doi.org/10.1089/genbio.2022.0030
