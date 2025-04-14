# Primeiro-Modelo-CNN -- Classificação de Imagens: Cães vs Gatos com CNN

## 📌 Visão Geral
Este projeto foi desenvolvido como parte da disciplina de **Laboratório de Inovação e Automação**, com o objetivo de otimizar um modelo de classificação de imagens de cães e gatos usando Redes Neurais Convolucionais (CNNs). O código original foi fornecido pelo professor e aprimorado para melhor desempenho e eficiência.

---

## 🚀 Objetivos

- Otimizar o modelo base fornecido pelo professor, melhorando sua acurácia e eficiência.
- Implementar técnicas de aprendizado profundo para classificação de imagens.
- Documentar o processo de forma clara e didática, facilitando a reprodução e o entendimento.

---

## 📋 Conteúdo do Projeto

O projeto está organizado da seguinte forma:

- **Configuração Inicial**: Importação de bibliotecas essenciais e configuração do ambiente.
- **Preparação dos Dados**: Download, organização e pré-processamento do dataset "Dogs vs Cats".
- **Treinamento e Avaliação**: Divisão dos dados, aumento de dados (data augmentation) e criação de geradores de dados.
- **Modelo CNN**: Arquitetura da rede neural convolucional, compilação e treinamento.
- **Callbacks**: Implementação de `EarlyStopping` e `ModelCheckpoint` para otimizar o treinamento.
- **Treinamento do Modelo**: Execução do treinamento com 15 épocas.
- **Avaliação do Modelo**: Cálculo de métricas como acurácia e AUC.
- **Salvamento do Modelo**: Armazenamento do modelo treinado no Google Drive.
- **Predição**: Função para classificar imagens diretamente de arquivos ZIP.

---

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **TensorFlow/Keras**: Bibliotecas para construção e treinamento de modelos de deep learning.
- **Google Colab**: Ambiente de execução com suporte a GPU.
- **Kaggle**: Fonte do dataset [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats/data).

---

## 📊 Resultados

O modelo otimizado alcançou uma **acurácia de aproximadamente 82%** nos dados de validação, demonstrando uma melhoria significativa em relação ao modelo base.  
Técnicas como aumento de dados e callbacks foram implementadas para **evitar overfitting** e garantir um treinamento mais eficiente.
