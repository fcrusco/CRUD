# Projeto: CRUD Windows Forms com SQL Server

![image](https://github.com/user-attachments/assets/3467f96d-bafc-43f5-b2bf-abcd21ccd116)

Este projeto é um exemplo prático de um CRUD completo (Create, Read, Update, Delete) desenvolvido com Windows Forms (.NET), utilizando procedures no SQL Server e acesso a dados via SqlClient.

-A aplicação permite:
Cadastro de usuários (Nome e Sobrenome)
Edição de registros existentes
Exclusão
Listagem em um DataGridView com seleção para edição
Controle total via procedures SQL

-Tecnologias Utilizadas
.NET 8 Windows Forms
SQL Server 2022
C#
Procedures no banco

-Estrutura do Projeto
/Repository
  └── UsuarioRepository.cs    → Camada de acesso ao banco
/Form1.cs                     → Tela principal (CRUD)
/App.config                   → String de conexão
/Program.cs                   → Entry point

-Funcionalidades
Inserir novo usuário
Atualizar dados
Excluir com confirmação
Listar registros no grid

-Como usar
Configure sua string de conexão no App.config
Execute o script de criação da tabela e procedures (disponível na pasta /Scripts)
Rode a aplicação via Visual Studio
Use os botões Novo, Gravar, Apagar, Listar para testar

-Observações
O usuário do SQL (sistema_app) deve ter permissão EXECUTE nas procedures
A tabela de usuários (TB_USUARIO) pode ser expandida com novos campos

-Possíveis melhorias
Camada de serviço (Service Layer)
Validações visuais (DataAnnotations ou FluentValidation)
Integração com Dapper ou Entity Framework
Deploy via ClickOnce
