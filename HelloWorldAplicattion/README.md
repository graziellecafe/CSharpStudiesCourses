✨ [Build ASP.NET Core Web API - Scratch to Finish (.Net8 API)
]

Visão Geral

Vamos usar a API para realizar outras operações, como criar, atualizar excluir.
Começaremos nosso curso entendendo os princípios do Rest, criaremos e entenderemos os novo projeto.

Este projeto é uma aplicação [API RESTful / Aplicação Web Full-Stack ] desenvolvida em C# e .NET, com um frontend em React.

🛠️ Stack Tecnológica

Backend: C# | .NET [Versão: 8.0]

Frontend: React [Versão: 18] | JavaScript/TypeScript

Database: [SQL Server / PostgreSQL / SQLite / MongoDB]

Gerenciamento de Pacotes: NuGet (C#) e npm/Yarn (React)

IDE: JetBrains Rider

Cloud (Futuro): Preparação para Azure / AWS

⚙️ Configuração e Execução

Estas são as instruções para configurar e rodar o projeto localmente no Mac (usando o Rider ou Terminal).

Pré-requisitos

.NET SDK [Versão, ex: 8.0] (Verifique com dotnet --version)

Node.js e npm (Para o projeto React)

1. Backend (C# e .NET)

Abra o Terminal na pasta raiz do projeto C# (onde está o arquivo .csproj):

# Instala/restaura todas as dependências do C#
dotnet restore

# Roda o projeto e inicia o servidor (o Rider faz isso ao clicar em Play)
dotnet run


Se o projeto for uma API, a documentação Swagger estará disponível em: https://localhost:[PORTA]/swagger/index.html

2. Frontend (React)

Abra outro Terminal e navegue até a subpasta do projeto React (ex: cd ClienteApp):

# Instala as dependências do Node
npm install

# Inicia o servidor de desenvolvimento do React
npm start


## Executando no Rider

Abra a solução (.sln) no Rider.

Defina o projeto [HelloWorldApplication].csproj como a configuração de execução principal (canto superior direito).

Clique no botão Play (Debug) para iniciar o backend.

🧪 Testes

Comandos para rodar testes:

# Rodar todos os testes unitários do projeto C#
dotnet test


🗺️ Estrutura da Solução

Lista de pastas principais para orientação:

```/src: Código fonte principal
- /src/[NomeDoProjeto]: Projeto C# principal (API).

- /src/[NomeDoProjeto]/Controllers: Endpoints da API.

- /src/[NomeDoProjeto]/Models: Classes de dados.

- /ClientApp: Pasta do projeto React.

- /[HelloWorldApplication].sln: Arquivo de Solução (para abrir no Rider).```
