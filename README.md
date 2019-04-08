# CNN-for-CIFAR100
1.	Tools needed
•	Laptop (CPU: I7 8th gen intel processor, GPU: Nvidia GTX 1060)/ any laptop with a NVIDIA GPU
•	Anaconda
•	Jupyter Notebook

2.	Installation
•	First install Anaconda from https://docs.anaconda.com/anaconda/install/
•	Install tensorflow for gpu using conda tensorflow-gpu
•	Install keras for gpu using conda keras-gpu
•	After installing anaconda we can write on the anaconda terminal, jupyter notebook to open the notebook in your browser window

3.	Motivation
While installing keras I was going through the documentation on their website. I found a code snippet for training a keras model for CIFAR-10 dataset. I tried compiling it and successfully executed it with an accuracy of 70%. I went on the database website and found another of their database CIFAR-100. It contained images divided into 100 different classes and 20 different super classes. It sounded like a challenge for me. I researched a lot about it and found out that the benchmark runtime accuracy for it was 84%. I thought this would be perfect if I could even come close to this accuracy of predicting classes by using convoluted neural network.

4.	Dataset
•	https://www.cs.toronto.edu/~kriz/cifar.html
•	Download the dataset
•	Extract using winzip and store it in a folder and copy the path.
