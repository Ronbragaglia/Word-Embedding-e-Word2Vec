Observações sobre o Código:

Importações Necessárias:

O código começa com a instalação de bibliotecas essenciais (pandas, textblob, matplotlib, seaborn) e as importa para uso posterior.

Criação do DataFrame:

Um dicionário data é criado com dados de avaliações (incluindo IDs, pontuações, títulos, mensagens e timestamps).
Um DataFrame df é gerado a partir do dicionário.

Função para Análise de Sentimentos:

A função get_sentiment calcula a polaridade do texto usando a biblioteca TextBlob. Retorna None para valores nulos, permitindo evitar erros ao processar dados faltantes.

Aplicação da Análise de Sentimentos:

A coluna 'sentiment' é criada no DataFrame df, onde a função get_sentiment é aplicada à coluna review_comment_message.

Visualizações:

Distribuição das Notas de Review: Um gráfico de contagem (countplot) mostra a distribuição das notas de avaliação.

Distribuição dos Sentimentos: Um histograma (histplot) mostra a distribuição das polaridades dos sentimentos, com uma linha de densidade (KDE) para melhor visualização.
Exibição do DataFrame:

O DataFrame df é exibido no final, mostrando todas as colunas, incluindo a nova coluna 'sentiment'.

![image](https://github.com/user-attachments/assets/e5c1f345-a1dc-41ca-b986-661e90f66e3d)

![image](https://github.com/user-attachments/assets/03093d0a-da87-41ce-b57e-7ab1c5935bb4)

![image](https://github.com/user-attachments/assets/c0ac596a-4192-47a0-bcd3-ecf24100de32)
