# _atividade-senai
Este repositório contém um projeto desenvolvido em C# como parte de uma atividade do curso de codificação para Back-End. O projeto é um sistema simples de cadastro de clientes, onde é possível cadastrar pessoas físicas e jurídicas e calcular os impostos a serem pagos com base no valor da compra.

# Sistema de Cadastro de Clientes

Este é um projeto simples desenvolvido em C# para demonstrar um sistema de cadastro de clientes, onde é possível cadastrar tanto pessoas físicas quanto pessoas jurídicas e calcular os impostos a serem pagos com base no valor da compra.

## Funcionalidades

- Cadastro de clientes:
  - Nome
  - Endereço
- Cadastro de Pessoa Física:
  - CPF
  - RG
- Cadastro de Pessoa Jurídica:
  - CNPJ
  - Inscrição Estadual (IE)
- Cálculo de impostos:
  - Pessoas Físicas: 10% sobre o valor da compra
  - Pessoas Jurídicas: 20% sobre o valor da compra

## Como usar

1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter o .NET Core SDK instalado em seu sistema.
3. Abra um terminal e navegue até o diretório do projeto.
4. Compile o projeto executando o comando `dotnet build`.
5. Execute o projeto com o comando `dotnet run`.
6. Siga as instruções no console para cadastrar clientes e calcular os impostos.

## Estrutura do Projeto

- `Program.cs`: Contém a classe principal com o método `Main` onde o programa é iniciado.
- `Clientes.cs`: Define a classe base `Clientes` com propriedades comuns a todas as entidades de cliente e um método para calcular impostos.
- `Pessoa_Fisica.cs`: Define a classe `Pessoa_Fisica` que herda de `Clientes` e adiciona propriedades específicas de pessoas físicas.
- `Pessoa_Juridica.cs`: Define a classe `Pessoa_Juridica` que herda de `Clientes` e adiciona propriedades específicas de pessoas jurídicas.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request com melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
