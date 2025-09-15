# dio-step-functions
Desafio - Workflows Automatizados com AWS Step Functions

Este repositório documenta o laboratório de **workflows automatizados com AWS Step Functions**, conforme proposto pela **Digital Innovation One (DIO)**.  
O objetivo é consolidar o conhecimento adquirido nas aulas, demonstrando como criar e gerenciar fluxos de trabalho serverless e documentar o processo técnico.

## Objetivos do Desafio
- Aplicar os conceitos aprendidos em aula sobre Step Functions.
- Criar workflows automatizados usando State Machines.
- Documentar o passo a passo de forma clara e estruturada.
- Utilizar o GitHub como ferramenta para compartilhar documentação técnica.

## Passo a Passo

### 1. Criação da State Machine
- Nome: `dio-stepfunctions-lab`
- Tipo: **Standard**
- Definição do Workflow em JSON:
```json
{
  "Comment": "Exemplo simples de Step Function",
  "StartAt": "TarefaInicial",
  "States": {
    "TarefaInicial": {
      "Type": "Pass",
      "Result": "Hello DIO!",
      "End": true
    }
  }
}



