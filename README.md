# Teste para a vaga de Programador Pleno

## Objetivo

Este teste tem como objetivo entender um pouco mais de como você desenvolve e cria as suas lógicas. Também vai ser analisado a sua organização.

## Descrição do teste

O teste consiste em criar uma API que vai receber uma requisção com um código de categoria do Mercado Livre, após receber o código a API deve guardar esta informação em algum lugar ( fila ) para um outro procedimento buscar toda descrição e informação da categoria e guardar em um banco de dados.

--
Passo a passo do teste
--

1 - Criar uma API com alguma autenticação

2 - Receber um código de categoria do ML e guarda esta informação em algum lugar ( fila ou banco )

3 - Criar um procedimento que de tempo em tempo ( ou instantâno se for fila ) e busque na API do Mercado Livre toda descrição da categoria e guarde em um Banco de Dados ( MySQL )

4 - Criar um endpoint de listar as categorias cadastradas

## Diferenciais
 - Criar um front-end para enviar o código da categoria para API
 - Criar um front-end para listar as categorias cadastradas
 - Organização do Código \n
 - RabbitMQ \n
 - JWT \n

## Entrega
Após finalizar o teste você deverá criar um repositório público no github e colocar um readme com todas as informações de como vamos instalar o seu projeto em nosso ambiente local. Feito o seu git com o projeto e a descrição, encaminhe um e-mail para contato@goolhub.com.br para que possamos analisar.

Bom teste!!
