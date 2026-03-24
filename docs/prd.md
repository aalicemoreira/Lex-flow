# 📄 Product Requirements Document (PRD) - LexFlow

## 1. Visão Geral e Objetivo

O **LexFlow - Sistema de Gestão de Leads e Tarefas Jurídicas** é uma aplicação voltada para a organização interna de um escritório de advocacia que recebe um alto volume de potenciais clientes (leads) através de tráfego pago.

**O grande diferencial (Regra de Negócio Principal):** Você não está apenas cumprindo tabela acadêmica. Você mapeou um fluxo de trabalho real: Tráfego Pago → Secretária (Triagem) → Advogado (Execução). Isso demonstra maturidade profissional e capacidade de análise de sistemas, algo que vale ouro no mercado de tecnologia.

## 2. Atores do Sistema

- **Secretária (Administrador):** Responsável pela triagem inicial, cadastro de leads e organização da agenda.
- **Advogado (Usuário Operacional):** Responsável pela execução das tarefas jurídicas e consulta de prazos.

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

### 👤 Épico 1: Fluxo de Cadastro (Entrada)

* **Como Secretária**, eu quero **cadastrar um novo lead** informando nome, telefone e CEP, para que os dados fiquem registrados no sistema e não se percam.
* **Como Secretária**, eu quero que o **endereço seja preenchido automaticamente ao digitar o CEP**, para agilizar o atendimento inicial ao cliente.
* **Como Secretária**, eu quero **validar os campos de e-mail e telefone** com máscaras e avisos, para garantir que o advogado consiga entrar em contato com o cliente depois.

###  Épico 2: Fluxo de Listagem e Gestão (Saída)

* **Como Advogado**, eu quero **visualizar uma lista de tarefas pendentes** em um dashboard, para que eu possa priorizar os atendimentos do dia.
* **Como Advogado**, eu quero **filtrar ou buscar tarefas por nome do cliente**, para localizar rapidamente um processo específico.
* **Como Usuário**, eu quero que o **layout seja adaptável para o meu celular**, para que eu possa consultar os prazos mesmo quando estiver fora do escritório.

### 📊 Épico 3: Persistência e Controle

* **Como Administrador**, eu quero **excluir ou editar uma tarefa concluída**, para manter a lista de trabalhos atualizada e limpa.
* **Como Usuário**, eu quero que meus **rascunhos fiquem salvos localmente**, para não perder as informações caso a página seja atualizada acidentalmente.