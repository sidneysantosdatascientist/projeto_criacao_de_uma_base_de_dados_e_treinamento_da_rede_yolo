# 📌 YOLOv8 - Detecção de Objetos no Google Colab

Este projeto utiliza o modelo **YOLOv8** para detectar objetos em imagens, permitindo que usuários carreguem imagens no **Google Colab** e obtenham predições automáticas.

## 🚀 Tecnologias Utilizadas
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Google Colab

## 📌 Instalação

Antes de rodar o projeto, instale as dependências:

```bash
pip install -r requirements.txt
```

## 🖼️ Como Rodar a Detecção

1. Faça upload de uma imagem no Google Colab.
2. Execute o script `detect.py` para rodar a detecção de objetos.
3. Veja os resultados na tela.

```bash
python detect.py
```

## 📌 Exemplo de Uso

Após rodar o código, a saída será uma imagem com as detecções feitas pelo YOLOv8, similar a esta:

![Exemplo de Detecção](images/example_output.png)

## 📌 Treinamento de um Modelo Personalizado

Se quiser treinar o YOLOv8 em suas próprias classes, siga os passos:

1. Prepare um dataset rotulado no formato YOLO.
2. Modifique o arquivo `data.yaml` para apontar para suas imagens.
3. Execute o treinamento:

```bash
python train.py
```

## 📌 Autores

- **Sidney Pereira Santos** - *Desenvolvedor* ([LinkedIn](https://www.linkedin.com/in/sidney-santos-analista-de-dados/))
