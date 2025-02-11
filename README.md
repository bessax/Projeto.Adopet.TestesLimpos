# Projeto C# com API, Testes e Console Client (ADOPET)

Este repositório contém um projeto C# estruturado com uma API Minimal utilizando ASP.NET Core 8, um projeto de testes unitários com xUnit e Clean Tests, e um projeto console que consome a API utilizando `HttpClientFactory`.

## Estrutura do Projeto

- **Api**: Projeto de API desenvolvido com Minimal API e ASP.NET Core 8.
- **Tests**: Projeto de testes unitários utilizando xUnit e Clean Tests.
- **Console**: Aplicativo console que consome a API utilizando `HttpClientFactory`.

## Tecnologias Utilizadas

- .NET 8
- ASP.NET Core Minimal API
- xUnit
- Moq
- HttpClientFactory
- Swagger

## Como Executar o Projeto

### Clonar o Repositório
```bash
git clone [https://github.com/seu-usuario/projeto-csharp.git](https://github.com/bessax/Projeto.Adopet.TestesLimpos.git)
cd projeto-csharp
```

### Executar a API
```bash
cd ApiProject
dotnet run
```
A API estará disponível em `http://localhost:XXXXX`.

### Executar os Testes
```bash
cd Tests
dotnet test
```

### Executar o Cliente Console
```bash
cd Console
dotnet run
```
O aplicativo console realizará requisições à API e exibira as respostas no terminal.

## Testes Unitários

O projeto de testes segue o conceito de **Testes Limpos**, garantindo:
- **Independência** entre os testes.
- **Isolamento** dos componentes testados.
- **Uso de mocks e stubs** para simular dependências.

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

