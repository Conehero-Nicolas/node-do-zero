API de Vídeos com Node.js e Fastify
Este é um projeto simples de uma API RESTful para cadastro de vídeos, desenvolvido em Node.js utilizando o framework Fastify. A aplicação permite operações de CRUD (Criar, Ler, Atualizar e Deletar) para vídeos, com a opção de persistência de dados em um banco de dados PostgreSQL (utilizando Neon) ou em memória.

Funcionalidades

Criação de vídeos: Adicione novos vídeos à base de dados.

Listagem de vídeos: Obtenha uma lista de todos os vídeos cadastrados.

Busca de vídeos: Filtre a lista de vídeos por título.

Atualização de vídeos: Modifique as informações de um vídeo existente.

Exclusão de vídeos: Remova um vídeo da base de dados.

Tecnologias Utilizadas

Backend: Node.js

Framework: Fastify

Banco de Dados: 

  PostgreSQL (com o driver postgres e integração com Neon DB)
  
  Opção de banco de dados em memória para desenvolvimento

Variáveis de Ambiente: dotenv

Geração de ID: randomUUID nativo do Node.js
