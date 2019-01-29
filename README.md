# data-wrangling-we-rate-dogs
Projeto de Data Wrangling do Nanodegree de Fundamentos de Data Science II (Udacity)

## Introdução
Dados do mundo real raramente vem limpos. Colete dados de uma série de fontes em uma variedade de formatos, avalie sua qualidade e arrumação e, então, limpe-os. Isso é chamado de data wrangling. Você irá documentar seus esforços de wrangling em um notebook Jupyter, além de exibi-los por meio de análises e visualizações usando Python e/ou SQL.

O conjunto de dados no qual você irá fazer o wrangling (e analisar e visualizar) é o arquivo de tweets do usuário do Twitter [@dog_rates](https://twitter.com/dog_rates), também conhecido como [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs é uma conta no Twitter que classifica os cães das pessoas com um comentário bem humorado sobre o cão. Ele foi iniciado em 2015 pelo estudante universitário Matt Nelson e recebeu cobertura da mídia internacional. Em outubro de 2017 tinha mais 3,7 milhões de seguidores. Estas classificações têm quase sempre um denominador de 10. Mas e os numeradores? Quase sempre maior que 10. 11/10, 12/10, 13/10, etc. Por quê? Porque "[são bons cães, Brent.](https://knowyourmeme.com/memes/theyre-good-dogs-brent)"

#### Requisitos

Necessário ter acesso a ferramenta de desenvolvimento do Twitter, utilizando suas chaves no Notebook.
Necessário ter instalado os seguintes pacotes:
* pandas
* numpy
* requests
* tweepy
* json

### Arquivos do Repositório

* **wrangle_act.ipynb:** Jupiter Notebook com o script utilizado no Data Wrangling.
* **twitter-archive-enhanced.csv:** Arquivo fornecido para download no projeto.
* **image_predictions.tsv:** Arquivo baixado (e salvo) durante a execução do Jupyter Notebook por meio de um link disponibilizado.
* **tweet_json.txt:** Tweets obtidos pela API do twitter com o pacote *tweepy*, gerado durante o Jupyter Notebook e persistido no arquivo .txt, cada linha do arquivo é um objeto json relativo a cada tweet.
* **twitter_archive_master.csv:** Base de dados após o procedimento do Data Wrangling.
* **reports**
  * **act_report.pdf:** documentação das análises e insights sobre os dados finais.
  * **wrangle_report.pdf:** documentação para os passos de data wrangling: coletar, avaliar e limpar.
  * **wrangle_act.html:** Jupyter Notebook em HTML para a visualização dos resultados.
