# ADR 001: Definição da Arquitetura e Stack Tecnológica do Connexa

## Status
Aceito

## Contexto
O projeto **Connexa** necessita de uma arquitetura inicial escalável, de rápida navegação e fácil integração entre a API do back-end e a interface do front-end.

## Decisão
Adotamos a seguinte arquitetura e stack tecnológica:
- **Back-end:** C# com .NET (ASP.NET Core Web API).
- **Front-end:** React com TypeScript e Vite.
- **Gerenciamento do Projeto:** Azure DevOps (Organização: **GpTreze**, Projeto: **Connexa**).
- **Controle de Versão:** GitHub (Repositório público).

## Consequências
- **Positivas:** Alta performance de compilação, forte tipagem no back-end e front-end, e rastreabilidade com as Tasks do Azure Boards (ex: #43).
- **Negativas:** Necessidade de rodar dois processos locais independentes (API .NET e servidor dev do Vite) durante o desenvolvimento.