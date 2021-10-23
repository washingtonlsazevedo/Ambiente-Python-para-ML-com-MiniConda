# Ambiente Python para ML com Miniconda
Configurar um ambiente de desenvolvimento Python para Machine Learning, utilizando o Miniconda (Vale salientar que ele tem suporte e Python 3.9)

## O que é o Miniconda?
É uma pequena versão do popular Anaconda, ele inclui apenas conda, Python, os pacotes dos quais eles dependem e um pequeno número de outros pacotes indispensaveis, incluindo pip, zlib e dentre outros. Mas permiti instalar mais de 720 outros pacotes conda.

## A quem se destina o Miniconda
Muitas vezes se acredita que Anaconda seria destinado a usuários novato ou que não queira gerenciar quais pacotes deveria instalar. No Miniconda, se terá que atentar na instalação e gestão dos pacotes que serão utilizados. Pessoalmente, acredito que a real diferença reside se você não dispõe de um espaço em disco, suficiente para comportar os mais de 1500 pacotes que são instalados pelo Anaconda e também queira gerenciar quais são os pacotes que realmente lhe interessam.

## Primeiros passos
### Instalar o Miniconda
O Miniconda tem instalador disponível para Windows, Linux e MacOS. Você pode baixa-lo no link a seguir: https://docs.conda.io/en/latest/miniconda.html

_Obs.: A instalação que irei fazer será para um MacOS, utlizando como editor o VSCode, foi instalado previamente as extensões Python e Jupiter Notebook. Utilize o editor que preferi. O objetivo desse tutorial é de somente auxiliar na preparação do ambiente de desenvolvimento para Machine Learning._

### Criando o ambiente
Com do Miniconda devidadmente instalando, vamos criar nosso ambiente para trabalhamos com ML

`conda create --name nome_seu_ambiente`

### Ativando o ambiente criado

`conda activate nome_seu_ambiente`

### Instalando as bibliotecas e pacotes
Primeiramente iremos instalar uma biblioteca open source de machine learning que prove suporte a aprendizados de maquinas supervisionados e não supervisionados.

`conda install - c conda-forge scikit-learn`

Para concluir nosso ambiente, vamos instalar os pacotes Pandas, MatPlotLib e SeaBorn

`conda install pandas`

`conda install matplotlib`

`conda install seaborn`

### Criação, ativação instalação de bibliotecas finalizados
>Agora basta abrir seu editor e criar um novo Jupyter Notebook e se divertir...
