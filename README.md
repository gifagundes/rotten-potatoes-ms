# Projeto Rotten Tomatoes Microsserviços

## Estrutura do projeto
Esse projeto é baseado em uma aquitetura de Microsserviços e depende de outros 2 projetos pra funcionar

- [Serviço de Filmes](https://github.com/kubedev/movie)
- [Serviço de Review](https://github.com/kubedev/review)

Segue abaixo o diagrama:

![Diagrama da solução](./img/diagrama.png)

## Configuração

MOVIE_SERVICE_URI => URL de acesso ao serviço de listagem de filmes

REVIEW_SERVICE_URI => URL de acesso ao serviço de listagem de reviews

Exemplo:

MOVIE_SERVICE_URI: http://movies:8181

REVIEW_SERVICE_URI: http://review:8282


-----------------------------------------

# TESTES

<p>Faça o download deste repositório e das seguintes dependências que devem estar na mesma pasta raiz:</p>

<p><a href="https://github.com/gifagundes/movie" target="_blank">Movies</a></p>
<p><a href="https://github.com/gifagundes/review" target="_bkank">Reviews</a></p>

<p>Para rodar este ambiente execute na pasta raiz</p>

<p>docker-compose up -d --remove-orphans --build</p>

<p>Para desmontar o ambiente execute</p>

<p>docker-compose down</p>

