# Generative Adversarial Networks (DCGAN)

## To use code:
1. Either:
Download the celebA dataset from http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
or
Download the celebA dataset from http://vision.cs.utexas.edu/projects/finegrained/

2. Install dependancies listed in requirements.txt
3. You will also need pyTorch which may be downloaded from http://pytorch.org
4. Either:
Run the jupyter notebooks to get the data tensors xTrain.npy and yAllTrain.npy and move them in to folder InData/celebA/
or
Run the jupyter notebooks to get the data tensors xTrain.npy and yTrain.npy and move them in to folder InData/SHOES/
5. The code may be run from cmd line with various options detailed in the code

	$ 	python dcgan_shoes.py --maxEpochs=100 --root=InData/ --batchSize=32 --useNoise --imSize=64 --commit=xxx


## Example results:

![alt text](https://github.com/ToniCreswell/pyTorch_GAN/blob/master/Experiments/Ex_2/epoch99.png)