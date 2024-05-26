# semana6-atividade-programacao

# Reconhecimento de Objetos em Imagens

## Descrição do Projeto

Este projeto implementa um modelo de reconhecimento de objetos em imagens utilizando PyTorch. O modelo foi treinado utilizando a arquitetura ResNet-18 pré-treinada e ajustada para classificar imagens de formigas e abelhas. Uma API em Flask foi criada para receber imagens e retornar a categoria inferida pelo modelo.

## Como Executar

### Requisitos

- Python 3.7+
- Flask
- PyTorch
- Torchvision
- PIL
- Requests

### Passos

### Uso da API
Para usar a API, envie uma solicitação POST para o endpoint /predict com uma imagem. Aqui está um exemplo utilizando curl:

curl -X POST -F "file=@caminho/para/sua/imagem.jpg" http://127.0.0.1:5000/predict



Claro, aqui está o conteúdo do relatório em Markdown (README.md) que descreve o projeto, explica como executá-lo e apresenta os resultados dos testes:

markdown
Copy code
# Reconhecimento de Objetos em Imagens

## Descrição do Projeto

Este projeto implementa um modelo de reconhecimento de objetos em imagens utilizando PyTorch. O modelo foi treinado utilizando a arquitetura ResNet-18 pré-treinada e ajustada para classificar imagens de formigas e abelhas. Uma API em Flask foi criada para receber imagens e retornar a categoria inferida pelo modelo.

## Como Executar

### Requisitos

- Python 3.7+
- Flask
- PyTorch
- Torchvision
- PIL
- Requests

### Passos

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu_usuario/seu_repositorio.git
Navegue até o diretório do projeto:
sh
Copy code
cd seu_repositorio
Instale as dependências:
sh
Copy code
pip install -r requirements.txt
Execute o script para treinar o modelo e criar a API:
sh
Copy code
python implementacao_completa.py
Uso da API
Para usar a API, envie uma solicitação POST para o endpoint /predict com uma imagem. Aqui está um exemplo utilizando curl:

curl -X POST -F "file=@caminho/para/sua/imagem.jpg" http://127.0.0.1:5000/predict


### Resultados dos Testes

#### Caso de Teste 1
- **Imagem:** formiga1.jpg
- **Resultado Esperado:** Formiga
- **Resultado Obtido:** Formiga

#### Caso de Teste 2
- **Imagem:** abelha1.jpg
- **Resultado Esperado:** Abelha
- **Resultado Obtido:** Abelha

#### Caso de Teste 3
- **Imagem:** formiga2.jpg
- **Resultado Esperado:** Formiga
- **Resultado Obtido:** Formiga
