#Setup Environment

  • Open the integrated terminal.
  • Change directories (cd) to the folder that will contain the project folder.
  • Run the following commands:
.NET Core CLI
<pre>dotnet new webapi -o TodoApi</pre>



<pre>cd TodoApi</pre>

<pre>dotnet add package Microsoft.EntityFrameworkCore.SqlServer</pre>
<pre>dotnet add package Microsoft.EntityFrameworkCore.InMemory</pre>
<pre>code -r ../TodoApi</pre>


• When a dialog box asks if you want to add required assets to the project,
select Yes.
The preceding commands:
o Creates a new web API project and opens it in Visual Studio Code.
o Adds the NuGet packages which are required in the next section.
