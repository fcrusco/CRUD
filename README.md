# Projeto: CRUD Windows Forms com SQL Server

![image](https://github.com/user-attachments/assets/3467f96d-bafc-43f5-b2bf-abcd21ccd116)
<br>
Este projeto é um exemplo prático de um CRUD completo (Create, Read, Update, Delete) desenvolvido com Windows Forms (.NET), utilizando procedures no SQL Server e acesso a dados via SqlClient.
<br><br>
-A aplicação permite:<br>
Cadastro de usuários (Nome e Sobrenome)<br>
Edição de registros existentes<br>
Exclusão<br>
Listagem em um DataGridView com seleção para edição<br>
Controle total via procedures SQL
<br><br>
-Tecnologias Utilizadas<br>
.NET 8 Windows Forms<br>
SQL Server 2022<br>
C#<br>
Procedures no banco<br><br>

-Estrutura do Projeto<br>
/Repository<br>
  └── UsuarioRepository.cs    → Camada de acesso ao banco<br>
/Form1.cs                     → Tela principal (CRUD)<br>
/App.config                   → String de conexão<br>
/Program.cs                   → Entry point<br>
<br>
-Funcionalidades<br>
Inserir novo usuário<br>
Atualizar dados<br>
Excluir com confirmação<br>
Listar registros no grid<br>
<br>
-Como usar<br>
Configure sua string de conexão no App.config<br>
Execute o script de criação da tabela e procedures (disponível na pasta /Scripts)<br>
Rode a aplicação via Visual Studio<br>
Use os botões Novo, Gravar, Apagar, Listar para testar<br>
<br>
-Observações<br>
O usuário do SQL (sistema_app) deve ter permissão EXECUTE nas procedures<br>
A tabela de usuários (TB_USUARIO) pode ser expandida com novos campos<br>
<br>
-Possíveis melhorias<br>
Camada de serviço (Service Layer)<br>
Validações visuais (DataAnnotations ou FluentValidation)<br>
Integração com Dapper ou Entity Framework<br>
Deploy via ClickOnce<br>
