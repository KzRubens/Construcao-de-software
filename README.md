🚀 Simulação de Desenvolvimento Ágil: Gerenciador de Tarefas em Console

Este projeto consiste em uma atividade prática de simulação ágil inspirada no Scrum Framework, onde a equipe atua como um time completo de desenvolvimento de software para construir um Gerenciador de Tarefas via Console.

A dinâmica e a fundamentação teórica deste projeto baseiam-se nas diretrizes dos documentos e materiais de apoio de nossa metodologia:

"2) Construção de Software Utilizando Metodologias Ágeis.docx"

"2) Modelos de Desenvolvimento.pptx"

🎯 Objetivo do Projeto

O objetivo principal é vivenciar a experiência real de um ciclo ágil, enfrentando os desafios de comunicação, priorização e adaptação a mudanças de requisitos enquanto construímos um aplicativo funcional em formato de console.

💻 O Programa (Gerenciador de Tarefas)

O sistema desenvolvido opera diretamente no terminal de comando e fornece as seguintes funções essenciais:

Adicionar Tarefa: Inserir um novo registro no sistema de monitoramento.

Marcar como Concluída: Atualizar o status de uma tarefa pendente.

Visualizar Todas as Tarefas: Listar de forma limpa e organizada os itens cadastrados.

Remover Tarefa: Excluir um item do gerenciador.

Encerrar o Programa: Sair da execução com segurança.

👥 Papéis do Time (Estrutura Scrum)

Para simular o ambiente de mercado, a equipe dividiu-se nos papéis fundamentais do Scrum, executando as seguintes atribuições diárias:

Papel

Responsabilidades Práticas

Product Owner (PO)

• Representa a voz do cliente e define as metas do produto.



• Cria, gerencia e prioriza o Product Backlog.



• Altera requisitos dinamicamente após as dailies para simular cenários reais.



• Não interfere em decisões técnicas ou de implementação.

Scrum Master (SM)

• Garante a correta execução dos ritos do Scrum.



• Facilita reuniões (Sprint Planning, Daily, Review e Retrospective).



• Remove impedimentos e bloqueios da equipe técnica.

Developers

• Planejam o escopo técnico (Sprint Backlog).



• Implementam o código-fonte do gerenciador no console.



• Decidem a arquitetura técnica, divisão interna de tarefas e design do sistema.

Tester / QA

• Garante a estabilidade e qualidade técnica da entrega.



• Planeja casos de teste baseado nas regras do PO.



• Valida e reporta bugs ou inconformidades no console.

🔄 Dinâmica das Sprints e Ritos Ágeis

O projeto foi dividido em ciclos incrementais chamados Sprints, respeitando os ritos tradicionais de desenvolvimento de software:

graph TD
    A[Product Backlog] --> B(Sprint Planning)
    B --> C{Sprint Cycle}
    C -->|Reunião Diária - 15min| D(Daily Standup)
    D -->|Novos Requisitos do PO| A
    C --> E(Sprint Review)
    E --> F(Sprint Retrospective)
    F --> G[Incremento Funcional do Console]


Sprint Planning: Reunião onde o PO apresenta os itens prioritários, a equipe define a Meta da Sprint e os Desenvolvedores criam o Sprint Backlog.

Daily Standup: Reuniões rápidas diárias de até 15 minutos para sincronizar o progresso e expor bloqueios.

Mudanças Dinâmicas: Após cada daily, o PO pode inserir "mudanças de mercado" que forçam o time a adaptar-se rapidamente a novos requisitos.

Sprint Review & Retrospective: Apresentação da ferramenta final ao PO e discussão sobre melhorias no processo de trabalho do time.

📋 Quadro de Fluxo de Trabalho (Kanban)

Utilizamos um quadro visual baseado no Kanban de engenharia de software para rastrear o status de cada funcionalidade:

Backlog: Ideias e novos requisitos sugeridos pelo PO.

To Do (A Fazer): Itens selecionados e planejados para a Sprint vigente.

In Progress (Em Desenvolvimento): Funcionalidades ativamente sendo programadas no console.

Review (Revisão): Código concluído aguardando aprovação de outro desenvolvedor (Pull Request).

Testing (Testes): Aplicação entregue para a fase de testes manuais e de estresse pelo QA.

Done (Concluído): Funcionalidade integrada com sucesso e 100% testada.

🛠️ Tecnologias e Execução

Linguagem Utilizada: [Python]

Interface: Interface de linha de comando (Console/Terminal).
