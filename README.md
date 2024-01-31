**Readme - Previsão de Preços de Imóveis em São Paulo** 🏡📊

Bem-vindo ao projeto de previsão de preços de imóveis em São Paulo! Este experimento utiliza Machine Learning para estimar os valores de imóveis com base em diferentes características. Aqui está um guia rápido para começar:

### Estrutura do Projeto:

1. **Análise e Tratamento de Dados** 📈🧹:
   - Os dados foram analisados, e a informação desnecessária nos nomes dos bairros foi removida.
   - O conjunto de dados inclui informações sobre aluguel e venda de imóveis.

2. **Modelo de Machine Learning** 🤖🌲:
   - Utilizamos o algoritmo Random Forest para treinar o modelo.
   - Três métricas principais (precisão, recall, F1-score) foram observadas durante a avaliação.

3. **Persistência do Modelo** 💾:
   - O modelo treinado foi salvo como 'modelo_treinado.joblib'.
   - Para carregar o modelo em outras instâncias, utilize `joblib.load('modelo_treinado.joblib')`.

4. **Previsão de Preços com Interface Gráfica** 🖥️💰:
   - Desenvolvemos uma interface gráfica simples usando Tkinter.
   - Execute o script fornecendo os detalhes do imóvel para obter uma previsão de preço.

### Instruções de Uso:

1. **Pré-requisitos**:
   - Certifique-se de ter instalado todas as dependências listadas no arquivo `requirements.txt`.

2. **Execução do Modelo**:
   - Execute o script `Machine_Learning_para_Preço_de_Imóveis_em_São_Paulo.ipynb`.
   - Insira os dados solicitados na interface gráfica e clique em "Prever Preço".

3. **Visualização de Resultados**:
   - O resultado será exibido na interface, indicando o preço previsto do imóvel.

### Arquivos Adicionais:

1. **Nomes dos Bairros** 🏙️:
   - Os nomes dos bairros utilizados estão salvos no arquivo 'nomes_bairros.txt'.

### Contribuições e Problemas:

- Aceitamos contribuições! Sinta-se à vontade para abrir issues ou enviar pull requests.

Aproveite o experimento de previsão de preços de imóveis em São Paulo! 🚀🏠
