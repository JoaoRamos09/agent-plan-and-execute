# **Agent Plan-and-Execute**

## Descrição

Este projeto explora a arquitetura de agente "Plan-and-Execute" em um ambiente de notebooks interativos. No modelo "Plan-and-Execute", o agente é projetado para criar um plano detalhado dividido em etapas, que são seguidas de forma sequencial até que um objetivo específico seja alcançado. A entrada do objetivo é fornecida pelo usuário, e o agente se adapta dinamicamente à execução de cada etapa, verificando se o objetivo foi atingido após cada ação. Caso o objetivo seja alcançado antes de todas as etapas serem executadas, o agente encerra o processo e notifica o usuário.

Este tipo de arquitetura é ideal para agentes que precisam lidar com tarefas complexas de forma estruturada, criando um fluxo lógico de execução para atingir metas predefinidas. Ao contrário de abordagens que apenas reagem ao ambiente ou entrada do usuário, o "Plan-and-Execute" capacita o agente a planejar antecipadamente e agir de maneira eficiente, dividindo objetivos em ações menores e mensuráveis.

## Base de Implementação

Este projeto foi inspirado e desenvolvido com base no exemplo `plan_and_execute` fornecido pela documentação oficial do LangGraph. A implementação demonstra uma abordagem prática para aplicar a arquitetura, destacando a eficiência e o planejamento lógico necessário para alcançar objetivos complexos.

## Funcionalidades Principais

- **Planejamento de Ações**: O agente cria um plano detalhado para atingir o objetivo do usuário.
- **Execução Iterativa**: Cada etapa do plano é executada sequencialmente com verificações após cada ação.
- **Adaptação e Verificação**: O agente adapta o plano conforme o progresso e encerra a execução assim que o objetivo é alcançado.
- **Entrada do Usuário**: O objetivo a ser alcançado é fornecido como entrada, permitindo flexibilidade na definição das metas do agente.

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/agent-plan-and-execute.git

2. Navague até o diretório do projeto:
   ```bash
   cd agent-plan-and-execute

3. Abra o notebook em seu ambiente preferido (Jupyter, VS Code, etc.) e forneça o objetivo que deseja que o agente atinja.

## Contribuindo

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorar o projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.
