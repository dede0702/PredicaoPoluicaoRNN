# Previsão de Poluição com Redes Neurais Recorrentes (RNN)

## Descrição do Projeto

Este projeto utiliza Redes Neurais Recorrentes (RNN) para prever níveis de poluição atmosférica com base em dados históricos. O modelo é treinado para detectar padrões temporais e prever concentrações futuras de poluentes, proporcionando uma ferramenta útil para monitoramento ambiental e tomada de decisões.

## Estrutura do Projeto

- **`PredicaoPoluicaoRNN.ipynb`**: O notebook principal contendo o código para processamento, treinamento e avaliação do modelo RNN.
- **Dados**: Dataset utilizado para o treinamento do modelo, contendo variáveis atmosféricas e de poluição.
  
## Funcionalidades

- **Processamento de dados**: Limpeza e transformação dos dados para alimentar o modelo.
- **Criação do modelo RNN**: Configuração de uma Rede Neural Recorrente personalizada para previsão de séries temporais.
- **Treinamento do modelo**: Treinamento do modelo utilizando dados históricos de poluição.
- **Avaliação**: Análise do desempenho do modelo com métricas de erro.

## Requisitos

Para executar este projeto, você precisa dos seguintes pacotes:

- `numpy`
- `pandas`
- `matplotlib`
- `tensorflow`
- `scikit-learn`

## Instalação

Instale as dependências do projeto utilizando o gerenciador de pacotes `pip`:

```bash
pip install numpy pandas matplotlib tensorflow scikit-learn

Como Executar

1. Clone o repositório e navegue até o diretório do projeto.


2. Abra o notebook PredicaoPoluicaoRNN.ipynb no Jupyter Notebook ou Google Colab.


3. Execute as células sequencialmente para:

Processar os dados

Configurar e treinar o modelo RNN

Avaliar a precisão do modelo

```bash

```bash
Configurações do Modelo

O modelo RNN foi configurado com os seguintes parâmetros:

Número de épocas: 50 (personalizável)

Tamanho do batch: 32

Camadas ocultas: 2 camadas LSTM com 50 neurônios cada

Função de perda: mean_squared_error

Otimizador: adam


Exemplo de Uso

Abaixo está um exemplo de como utilizar o modelo para previsão após o treinamento:

import numpy as np

# Dados de entrada para previsão
novo_dado = np.array([...])  # Insira os valores do novo dado para previsão

# Previsão
previsao = modelo.predict(novo_dado)
print("Previsão de poluição:", previsao)

```bash

Contribuições

Sinta-se à vontade para abrir issues para relatar problemas ou discutir melhorias. Contribuições são bem-vindas através de pull requests.

Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.

Contato

Para mais informações, entre em contato pelo email: andrerovaijr722@gmail.com



