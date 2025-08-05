# Como rodar esse app

1. **Faça uma cópia do repositório**

2. **Crie um banco de dados no SQL Server**

3. **Atualize o arquivo `appsettings.json`**  
   Altere os valores de `Source` com o nome do seu computador e de `Catalog` com o nome do banco de dados que criou.

4. **Migrations**  
   Crie as tabelas do banco de dados com os comandos abaixo:

   ```bash
   dotnet ef migrations add init
   dotnet ef database update
