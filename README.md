# Cypress - Testes E2E

Projeto de automacao de testes end-to-end com Cypress, criado para demonstrar habilidades praticas em:

- planejamento de cenarios de teste
- validacao de fluxos criticos de e-commerce
- organizacao de suites por funcionalidade
- escrita de testes legiveis e reutilizaveis

## Objetivo

Este repositorio foi estruturado como portfolio tecnico para mostrar minha evolucao em QA e automacao de testes web.

## Tecnologias

- Cypress
- JavaScript
- Node.js

## Estrutura do Projeto

- cypress/e2e/login.cy.js: cenarios de autenticacao
- cypress/e2e/about.cy.js: validacoes de pagina institucional
- cypress/e2e/carrinho.cy.js: fluxo de carrinho de compras
- cypress/e2e/PaginaCompras.cy.js: fluxo de compras
- cypress/e2e/spec.cy.js: testes gerais
- cypress/support/: comandos e configuracoes de suporte
- cypress/fixtures/: dados de apoio

## Como Executar

1. Instale as dependencias:
   npm install

2. Rode os testes no modo interativo:
   npx cypress open

3. Rode os testes no modo headless:
   npx cypress run

## Diferenciais deste Portfolio

- Casos de teste focados em jornada real de usuario
- Estrutura simples para manutencao e escalabilidade
- Base pronta para evoluir com CI/CD (GitHub Actions)

## Proximos Passos

- Adicionar relatorios (Mochawesome ou Allure)
- Integrar execucao automatica no GitHub Actions
- Separar massa de teste por ambiente
- Aplicar padrao Page Objects

## Autor

Desenvolvido por Gabroel Narcelio para fins de estudo e portfolio profissional em testes automatizados.
