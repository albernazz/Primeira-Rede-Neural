# Classificador de Dígitos MNIST com PyTorch

Este projeto implementa um classificador de dígitos manuscritos usando o conjunto de dados MNIST e a biblioteca PyTorch.

## Descrição

O código treina uma rede neural simples para reconhecer dígitos de 0 a 9. Ele utiliza:

- **PyTorch:** Para construir e treinar o modelo de rede neural.
- **MNIST:** Um conjunto de dados clássico de imagens de dígitos manuscritos.
- **DataLoader:** Para carregar os dados em batches durante o treinamento.
- **ReLU:** Função de ativação para as camadas ocultas.
- **Softmax:** Para calcular a probabilidade de cada classe na saída.

## Como Executar

1. **Clone o repositório:** `git clone https://github.com/seu_usuario/seu_repositorio.git`
2. **Instale as dependências:** `pip install torch torchvision matplotlib`
3. **Execute o código:** `python seu_codigo.py`

## Resultados

O modelo alcança uma precisão de aproximadamente **[insira a precisão aqui]%** no conjunto de teste MNIST após o treinamento.

## Observações

- O código está estruturado para facilitar a compreensão e modificação.
- Você pode ajustar os hiperparâmetros, como a taxa de aprendizado e o número de épocas, para melhorar o desempenho.
- Este projeto serve como um ponto de partida para aprender sobre classificação de imagens com PyTorch.
