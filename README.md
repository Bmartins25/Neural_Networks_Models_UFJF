# Redes_Neurais_Modelos
* Repositório atendendo a tarefa do Mestrado UFJF em Ciência da Computação " Implementação de Redes Neurais ".
* Foram utilizadas as seguintes arquiteturas: AlexNet, LeNet e VGG.
* Conjuntos de dados escolhidos: FashionMNIST e CIFAR-10


------ 

# Arquiteturas e Conjuntos de dados - em andamento

LeNet - MNIST - check - Sem plot
* Hiperparâmetros -> learning_rate = 0.001 / batch_size = 128 / epochs = 10

LeNet - CIFAR - check - Sem plot
* Hiperparãmetros ->  learning_rate = 0.001 / batch_size = 128 / epochs = 10


-----

AlexNet - MNIST - check
* Hiperparâmetros -> batch_size = 128 / resize = 224 /max_epochs = 10 / num_gpus= = 1 / learning_rate = 0.01
    
AlexNet - CIFAR - check
* Hiperparâmetros -> epochs = 5 / learning_rate = 0.01 / batch_size = 32

------

VGG - MNIST - check
* Hiperparâmetros - > batch_size = 128/ epochs = 12 / num_classes = 10
  
VGG - CIFAR - check - tensorflow/tensorboard
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

# VGG - Acurácia / Perda - CIFAR10 - Dados de treino e teste

![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/a86afaee-28b4-4741-afd7-e86aa58722b1)

# VGG - Acurácia / Perda - MNIST - Dados de treino e teste

![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/693b31d1-45a7-4286-ad95-b8e685afe324)
![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/91756a78-8f38-495d-bef2-db8323af2109)
![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/2d742abb-6cad-4302-b025-4e2efc008432)
![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/be41be85-55da-48b3-9ccd-4b67fb314142)





# AlexNet - Acurácia / Perda - CIFAR10  - Dados de treino e teste

![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/d4508e32-11f7-4021-8645-b0b11cc0009d)
![image](https://github.com/Bmartins25/Redes_Neurais_Modelos/assets/42076192/f11a4521-31ca-4046-b4e2-e807f78ace38)



# LeNet - Acurácia / Perda - CIFAR10


