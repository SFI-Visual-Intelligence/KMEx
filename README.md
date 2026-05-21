Paper: Prototypical Self-Explainable Models Without Re-training ([Link](https://api.nva.unit.no/publication/0198cc94fc5e-f9090bec-6ccb-41b9-b38f-09d2c173bfe3))

# KMEx
The official repository for Prototypical Self-Explainable Models Without Re-training

### Setup

Install a new conda environment 
```sh
conda env create -f requirements.yml
conda activate kmex
```


### Usage

```
Command example: python main.py --dataset mnist --model RESNET34 --run r0 --load
(1) -dataset: name of the dataset. Supports mnist, fmnist, quickdraw, cifar10, svhn, stl10, celeba
(2) -model: backbone model. Supports RESNET34, PROTOVAE_RESNET34 (for training as well as evaluation of KMEx), PPNET_RESNET34 (for ProtoPNet+KMEx and its evaluation), FLINT_RESNET34 (for FLINT+KMEx and its evaluation). 
(3) -run: name of the experiment.
(4) --load: flag for loading the model.
```


