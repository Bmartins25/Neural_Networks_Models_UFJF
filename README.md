# Redes_Neurais_Modelos
* Repositório atendendo a tarefa do Mestrado UFJF em Ciência da Computação " Implementação de Redes Neurais ".
* Foram utilizadas as seguintes arquiteturas: AlexNet, LeNet e VGG.
* Conjuntos de dados escolhidos: FashionMNIST e CIFAR-10


------ 

# Arquiteturas e Conjuntos de dados 

* LeNet - MNIST - check - Sem plot
* Hiperparâmetros -> learning_rate = 0.001 / batch_size = 128 / epochs = 10

* LeNet - CIFAR - check - Sem plot
* Hiperparãmetros ->  learning_rate = 0.001 / batch_size = 128 / epochs = 10


-----

* AlexNet - MNIST - check
* Hiperparâmetros -> batch_size = 128 / resize = 224 /max_epochs = 10 / num_gpus= = 1 / learning_rate = 0.01
    
* AlexNet - CIFAR - check
* Hiperparâmetros -> epochs = 5 / learning_rate = 0.01 / batch_size = 32

------

* VGG - MNIST - check
*  Hiperparâmetros - > batch_size = 128/ epochs = 12 / num_classes = 10
  
* VGG - CIFAR - check - tensorflow/tensorboard
* Hiperparâmetros - > batch_size = 100 / epochs = 3 / learning_rate = 0.001 

-----

# GPU - Unidade de processamento de gráficos
* CUDA 8.0.61
* CUDNN 5.1
* tensorflow_gpu 1.2.0

------

# Logs
%tensorboard --logdir logs

------

# VGG - Acurácia / Perda - CIFAR10

![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/39361610-c7a9-4440-8740-bb9274d62201)

# AlexNet - Acurácia / Perda - CIFAR10

![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/39436828-8aaa-4f8e-8a3c-e85f08a409b2)

# leNet - Acurácia / Perda - CIFAR10


