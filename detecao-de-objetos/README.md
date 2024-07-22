# Detecção de Objetos

## Autor
Matheus Gante

## Descrição
Este projeto implementa um sistema de detecção de objetos em vídeos utilizando o OpenCV e um modelo pré-treinado de deep learning. O código utiliza a API DNN do OpenCV para processar as imagens capturadas de um vídeo, detectando objetos e desenhando caixas delimitadoras ao redor de cada um deles.

## Funcionalidades
- Detecção de objetos em tempo real a partir de um vídeo.
- Aplicação de Supressão Não Máxima para evitar caixas delimitadoras redundantes.
- Contagem e exibição do número de objetos detectados no vídeo.

## Modelo Pré-Treinado
O modelo utilizado para a detecção de objetos pode ser baixado através do seguinte link:

[Download frozen_inference_graph.pb](https://example.com/download-link)

Extraia o arquivo `frozen_inference_graph.pb` do arquivo tar.gz baixado e coloque-o no diretório `detecao-de-objetos` do projeto.

## Executando o Projeto
Para executar a detecção de objetos, simplesmente execute o script `main.py` com Python. Certifique-se de que todos os arquivos necessários estão na mesma pasta que o script.

```bash
python main.py

git add detecao-de-objetos/README.md
git commit -m "Entrega Realizada"
git push origin main

