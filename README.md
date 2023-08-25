# Redes_Neurais_Modelos
* Repositório atendendo a tarefa do Mestrado UFJF em Ciência da Computação " Implementação de Redes Neurais ".
* Foram utilizadas as seguintes arquiteturas: AlexNet, LeNet e VGG.
* Conjuntos de dados escolhidos: FashionMNIST e CIFAR-10


------ 

# Arquiteturas e Conjuntos de dados - andamento

* LeNet - MNIST - check - Sem plot
* LeNet - CIFAR - check - Sem plot

-----

* AlexNet - MNIST -
* AlexNet - CIFAR -

------

* VGG - MNIST -
* VGG - CIFAR - check - tensorflow/tensorboard

-----

# Use GPU
* CUDA 8.0.61
* CUDNN 5.1
* tensorflow_gpu 1.2.0

------

# Chose GPU to use
$ CUDA_VISIBLE_DEVICES=0 python main.py (optional patameters...)

------

# Logs
$ tensorboard --logdir=/logs
