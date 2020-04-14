![](https://img.shields.io/github/repo-size/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/issues/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/stars/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/watchers/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/last-commit/michelpf/fiap-ml-visao-computacional)


# MBA FIAP Inteligência Artificial & Machine Learning

Obtenha mais informações sobre a formação em inteligência artificial e a ementa completa no [portal](https://www.fiap.com.br/mba/mba-em-artificial-intelligence-e-machine-learning/) da FIAP.

## Visão Computacional Capstone

### Análise de Imagens Médicas

As tecnologias de imagens médicas estão cada vez mais integradas aos sitemas de visão computacional, incluindo as imagens de raio-x.

Modelos de equipamentos modernos geram imagens digitais deste tipo de exame, proporcionando análises mais completas e menos _ad-hoc_, com isso algumas pré-análises podem ser realizadas por aplicações baseadas em inteligência artificial para confirmar ou sugerir diagnósticos ao profissional responsável pelo exame.

No campo dos diagósticos por raios-x, a pnenumonia é uma das enfermidades onde seu uso é um dos mais aplicados para determinar o curso de tratamento.

<p align="center">
    <img src="imagens/NORMAL2-IM-1422-0001.jpeg">
</p>


## 1. Instruções

Nas aulas utilizaremos a distribuição Ananconda, com uso intensivo do Jupyter Notebook, que há vem instalado nesta distribuição.

Para instalar, acesse a sessão de [Downloads](https://www.anaconda.com/download) do Anaconda.


### 2. Repositório

Recomendamos clonar este repositório.

>**Importante**: como serão desenvolvidos modelos com arquivos grandes, é necessário ter um arquivo ```.gitignore``` com o seguinte conteúdo:

```
projeto/pesos/*
!projeto/pesos/.gitkeep 

projeto/modelos/*
!projeto/modelos/.gitkeep 

projeto/classificadores/*
!projeto/classificadores/.gitkeep 

projeto/.ipynb_checkpoints

.DS_Store
````

### 3. Template guiado

Utilize o arquivo Jupyter "projeto-final/e-imagens-medicas.ipynb", siga todas as instruções, completando e construindo os algoritmos necessários.

### 4. Bibliotecas utilizadas

Este projeto requer **Python 3.5 ou superior** e as seguintes bibliotecas:

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](http://seaborn.pydata.org/)
- [Keras](https://keras.io/)
- [Tensorflow](http://tensorflow.org/)
- [Pillow](https://pillow.readthedocs.io/en/stable/)


### 5. Critérios de avaliação

O projeto será avaliado pelos seguintes itens abaixo. A nota final será uma composição levando em consideração o peso de cada tema.

- Desenvolvimento e tratamento da base de treinamento e validação (n1 _peso 1_)
- Implementação de modelo transfer learning baseado na implementação ResNet50 (n2 _peso 1,5)
- Implementação de modelo transfer learning baseado na implementação VGG16 (n3 _peso 1,5_)
- Implementação de modelo transfer learning baseado na implementação VGG19 (n4 _peso 1,5_)
- Implementação de modelo transfer learning baseado na implementação de arquitetura de escolha do grupo (arquitetura adicional) (n5 _peso 2_)
- Conclusões finais (n6 _peso 2,5_)

Nota Final = 2 * n1 + 1,5 * n2 + 1,5 * n3 + 1,5 * n4 + 2 * n5 + 2.5 * n6

### Dúvidas

Crie uma [Issue](https://github.com/michelpf/fiap-ml-visao-computacional-capstone-alternative/issues/new) com as perguntas para que as dúvidas sejam compartilhados com todos os alunos. Questionamentos particulares devem ser encaminhados pelo e-mail do professor.
