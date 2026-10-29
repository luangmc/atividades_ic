# Atividades de Iniciação Científica - Análise de Dados e Machine Learning

Este repositório contém os materiais de treinamento inicial para novos alunos de Iniciação Científica (IC). O objetivo das atividades é fornecer uma introdução prática à **análise de dados** e **Machine Learning** utilizando Python.

---

## 📂 Estrutura do Repositório

As atividades e seus respectivos conjuntos de dados estão organizados da seguinte forma:

```text
├── atividade_1/
│   ├── atividade1_aluno_IC.pdf         # Roteiro: Análise Exploratória e Visualização
│   └── dados_atividade/                # Arquivos de dados no formato .root
│
├── atividade_2/
│   ├── atividade2_aluno_IC.pdf         # Roteiro: Classificação com Machine Learning
│   └── dados_atividade/                # Dataset consolidado no formato .csv
│
└── atividade_3/
    └── atividade3_aluno_IC.pdf         # Roteiro: Redes Neurais com PyTorch (MLP e CNN)
```

> Os dados da Atividade 3 (`.csv`, imagens em `.h5` e divisão treino/teste em `.json`) não estão no repositório, por causa do tamanho: eles são enviados diretamente ao aluno por um link do Google Drive.

---

## 📋 Descrição das Atividades

### [Atividade 1: Análise Exploratória e Manipulação de Dados](./atividade_1/atividade1_aluno_IC.pdf)
Focada no desenvolvimento de habilidades de manipulação de formatos científicos de arquivos, álgebra linear aplicada a imagens e ajustes estatísticos.

---

### [Atividade 2: Projeto de um Classificador de Machine Learning](./atividade_2/atividade2_aluno_IC.pdf)
Focada na construção e avaliação de um pipeline completo de aprendizado de máquina supervisionado para classificação binária.

---

### [Atividade 3: Redes Neurais com PyTorch (MLP e CNN)](./atividade_3/atividade3_aluno_IC.pdf)
Introdução ao PyTorch e às redes neurais: uma MLP treinada com as features dos eventos (continuação da Atividade 2) e uma CNN treinada diretamente com as imagens, comparadas no mesmo conjunto de teste, além de experimentos com os hiperparâmetros das redes. Deve ser feita no Google Colab com GPU.

---

## 💻 Requisitos

As atividades podem ser desenvolvidas localmente (como VSCode) ou em plataformas baseadas em nuvem (como o Google Colab). As principais dependências necessárias são:

*   `Python` (linguagem de programação)
*   `uproot` (leitura de arquivos `.root`)
*   `numpy` e `scipy` (álgebra linear e ajuste de curvas)
*   `pandas` (manipulação de dados tabulares)
*   `matplotlib` (geração de gráficos e visualização)
*   `scikit-learn` (algoritmos de machine learning e métricas)
*   `torch` e `torchinfo` (redes neurais, Atividade 3)
*   `h5py` (leitura de arquivos `.h5`, Atividade 3)

---

## ✉️ Contato e Suporte

Dúvidas sobre a execução dos códigos, formatação dos dados ou interpretação dos roteiros podem ser enviadas diretamente para os pós-graduandos responsáveis pelo acompanhamento das tarefas:

*   **Luan Gomes** – 📧 [luan.gomes@estudante.ufjf.br](mailto:luan.gomes@estudante.ufjf.br)
*   **Igor Pains** – 📧 [igorpains@gmail.com](mailto:igorpains@gmail.com)
