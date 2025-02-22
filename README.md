# Bootcamp BairesDev - Machine Learning Practitioner - DIO

Este repositório contém os projetos desenvolvidos durante o bootcamp "Machine Learning Practitioner" oferecido pela BairesDev em parceria com a Digital Innovation One (DIO). O objetivo deste bootcamp é capacitar os participantes com conhecimentos e habilidades práticas em Machine Learning, utilizando diversas ferramentas e técnicas.

## Projetos Realizados

### 1. Matriz de Confusão
- **Descrição:** Projeto focado na análise e interpretação da matriz de confusão, uma ferramenta essencial para avaliar o desempenho de modelos de classificação.
- **Objetivos:** Introduzir a matriz de confusão e suas métricas derivadas, como Acurácia, Precisão, Recall e F1-Score. Demonstrar a implementação em Python utilizando a biblioteca scikit-learn.
- **Funcionalidades:**
  - Criação e visualização de matriz de confusão
  - Cálculo de métricas de desempenho
  - Exemplos práticos e interpretação dos resultados
- **Tecnologias Utilizadas:** Python, scikit-learn, matplotlib, seaborn
- **Instruções de Instalação:**
  ```bash
  pip install scikit-learn matplotlib seaborn
  ```

### 2. Exercicio de Redimensionalidade de Imagens
- **Descrição:** Projeto que aborda técnicas de redimensionamento e conversão de imagens para escala de cinza e binarização.
- **Objetivos:** Demonstrar o uso da biblioteca PIL para manipulação de imagens, incluindo redimensionamento, conversão para escala de cinza e binarização.
- **Funcionalidades:**
  - Redimensionamento de imagens
  - Conversão de imagens para escala de cinza
  - Binarização de imagens
- **Tecnologias Utilizadas:** Python, PIL, numpy
- **Instruções de Instalação:**
  ```bash
  pip install pillow numpy
  ```

### 3. Assistente Virtual Básico
- **Descrição:** Desenvolvimento de um assistente virtual básico utilizando reconhecimento de fala e síntese de voz.
- **Objetivos:** Criar um assistente virtual capaz de reconhecer comandos de voz e responder com síntese de voz, além de realizar tarefas como localização de endereços e comércios.
- **Funcionalidades:**
  - Reconhecimento de fala
  - Síntese de voz
  - Integração com Google Maps para localização de endereços e comércios
- **Tecnologias Utilizadas:** Python, SpeechRecognition, pyttsx3, pyaudio, webbrowser
- **Instruções de Instalação:**
  ```bash
  pip install SpeechRecognition pyttsx3 pyaudio
  ```

### 4. Sistema de Recomendação de Imagens
- **Descrição:** Criação de um sistema de recomendação de imagens baseado em similaridade.
- **Objetivos:** Desenvolver um sistema capaz de recomendar imagens semelhantes com base em características extraídas das imagens.
- **Funcionalidades:**
  - Extração de características de imagens
  - Cálculo de similaridade entre imagens
  - Implementação de um sistema de recomendação
- **Tecnologias Utilizadas:** Python, tensorflow, numpy, pandas, matplotlib
- **Instruções de Instalação:**
  ```bash
  pip install tensorflow numpy pandas matplotlib
  ```

### 5. Transfer Learning - Cats and Dogs
- **Descrição:** Implementação de um modelo de classificação de imagens utilizando Transfer Learning para diferenciar gatos e cachorros.
- **Objetivos:** Demonstrar a utilização de modelos pré-treinados para transfer learning, aplicando-os na classificação de imagens de gatos e cachorros.
- **Funcionalidades:**
  - Download e organização do dataset Cats and Dogs
  - Implementação de Transfer Learning utilizando um modelo pré-treinado
  - Treinamento e avaliação do modelo
- **Tecnologias Utilizadas:** Python, tensorflow, keras, numpy, matplotlib
- **Instruções de Instalação:**
  ```bash
  pip install tensorflow keras numpy matplotlib
  ```

### 6. Sistema de Reconhecimento Facial usando OpenCV
- **Descrição:** Desenvolvimento de um sistema de reconhecimento facial utilizando a biblioteca OpenCV.
- **Objetivos:** Criar um sistema capaz de detectar e reconhecer faces em imagens utilizando algoritmos de visão computacional.
- **Funcionalidades:**
  - Captura de imagens usando webcam
  - Detecção de faces utilizando OpenCV
  - Desenho de caixas delimitadoras ao redor das faces detectadas
- **Tecnologias Utilizadas:** Python, OpenCV, imutils, numpy
- **Instruções de Instalação:**
  ```bash
  pip install opencv-python imutils numpy
  ```

### 7. Projeto de Detecção com a Rede Yolo
- **Descrição:** Implementação de um sistema de detecção de objetos utilizando a rede YOLO (You Only Look Once).
- **Objetivos:** Demonstrar a utilização da rede YOLO para detecção de objetos em imagens, incluindo configuração, treinamento e inferência.
- **Funcionalidades:**
  - Configuração e uso da rede YOLO
  - Detecção de múltiplos objetos em imagens
  - Visualização dos resultados com caixas delimitadoras
- **Tecnologias Utilizadas:** Python, PyTorch, YOLOv5
- **Instruções de Instalação:**
  ```bash
  pip install torch torchvision
  ```

## Estrutura do Repositório

- `notebooks/`: Contém os notebooks Jupyter desenvolvidos durante o bootcamp.
- `datasets/`: Conjunto de dados utilizados nos projetos.
- `scripts/`: Scripts auxiliares para manipulação de dados e treinamentos de modelos.
- `models/`: Modelos treinados e salvos para reutilização.

## Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`
3. Commit suas mudanças: `git commit -m 'Minha nova feature'`
4. Faça um push para a branch: `git push origin minha-feature`
5. Abra um Pull Request.

## Contato

- **Nome:** Daniel Bevilacqua
- **LinkedIn:** [Daniel Bevilacqua](https://www.linkedin.com/in/danielbevilacqua/)
