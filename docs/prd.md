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
    - _Critérios de Aceitação:_ O sistema não deve permitir salvar se o nome estiver em branco; o telefone deve aceitar apenas números e formatar automaticamente; após salvar, o formulário deve limpar para o próximo atendimento.
* **Como Secretária**, eu quero que o **endereço seja preenchido automaticamente ao digitar o CEP**, para agilizar o atendimento inicial ao cliente.
    - _Critérios de Aceitação:_ O sistema deve realizar uma requisição assíncrona para a API pública ViaCEP assim que o campo de CEP for preenchido com 8 dígitos.
###  Épico 2: Fluxo de Listagem e Gestão (Saída)

* **Como Advogado**, eu quero **visualizar uma lista de tarefas pendentes** em um dashboard, para que eu possa priorizar os atendimentos do dia.
    - _Critérios de Aceitação:_ A tela deve mostrar um resumo visual de quantos clientes estão aguardando; os clientes mais recentes devem aparecer no topo da lista.
* **Como Advogado**, eu quero **filtrar ou buscar tarefas por nome do cliente**, para localizar rapidamente um processo específico.
    - _Critérios de Aceitação:_ A busca deve filtrar a lista conforme o usuário digita; os botões de filtroetc devem mostrar apenas os clientes daquela categoria específica.
* **Como Usuário**, eu quero que o **layout seja adaptável para o meu celular**, para que eu possa consultar os prazos mesmo quando estiver fora do escritório.
    - _Critérios de Aceitação:_ O menu deve ser fácil de clicar com o polegar; as informações da tabela não devem ficar "cortadas" ou escondidas na tela do celular.

### 📊 Épico 3: Persistência e Controle

* **Como Administrador**, eu quero **excluir ou editar uma tarefa concluída** 
   - _Critérios de Aceitação:_ para manter a lista de trabalhos atualizada e limpa.
o clicar em editar, todos os dados do cliente devem voltar para o formulário.
* **Como Usuário**, eu quero que meus **rascunhos fiquem salvos localmente**, para não perder as informações caso a página seja atualizada acidentalmente.
   - _Critérios de Aceitação:_ Se a secretária fechar o navegador no meio de um cadastro longo, ao abrir novamente, o que ela já digitou deve estar lá nos campos.