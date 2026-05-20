# Projeto de Gestão de Estoque e Automação de Vendas no WhatsApp

## 1. Descrição do Projeto

Este projeto tem como objetivo desenvolver uma solução para melhorar o controle de estoque, entrada e saída de produtos, além de automatizar o atendimento e as vendas realizadas pelo WhatsApp Business por meio de um chatbot.

A proposta surge da necessidade de tornar os processos mais organizados, rápidos e eficientes, reduzindo erros manuais e melhorando o atendimento ao cliente.

---

## 2. Objetivo Geral

Criar um sistema para controle de estoque e caixa integrado a uma automação de atendimento via WhatsApp Business, permitindo mais organização na gestão do negócio e mais agilidade nas vendas.

---

## 3. Objetivos Específicos

- Permitir o cadastro de produtos no sistema.
- Controlar entrada e saída de mercadorias.
- Exibir a quantidade atual de estoque.
- Registrar movimentações do caixa.
- Gerar relatórios básicos de estoque e financeiro.
- Automatizar o atendimento inicial no WhatsApp Business.
- Criar um chatbot para responder dúvidas frequentes.
- Direcionar o cliente para atendimento humano quando necessário.

---

## 4. Justificativa

Muitos pequenos negócios ainda realizam o controle de estoque e atendimento ao cliente de forma manual, o que pode causar erros, atrasos e dificuldades na organização. Com esse projeto, será possível centralizar informações importantes em um sistema simples e prático, além de automatizar parte do atendimento comercial via WhatsApp.

---

## 5. Escopo do Projeto

O projeto será dividido em duas frentes principais:

### 5.1 Sistema Interno
Responsável pelo controle de estoque e caixa.

### 5.2 WhatsApp Business com Chatbot
Responsável pela automação de atendimento e vendas.

---

## 6. Funcionalidades do Sistema

### Sistema de Estoque e Caixa
- Cadastro de produtos
- Edição e exclusão de produtos
- Entrada de estoque
- Saída de estoque
- Visualização do estoque atual
- Controle de caixa
- Exibição de saldo do caixa
- Relatórios de movimentação

### WhatsApp Business com Chatbot
- Configuração do canal de atendimento
- Respostas automáticas
- Menu de opções
- Informações sobre produtos
- Encaminhamento para atendimento humano
- Registro básico de interações

---

## 7. Tecnologias Utilizadas

> Esta parte pode ser ajustada conforme o que vocês realmente forem usar.

- Front-end: HTML, CSS e JavaScript
- Back-end: Python / Node.js / PHP
- Banco de dados: MySQL / SQLite / PostgreSQL
- Automação do WhatsApp: API de integração com WhatsApp Business
- Ferramentas de apoio: Git, GitHub, VS Code

---

## 8. Requisitos Funcionais

- RF01: O sistema deve permitir cadastrar produtos.
- RF02: O sistema deve permitir editar e excluir produtos.
- RF03: O sistema deve registrar entradas de estoque.
- RF04: O sistema deve registrar saídas de estoque.
- RF05: O sistema deve exibir a quantidade atual de produtos.
- RF06: O sistema deve registrar movimentações do caixa.
- RF07: O sistema deve exibir o saldo atual do caixa.
- RF08: O sistema deve gerar relatórios de estoque.
- RF09: O sistema deve gerar relatórios financeiros.
- RF10: O sistema deve integrar o atendimento ao WhatsApp Business.
- RF11: O chatbot deve responder mensagens automaticamente.
- RF12: O chatbot deve apresentar opções ao cliente.
- RF13: O chatbot deve encaminhar para atendimento humano quando necessário.

---

## 9. Requisitos Não Funcionais

- RNF01: A interface deve ser simples e intuitiva.
- RNF02: O sistema deve responder rapidamente às ações do usuário.
- RNF03: Os dados devem ser armazenados com segurança.
- RNF04: O sistema deve ser responsivo.
- RNF05: O chatbot deve fornecer respostas claras e objetivas.
- RNF06: O sistema deve permitir futuras melhorias.
- RNF07: O sistema deve funcionar de forma estável durante o uso.

---

## 10. Backlog do Produto

| ID | Item | Checklist | Prioridade | Sprint | Status |
|---|---|---|---|---|---|
| 01 | Sistema de Controle de Estoque | Cadastro de produtos <br> Entrada de estoque <br> Saída de estoque <br> Visualização do estoque | Alta | Sprint 1 | Não iniciado |
| 02 | Sistema de Controle de Caixa | Registro de entradas <br> Registro de saídas <br> Exibição de saldo | Alta | Sprint 1 | Não iniciado |
| 03 | Relatórios do Sistema | Relatório de estoque <br> Relatório financeiro | Média | Sprint 2 | Não iniciado |
| 04 | Integração com WhatsApp Business | Configuração do canal <br> Integração do atendimento | Alta | Sprint 2 | Não iniciado |
| 05 | Desenvolvimento do Chatbot | Respostas automáticas <br> Menu de opções <br> Encaminhamento humano | Alta | Sprint 3 | Não iniciado |
| 06 | Testes e Finalização | Testes do sistema <br> Correção de erros <br> Ajustes finais | Alta | Sprint 3 | Não iniciado |

---

## 11. User Stories

### 11.1 Sistema de Estoque

| ID | User Story | Critério de Aceite |
|---|---|---|
| US01 | Como funcionário, quero cadastrar produtos no sistema, para manter o controle do estoque. | O produto deve ser salvo com nome, quantidade e preço. |
| US02 | Como funcionário, quero editar produtos cadastrados, para corrigir informações quando necessário. | O sistema deve permitir alterar os dados do produto. |
| US03 | Como funcionário, quero excluir produtos, para remover itens que não são mais vendidos. | O produto deve ser removido da lista. |
| US04 | Como funcionário, quero registrar entrada de produtos, para atualizar o estoque corretamente. | A quantidade total deve ser aumentada automaticamente. |
| US05 | Como funcionário, quero registrar saída de produtos, para controlar o que foi vendido ou retirado. | A quantidade total deve ser reduzida automaticamente. |
| US06 | Como gerente, quero visualizar o estoque atual, para acompanhar os produtos disponíveis. | O sistema deve mostrar a quantidade atual de cada item. |

### 11.2 Sistema de Caixa

| ID | User Story | Critério de Aceite |
|---|---|---|
| US07 | Como gerente, quero registrar entradas no caixa, para acompanhar os valores recebidos. | O sistema deve salvar a movimentação financeira. |
| US08 | Como gerente, quero registrar saídas do caixa, para controlar despesas e retiradas. | O sistema deve atualizar o saldo corretamente. |
| US09 | Como gerente, quero visualizar o saldo do caixa, para saber quanto dinheiro está disponível. | O saldo deve ser exibido de forma atualizada. |
| US10 | Como gerente, quero gerar relatórios financeiros, para analisar entradas e saídas. | O sistema deve exibir os registros de forma organizada. |

### 11.3 WhatsApp Business e Chatbot

| ID | User Story | Critério de Aceite |
|---|---|---|
| US11 | Como cliente, quero ser atendido pelo WhatsApp Business, para ter mais agilidade no contato. | O atendimento deve iniciar pelo canal oficial da empresa. |
| US12 | Como cliente, quero receber respostas automáticas, para não precisar esperar atendimento manual. | O chatbot deve responder mensagens iniciais. |
| US13 | Como cliente, quero ver um menu de opções, para escolher rapidamente o que desejo. | O chatbot deve apresentar opções como produtos, preços e suporte. |
| US14 | Como cliente, quero falar com um atendente humano quando necessário, para resolver casos mais específicos. | O sistema deve encaminhar a conversa para um atendente. |
| US15 | Como empresa, quero registrar interações do chatbot, para acompanhar os atendimentos realizados. | O sistema deve armazenar o histórico básico da conversa. |

---

## 12. Fluxo Resumido do Sistema

1. O produto é cadastrado no sistema.
2. O estoque é atualizado com entradas e saídas.
3. O caixa registra movimentações financeiras.
4. O cliente entra em contato pelo WhatsApp Business.
5. O chatbot responde automaticamente.
6. Se necessário, o cliente é encaminhado para um atendente humano.
