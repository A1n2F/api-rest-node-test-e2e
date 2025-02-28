#Api-rest-Nodejs-test-e2e

Banco de dados desenvolvido para estudos do Nodejs com framework Fastify. Foi escolhido o Knex para a aplicação e realização da consulta ao banco, além das querys simples de inserção e busca. Os plugins do Fastify podem ser usados para adicionar funcionalidades como autenticação, log, validação de dados, gerenciamento de erros, entre outras e a criar e utilizar um plugin de rotas. Identificar o usuário que está utilizando a aplicação ao ler e escrever informações em Cookies utilizando o Fastify. Foi Utilizado a ferramenta Insomnia que permite fazer requisições HTTP de forma prática e intuitiva.

Testes e2e (end-to-end) são testes que validam o comportamento da aplicação como um todo, simulando a interação do usuário com a aplicação. Eles são importantes para garantir que a aplicação esteja funcionando corretamente em todos os níveis, desde a camada de interface até a camada de banco de dados.
Foi utilizado a ferramenta Vitest para criar e testar as rotas da aplicação com o teste automatizado e2e. Alguns métodos como: expect, test, beforeAll, afterAll, describe, beforeEach.
A aplicação está em Typescript, portanto foi necessário adicionar um framework chamado Supertest para garantir a funcionalidade efetiva dos testes.

A aplicação em si tem o sentido do usuário criar uma nova transação, onde ele escolhe se é do tipo "crédito" ou "débito", onde o crédito é acrescentado e o outro é retirado do saldo total. Além das funcionalidades de visualizar e listar as transações.

![tela4test](https://github.com/user-attachments/assets/9b0da54b-69fc-479a-9997-334709c72ef6)

-Tecnologias utilizadas: TYPESCRIPT.

-Bibliotecas: frameworks: Fastify. Knex. Zod para autenticação. Vitest e Supertest para testes automatizados.

-Trilha Nodejs - Rocketseat.
