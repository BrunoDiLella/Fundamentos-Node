# Projeto de Fundamentos de Node.js em JavaScript

Este projeto foi desenvolvido como uma forma de aprender e demonstrar os fundamentos de Node.js utilizando JavaScript. Ele implementa operações básicas de CRUD (Create, Read, Update, Delete) para gerenciar uma lista de usuários em um servidor HTTP.

## O Que Este Projeto Faz?

O projeto implementa um servidor HTTP utilizando o Node.js que fornece endpoints para criar, listar, editar e excluir usuários. Os endpoints disponíveis são:

- **GET /users:** Retorna uma lista de usuários.
- **POST /users:** Cria um novo usuário.
- **PUT /users/:id:** Atualiza um usuário existente.
- **DELETE /users/:id:** Remove um usuário existente.

## Conceitos e Tecnologias Utilizados

Durante o desenvolvimento deste projeto, foram explorados diversos conceitos e tecnologias, incluindo:

- **Node.js:** Uma plataforma de desenvolvimento para a construção de aplicações servidoras utilizando JavaScript.
- **HTTP:** Protocolo de comunicação utilizado para transferência de dados na web.
- **CRUD Operations:** Operações básicas de criação, leitura, atualização e exclusão em bancos de dados ou sistemas.
- **HTTP Methods:** Métodos padrão utilizados em requisições HTTP, incluindo GET, POST, PUT, PATCH e DELETE.
- **Route Handling:** Como lidar com diferentes rotas e métodos HTTP em um servidor Node.js.
- **Query Parameters e Route Parameters:** Utilização de parâmetros em URLs para filtrar recursos ou identificar recursos específicos.
- **Persistência de Dados:** Utilização de arquivos JSON como banco de dados simples para armazenar e manipular dados de usuários.
- **Promises:** Utilização de Promises para operações assíncronas de leitura e escrita de arquivos.
- **Módulos em Node.js:** Organização do código em módulos reutilizáveis para facilitar a manutenção e extensibilidade do projeto.

## Streams em Node.js

As streams são uma forma eficiente de lidar com a leitura e escrita de dados em Node.js, especialmente quando se trabalha com grandes volumes de dados. Elas permitem que os dados sejam processados de forma assíncrona e em pequenos pedaços, reduzindo a sobrecarga de memória e melhorando a eficiência do aplicativo.

Em Node.js, as streams são implementadas por meio de quatro tipos principais:

1. **Readable Streams:** Responsáveis pela leitura de dados de uma fonte, como um arquivo, uma requisição HTTP ou uma entrada do usuário.
2. **Writable Streams:** Responsáveis pela escrita de dados em um destino, como um arquivo, uma conexão de rede ou uma saída do usuário.
3. **Duplex Streams:** Streams que são tanto legíveis quanto graváveis, permitindo a leitura e escrita simultâneas de dados.
4. **Transform Streams:** Um tipo especial de duplex stream que permite a transformação dos dados enquanto são transmitidos de uma fonte para um destino.

Streams são amplamente utilizadas em Node.js para operações como leitura e escrita de arquivos, manipulação de dados em tempo real, e comunicação entre diferentes partes de uma aplicação.

## Recursos Adicionais

Se você está interessado em aprender mais sobre os conceitos abordados neste projeto, aqui estão alguns recursos recomendados:

- [Node.js Docs](https://nodejs.org/en/docs/): Documentação oficial do Node.js para aprender mais sobre como utilizar o Node.js para construir aplicações servidoras.
- [HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status): Lista completa de códigos de status HTTP e seus significados.
- [RESTful API Design](https://restfulapi.net/): Recomendações e boas práticas para projetar APIs RESTful.
- [JavaScript Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise): Guia completo sobre Promises em JavaScript.
- [Node.js Streams](https://nodejs.org/en/docs/guides/backpressuring-in-streams/): Documentação oficial sobre streams em Node.js.

## Como Executar o Projeto

Para executar o projeto em modo de desenvolvimento, siga as instruções abaixo:

1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter o Node.js instalado em sua máquina.
3. Execute `npm install` para instalar as dependências do projeto.
4. Execute `npm run dev` para iniciar o servidor em modo de desenvolvimento.
5. Você pode utilizar ferramentas como cURL, Postman ou seu navegador para fazer requisições para os endpoints fornecidos.
