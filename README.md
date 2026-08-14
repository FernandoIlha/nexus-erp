# Nexus ERP

ERP para pequenas e médias empresas. Monólito modular com foco em operações reais: cadastros, estoque, vendas, compras e financeiro básico.

## Stack

- **Backend:** Java 17, Spring Boot, Maven
- **Banco:** PostgreSQL + Flyway
- **Frontend:** Angular
- **Segurança:** Spring Security + JWT
- **Infra:** Docker, AWS, GitHub Actions

## O que está incluído

- Autenticação e autorização (JWT, roles)
- Produtos, clientes e fornecedores
- Estoque com movimentações, saldo e auditoria
- Vendas e compras com integração financeira
- Contas a pagar/receber e dashboard básico

## Fluxos principais

**Venda:** cliente → itens → valida estoque → calcula total → confirma → baixa estoque → gera conta a receber

**Compra:** fornecedor → itens → calcula total → confirma → entrada estoque → gera conta a pagar

## Roadmap

| Fase | Objetivo |
|------|----------|
| 0 | Definição e backlog |
| 1 | Spring Boot + PostgreSQL + Flyway |
| 2 | API REST + Angular inicial |
| 3 | JWT + Login |
| 4 | Estoque e concorrência |
| 5 | Vendas ponta a ponta |
| 6 | Compras |
| 7 | Financeiro e dashboard |
| 8 | Frontend completo |
| 9 | Testes e observabilidade |
| 10 | Docker |
| 11 | Deploy AWS |
| 12 | CI/CD e release |

## Como executar

Em breve — `docker compose up` após a Fase 10.

## Licença

MIT — veja [LICENSE](LICENSE).
