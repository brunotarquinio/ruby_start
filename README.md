#MyRottenPotatoes - Projeto do Livro "Engineering Software as a Service"
Este repositório contém a implementação da aplicação "MyRottenPotatoes", um clone simplificado do Rotten Tomatoes.

A aplicação foi desenvolvida em Ruby on Rails e permite aos usuários listar, adicionar, editar e remover filmes. A principal funcionalidade implementada neste trabalho foi a capacidade de ordenar a lista de filmes de forma interativa.

##Funcionalidades Implementadas:
Listagem de todos os filmes a partir de um banco de dados.

Criação, Edição e Exclusão de filmes.

Ordenação da lista: A lista de filmes pode ser ordenada dinamicamente clicando nos cabeçalhos das colunas "Título do Filme" e "Data de Lançamento".

##Tecnologias Utilizadas:

Ruby on Rails

SQLite3 (banco de dados)

RSpec (para testes)

ERB (para as views)

CSS

##Como Instalar e Rodar a Aplicação:
Siga os passos abaixo para configurar e executar a aplicação em um ambiente de desenvolvimento local.

Pré-requisitos:
Antes de começar, garanta que você tenha os seguintes softwares instalados:

Git

Ruby 2.6.6 (recomenda-se o uso de um gerenciador de versões como rbenv ou RVM)

Bundler

###Passos para Instalação
Clone o repositório pelo terminal:

git clone https://github.com/brunotarquinio/ruby_start
cd ruby_start

Instale as dependências (gems):
O Bundler irá instalar todas as bibliotecas necessárias que estão listadas no Gemfile.

bundle install

Configure o banco de dados:
Este comando irá criar o banco de dados e aplicar a estrutura de tabelas necessária (as "migrations").

bundle exec rake db:migrate

Popule o banco de dados:
Este comando irá popular o banco de dados com uma lista inicial de filmes para teste.

bundle exec rake db:seed

Como Rodar a Aplicação
Inicie o servidor Rails:

bundle exec rails server

Acesse no navegador:
Abra seu navegador e acesse a seguinte URL:
http://localhost:3000/movies
