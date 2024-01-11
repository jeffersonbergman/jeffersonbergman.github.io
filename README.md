#Documentação do Projeto de Página Web da Igreja Batista Antioquia

##Visão Geral

Este projeto consiste em duas plataformas web para o site da Igreja Batista Antioquia. A primeira plataforma é uma página simples que inclui as páginas Home, About Us, Contato, Calendário e Programas da Igreja. A segunda plataforma é uma página com autenticação para administradores poderem adicionar e editar as páginas.

Arquitetura

O projeto é composto pelos seguintes componentes:

Web API: Fornece uma API RESTful para acessar as informações das páginas.
Front-end simples: Fornece uma interface para visualizar as páginas.
Front-end com autenticação: Fornece uma interface para administradores adicionarem e editarem as páginas.
Código

O código do projeto está escrito em C# e usa o framework ASP.NET Core. A Web API usa o padrão RESTful para fornecer acesso às informações das páginas. O front-end simples usa HTML, CSS e JavaScript para visualizar as páginas. O front-end com autenticação usa Angular para fornecer uma interface de usuário mais sofisticada.

Cores

As cores usadas no projeto são as seguintes:

Cor primária: #FF0000
Cor de destaque: #00FF00
Cor de fundo: #FFFFFF
Essas cores são usadas em todo o projeto, incluindo o logotipo, o menu principal e os componentes.

API RESTful

A Web API fornece as seguintes operações CRUD para as informações das páginas:

GET: Obtém uma página específica.
POST: Cria uma nova página.
PUT: Atualiza uma página existente.
DELETE: Exclui uma página.
Parâmetros

Os parâmetros das operações CRUD são os seguintes:

Id: O ID da página.
Nome: O nome da página.
Conteúdo: O conteúdo da página.
Exemplos

Aqui estão alguns exemplos de como usar a API RESTful:

Obter uma página:
GET /api/pages/1
Este exemplo obtém a página com o ID 1.

Criar uma nova página:
POST /api/pages
{
  "nome": "Home",
  "conteudo": "Esta é a página inicial da Igreja Batista Antioquia."
}
Este exemplo cria uma nova página com o nome "Home" e o conteúdo "Esta é a página inicial da Igreja Batista Antioquia."

Atualizar uma página existente:
PUT /api/pages/1
{
  "nome": "Página Principal",
  "conteudo": "Esta é a página principal da Igreja Batista Antioquia."
}
Este exemplo atualiza a página com o ID 1 com o nome "Página Principal" e o conteúdo "Esta é a página principal da Igreja Batista Antioquia."

Excluir uma página:
DELETE /api/pages/1
Este exemplo exclui a página com o ID 1.

Front-end Simples

O front-end simples usa HTML, CSS e JavaScript para visualizar as páginas. A página inicial inclui links para as outras páginas. As outras páginas incluem o nome e o conteúdo da página.

Front-end com Autenticação

O front-end com autenticação usa Angular para fornecer uma interface de usuário mais sofisticada. Os administradores podem adicionar e editar as páginas usando formulários.
