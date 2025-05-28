<h2> Zhuyu CHen Su - RA: 10400811 - Turma: 07J</h2>
  <h3>Data da atualização: 29/03/2025</h3>
  <h3>Descrição: essa atualização insere todo o código fonte da análise exploratória, junto com o arquivo que contém a base de dados utilizada para a análise.</h3>


<p>A base de dados adquirida, do site da câmara legislativa, em arquivo de formato “.json” é tratado e transformado em um dataframe com a biblioteca Pandas. Em seguida são realizados os seguintes passos: Remover valores nulos no campo “transcrição” para evitar erros; Exibir estatísticas básicas, como número de discursos por partido; Criar um histograma para mostrar a distribuição do tamanho dos discursos (quantidade de palavras);  Contar as palavras mais comuns, excluindo stopwords, através da biblioteca NLTK; Gerar uma Nuvem de Palavras para visualizar os termos mais frequentes;  Exibir um gráfico de barras para visualizar a quantidade de discursos por partido; Fazer uma análise dos sentimentos nos discursos para identificar se há negatividade ou positividade, com a biblioteca textblob.</p>
<br>
<p> </p>


  <h3>Data da atualização: 27/05/2025</h3>
  <h3>Descrição: essa atualização insere todo o código usado para analisar a coerência entre discursos parlamentares e projetos de lei, com foco na reforma do Ensino Médio brasileiro, junto com o arquivo que contém a base de dados utilizada para a análise.</h3>


<p>Utilizando técnicas de Processamento de Linguagem Natural (PLN) e modelos de linguagem avançados, como o BERT em português, o trabalho buscou quantificar o alinhamento semântico entre os discursos proferidos na Câmara dos Deputados e o conteúdo legislativo em debate. A abordagem incluiu coleta de dados via API de Dados Abertos, pré-processamento textual, geração de embeddings, cálculo de similaridade de cosseno e visualização dos resultados com técnicas como t-SNE. </p>
