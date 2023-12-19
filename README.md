# cs-762-project-2023
Feeding Two Birds with a Smarter Scone: Adaptive Energy Margin for Enhanced OOD Performance


# Preliminaries
This is tested under Ubuntu Linux 20.04 and Python 3.8 environment, and requries some packages to be installed:

PyTorch
torchvision
numpy
sklearn
wandb

Dataset Preparation
Download the data in the folder

./data

The corrupted CIFAR-10 dataset can be downloaded via the link:

wget https://drive.google.com/drive/u/0/folders/1JcI8UMBpdMffzCe-dqrzXA9bSaEGItzo

# Pretrained models
You can find the pretrained models in:  
./snapshots/save/cifar10/svhn/scone/  
one good example is:  
./snapshots/save/cifar10/svhn/scone/steps/scone_0.0_1_0.05_1_1_1.5_0.5_0.1_epoch_90.pt

# Demo
To run the code, execute  
bash run.sh scone cifar10 svhn svhn  
you can use "--eta" to try different initial eta values

