# Dockerfile TF Smell Detection based on Dynamic and Static Analysis Methods

Abstract—Dockerfile is used to build docker image. In the image building process, temporary files are frequently used to import applications and data. A careless use of Dockerfile may cause temporary files left in the image, which can increase the image size, thus affecting the elastic scale ability and QoS. This problem is identified as temporary file smell.
The feature of UnionFS that docker image used is different from traditional filesystems. If users are not paying attention, they are too apt to make such mistakes. To address this problem, we propose two different methods to detect temporary file smell with dynamic analysis and static analysis respectively. We use the real-world cases to evaluate our methods. Experimental results show that our methods can effectively detect the temporary file smell.
Keywords-Dockerfile, temporary file smell, dynamic analysis, static analysis

## 1. Fichamento de Conteúdo

O artigo aborda a detecção de um problema conhecido como "Temporary File Smell (TF Smell)" em arquivos Dockerfile, que resulta da utilização descuidada de arquivos temporários durante o processo de construção de imagens Docker. Esse problema pode levar a arquivos temporários deixados nas imagens, aumentando seu tamanho e afetando sua distribuição. Para lidar com esse problema, os autores propõem dois métodos de detecção: análise dinâmica e análise estática. Os métodos são avaliados com casos reais, demonstrando eficácia na detecção do TF Smell.

## 2. Fichamento Bibliográfico 

* _Temporary File Smell (TF Smell):_ Problema identificado como resultado da utilização descuidada de arquivos temporários em arquivos Dockerfile, levando a arquivos temporários deixados nas imagens resultantes.
* _Dynamic Analysis:_ Método de detecção de TF Smell baseado na análise do comportamento do código em tempo de execução.
* _Static Analysis:_ Método de detecção de TF Smell baseado na análise do código-fonte sem executá-lo.
* _UnionFS:_ Sistema de arquivos utilizado pelas imagens Docker, que difere dos sistemas de arquivos tradicionais e pode contribuir para a ocorrência do TF Smell.

## 3. Fichamento de Citações 

* _"The container technology represented by Docker is widely used in datacenters. It provides resource isolation and usage limitation for different applications with lower overhead, which enables a large number of service instances run in a host simultaneously."_
* _"To speed up deployment, docker helps organizations to seamlessly build, share and run any application anywhere."_
* _"Consider as the Dockerfile 1. This Dockerfile creates an JDK image. It contains three instructions, each of them creates a layer."_
* _"The whole image size is about 607MB, however, the useless temporary file accounts for 195MB (about 32%)."_
* _"TF Smell is usually caused by a careless use of Dockerfile. We propose two different detection method to address this problem."_
* _"The static analysis method is lightweight and easy to use. However, the variant forms of TF Smells have myriad ways."_

