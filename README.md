# Portfólio - André Felippe Mendes Silva

# Projetos Ciência de Dados, Machine Learning e Engenharia de Dados

## Engenharia de Dados
<a href='https://github.com/aandrefms/formulario/blob/master/main_test(1.1).py' target= '_blank' rel='noopener noreferrer'> UI de formulário com banco de dados SQL</a>: Projeto desenvolvido utilizando PyQt5 para a criação da UI e a linguagem Python para o back-end. Utilizei o PostgreSQL como escolha para o banco de dados e inclui na UI diversas funcionalidades como: Inserir, visualizar, procurar e apagar dados. Além disso, utilizei a biblioteca SQLAlchemy para incrementar a segurança e impedir SQL injections. O repositório completo pode ser acessado neste <a href='https://github.com/aandrefms/formulario' target= '_blank' rel='noopener noreferrer'>link</a>.<br>
<strong>Ferramentas utilizadas</strong>: Python, PyQt5, PostgreSQL, SQLAlchemy, Flask.


<a  href='https://github.com/aandrefms/ecommerce_db' target="_blank" rel="noopener noreferrer"> Banco de dados para Olist e-commerce</a>: Script em Python para criação de um database em snow flakes schema, afim de receber 8 tabelas e mais de 500.000 dados. Utilizei o PostgreSQL como escolha para o banco de dados, além de sqlAlchemy para inserção dos dados. O script criará automaticamente o DB (caso não exista) e as tabelas (caso não existam), além de inserir os dados (caso existam, fará o append).<br>
<strong>Ferramentas utilizadas</strong>: Python, PostgreSQL, SQLAlchemy, Pandas, psycopg2.

<a  href='https://github.com/aandrefms/ecommerce_db' target="_blank" rel="noopener noreferrer">Script Apache Kafka consumer-producer utilizando API</a>: Este Script fará a request da API do site OpenWeather, e então conectará um kafka producer para enviar esses dados para o localhost, e um kafka consumer para receber esses dados. Este processo visa utilizar-se do recurso de streaming de dados, ou seja, os dados são enviados e lidos de forma automática e simultânea.<br>
<strong>Ferramentas utilizadas</strong>: Apache Kafka, Python, request.

## Machine Learning e Ciência de Dados

<a href='https://github.com/aandrefms/projects/blob/master/Chatbot/main_portuguese_pt.py' target= '_blank' rel='noopener noreferrer'> Chatbot em Português usando redes neurais</a>: Este projeto foi desenvolvido a partir de ferramentas de Deep Learning (Redes Neurais) com o intuito de criar um chatBot sem utilizar de Codificação rígida. O banco de dados utilizado contem conversas com suas respectivas intenções ( conversação, mercado de ações, elogios, etc.).<br>
<strong>Ferramentas utilizadas</strong>: Redes Neurais (TensorFlow e Keras), Processamento de linguagem natural (NLP).

<a  href='https://github.com/aandrefms/projects/blob/master/aabb.ipynb' target="_blank" rel="noopener noreferrer"> Criação de perfil do cliente utilizando Data Science</a>: Projeto realizado para o maior clube atlético de São Luís/MA afim de gerar insights para tomada de decisões do time de publicidade. Para isso, foram utilizadas ferramentas de Data Science(extração, manipulação e visualização dos dados) e também de Data Mining. Ao final, gerei um perfil de cliente que poderá atender as necessidades da empresa.<br>
<strong>Ferramentas utilizadas</strong>: Python, Numpy, Pandas, Matplotlib, Scrapy, Selenium.

<a  href='https://github.com/aandrefms/projects/blob/master/An%C3%A1lise%20de%20Apps/App.ipynb' target="_blank" rel="noopener noreferrer">Exploração e Visualização de dados de Apps da Play Store</a>: Este trabalho de consultoria para uma Startup teve como objetivo explorar, analisar e inferir em um banco de dados de Apps da Play Store os motivos que fizeram certas categorias ou apps obterem melhor desempenho de vendas. Foram analisados aspectos como: Vantagem de ser pago ou gratuito; Tamanho do arquivo influencia no sucesso? Afim de encontrar um padrão entre os Aplicativos mais bem sucedidos.<br>
<strong>Ferramentas utilizadas</strong>: Matplotlib, plotly, seaborn.<br>

<a href='https://github.com/aandrefms/projects/blob/master/time_series/Untitled.ipynb' target='_blank' rel='noopener noreferrer'> Análise de série temporal</a>: Analisei os dados do consumo de energia de uma organização regional dos EUA afim de construir um modelo capaz de prever o comportamento do consumo de energia. Para isso, foram abordadas diversas técnicas e tópicos como estacionariedade e processos AR e MA.<br>
<strong>Ferramentas utilizadas</strong>: Pandas, XgBoost, Matplotlib. <br>


<a href='https://github.com/aandrefms/projects/blob/master/regression_car_price/reg01.ipynb' target='_blank'> Modelo de regressão para previsão de preços de veículos usados </a>: Este trabalho foi desenvolvido para se ajustar as necessidades de uma empresa de veículos usados em construir um catálogo eficaz de preços dos seus veículos. Para isso, desenvolvi um modelo de regressão que alcançou uma precisão de 98% de acurácia. Para isso, foram aplicadas técnicas de limpeza e transformações de dados, além de técnicas de aprendizado de máquina.<br>
<strong>Ferramentas utilizadas</strong>: Learn-scikit, matplotlib, plotly, seaborn.<br>


<a  href="https://github.com/aandrefms/projects/blob/master/Classifica%C3%A7%C3%A3o%20de%20Palavras/Classif_palavras.ipynb" target="_blank">Modelo para avaliação de comentários com Machine Learning</a>: Este trabalho foi desenvolvido com o intuito de criar um modelo, através de <strong>Machine Learning</strong>, que seja capaz de classificar comentários feitos em uma loja virtual de livros em positivos e negativos. Foram aplicados métodos de optimização de parâmetros afim de alcançar maior precisão.<br>
<strong>Ferramentas utilizadas</strong>: Matplotlib, seaborn, learn-scikit, skopt.<br>

<a  href="https://github.com/aandrefms/projects/blob/master/Stack%20Overflow/Stack%20Overflow.ipynb">Modelo para classificação utilizando Machine Learning</a>: Este trabalho foi desenvolvido com o intuito de aplicar Modelos de classificação para prever a categoria que determinada pergunta pertencia. Para isso, utilizei um dataset com 60.000 perguntas feitas no site Stack Overflow com um percentual de precisão de 88%. Foram aplicadas técnicas como <strong>vetorização</strong> e <strong>Machine Learning</strong>.<br>
<strong>Ferramentas utilizadas</strong>: Matplotlib, seaborn, learn-scikit, skopt.<br>

<a href="https://github.com/aandrefms/projects/blob/master/amazon1/amazon1/spiders/books.py" target="_blank">Scraping dados do site da Amazon</a>: O intuito deste script foi colher informações de forma automática do site da Amazon (Web Scraping). Foram extraidas 1000 linhas de dados de uma categoria de livros, podendo se extender para todo o site da Amazon. Foram obtidas informações como: nome do autor, nome do livro, preço, avaliações. Web Scraping tem grande utilidade para a coleta de informações de diferentes websites.<br>
<strong>Ferramenta utilizada</strong>: Scrapy.<br>

<a  href="https://github.com/aandrefms/projects/blob/master/imdb/imdb/spiders/imdb.py" target="_blank">Scraping dados do site IMDB</a>: O intuito deste projeto foi desenvolver um script capaz de obter informações, de forma automática, do site IMDB. Foram extraidas informações como: Nome de filmes, Nome de autores, Avaliações.<br>
<strong>Ferramenta utilizada</strong>: Scrapy.<br>

