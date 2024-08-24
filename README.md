# Projeto de Reconhecimento de Padrões
> Descrição: Projeto de classificação de dígitos escritos à mão usando o dataset MNIST Adaptado, contendo dígitos 0, 1, 4 e 5.

## Desenvolvedores
- [@kamilyassis](https://www.github.com/kamilyassis)
- [@adriel1ft](https://github.com/adriel1ft)

## Etapas do Projeto
1. Preparação dos Dados [feito]
Redução de Dimensão: Reduzir a complexidade dos dados extraindo as características de intensidade e simetria de cada imagem.
Geração de Novos Arquivos: Criar os arquivos train_redu.csv e test_redu.csv contendo as colunas: label, intensidade, simetria.

3. Classificação Binária (Dígitos 1 x 5)
Filtro de Dados: Filtrar os dados para conter apenas dígitos 1 e 5.
Visualização: Plotar os dados de intensidade e simetria em um gráfico bidimensional.
Treinamento: Implementar três classificadores (Perceptron, Regressão Linear, Regressão Logística) e treinar com os dados filtrados.
Predição e Avaliação: Realizar predições nos dados de teste, gerando matriz de confusão e relatórios de eficácia.

4. Classificação Multiclasse (0, 1, 4, 5)
Estratégia "Um Contra Todos": Implementar um classificador para cada dígito, utilizando a abordagem de "um contra todos".
Construção das Funções Hipótese: Criar uma função para cada dígito, aplicando a estratégia para classificar cada imagem.

5. Comparação de Classificadores
Comparação: Comparar os três classificadores usando as métricas de acurácia, precisão, recall e F1-score.
Matriz de Confusão: Gerar matrizes de confusão para cada classificador.

6. Implementações Avançadas (Opcional*)
Weight Decay: Implementar regularização com weight decay para o algoritmo de regressão logística.
Otimização da Ordem de Classificação: Testar diferentes ordens de classificação dos dígitos para otimizar a acurácia.

### Principais Referências

[Logistic Regression in Python from Scratch | Simply Explained](https://www.youtube.com/watch?v=nzNp05AyBM8)
[Regressão Logística – Algoritmos de Aprendizado de Máquinas](https://www.hashtagtreinamentos.com/regressao-logistica-ciencias-dados)
