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
<br>
# Project: CRUD Windows Forms with SQL Server

![image](https://github.com/user-attachments/assets/3467f96d-bafc-43f5-b2bf-abcd21ccd116)
<br>
This project is a practical example of a complete CRUD (Create, Read, Update, Delete) developed with Windows Forms (.NET), using stored procedures in SQL Server and data access via SqlClient.
<br><br>
-The application allows:<br>
User registration (First and Last Name)<br>
Editing of existing records<br>
Deletion<br>
Listing in a DataGridView with selection for editing<br>
Full control via SQL procedures
<br><br>
-Technologies Used<br>
.NET 8 Windows Forms<br>
SQL Server 2022<br>
C#<br>
Database procedures<br><br>

-Project Structure<br>
/Repository<br>
  └── UsuarioRepository.cs    → Database access layer<br>
/Form1.cs                     → Main screen (CRUD)<br>
/App.config                   → Connection string<br>
/Program.cs                   → Entry point<br>
<br>
-Features<br>
Insert new user<br>
Update data<br>
Delete with confirmation<br>
List records in the grid<br>
<br>
-How to Use<br>
Configure your connection string in App.config<br>
Run the table and procedures creation script (available in the /Scripts folder)<br>
Run the application using Visual Studio<br>
Use the New, Save, Delete, List buttons to test<br>
<br>
-Notes<br>
The SQL user (sistema_app) must have EXECUTE permission on the procedures<br>
The user table (TB_USUARIO) can be expanded with new fields<br>

<br>
-Possíveis melhorias<br>
Camada de serviço (Service Layer)<br>
Validações visuais (DataAnnotations ou FluentValidation)<br>
Integração com Dapper ou Entity Framework<br>
Deploy via ClickOnce<br>
