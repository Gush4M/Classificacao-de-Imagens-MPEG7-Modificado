
<h1 align="center"> Classificação de Imagens no Conjunto de Dados MPEG7 Modificado </h1>
Projeto da disciplina SIN 393 - Introdução à Visão Computacional

Este projeto tem como objetivo implementar e avaliar diferentes métodos de classificação de formas e silhuetas utilizando o dataset MPEG-7 Modificado, um conjunto de imagens binárias (preto e branco) contendo diversas categorias de objetos, animais e símbolos.

# 📌 Objetivos

- Implementar técnicas de extração de características (Hu Moments, Histogram of Oriented Gradients - HOG);

- Comparar modelos de aprendizado de máquina tradicional (SVM, Random Forest) com redes neurais convolucionais (CNNs);

- Avaliar a eficiência de diferentes abordagens para reconhecimento de formas.

# 🔍 Métodos Utilizados
🔹 Pré-processamento

- Binarização e normalização de imagens

- Extração de contornos

🔹 Extração de Características

- Hu Moments (invariantes a rotação e escala)

- HOG (Histogram of Oriented Gradients) para descrição estrutural

🔹 Modelos de Classificação

- SVM (Máquinas de Vetores de Suporte);

- Random Forest;

- CNN (Rede Neural Convolucional) adaptada para formas binárias;

# 📊 Resultados

Os experimentos compararam a acurácia dos diferentes métodos, analisando:

- Desempenho em diferentes categorias do dataset;

- Robustez a variações de rotação e escala;

- Tempo de processamento e eficiência computacional.

Um relatório detalhado (em PDF) está disponível no repositório, contendo:

✔️ Metodologia completa

✔️ Análise comparativa dos modelos

✔️ Conclusões e possíveis melhorias

# Requisitos do Sistema
 - Sistema Operacional: Windows, macOS ou Linux
 - Python: Versão 3.8 ou superior
 - RAM: Pelo menos 8 GB de memória recomendada

# Dependências
As principais dependências para este projeto incluem:
 - numpy
 - pandas
 - matplotlib
 - scikit-learn
 - opencv-python
 - tensorflow

# Execução
Clone o repositório:

git clone <https://github.com/Gush4M/Classificacao-de-Imagens-MPEG7-Modificado/tree/main>
cd Classificação_de_Imagens_MPEG7_Modificado

Certifique-se de que todas as dependências foram instaladas.

Execute o notebook interativamente:

jupyter notebook Classificação_de_Imagens_MPEG7_Modificado.ipynb

Caso prefira, converta o notebook em script Python e execute-o:

jupyter nbconvert --to script Classificação_de_Imagens_MPEG7_Modificado.ipynb
python Classificação_de_Imagens_MPEG7_Modificado.py

# Autores

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/98776180?v=4" width=115><br><sub>Gustavo Henrique de Deus Reis</sub>](https://github.com/Gush4M)

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/108095908?v=4" width=115><br><sub>Júlio Cezar Lopes Cardoso</sub>](https://github.com/cez4rrxvxl)

