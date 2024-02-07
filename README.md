# Projeto de Agenda de Contatos

Este é um projeto de agenda de contatos desenvolvido em C# usando o framework ASP.NET Core MVC e o banco de dados SQL Server.

## Pré-requisitos

- Visual Studio (ou outra IDE de sua preferência)
- .NET Core SDK
- SQL Server

## Configuração do Banco de Dados

1. Certifique-se de ter o SQL Server instalado em sua máquina.
2. Execute o script `AgendaContatosDB.sql` para criar o banco de dados e as tabelas necessárias.

## Como Executar o Projeto

1. Abra o projeto no Visual Studio.
2. Configure a conexão com o banco de dados no arquivo `appsettings.json` conforme necessário.
3. Execute o projeto.

## Funcionalidades

- **Listagem de Contatos:** Visualize todos os contatos cadastrados.
- **Adição de Contatos:** Adicione novos contatos à agenda.
- **Edição de Contatos:** Edite as informações de contatos existentes.
- **Detalhes de Contatos:** Veja informações detalhadas de cada contato.
- **Remoção de Contatos:** Remova contatos da agenda.

## Estrutura do Projeto

- **ContatoController.cs:** Controlador responsável por gerenciar as operações relacionadas aos contatos.
- **AgendaContext.cs:** Classe de contexto do Entity Framework para interação com o banco de dados.
- **Contato.cs:** Modelo de dados para representar um contato na agenda.
- **Views/Contato/**: Diretório contendo as visualizações relacionadas aos contatos.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
