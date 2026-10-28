---
description: "Orientações para criar e editar README.md de tarefas em assignments, seguindo o template e os padrões educacionais do projeto."
applyTo: "assignments/**/README.md"
---

# Diretrizes de Estrutura para Markdowns de Tarefas

Todos os arquivos markdown de tarefas devem seguir estas diretrizes:

## Uso do Template

- Use a estrutura de [`templates/assignment-template.md`](../../../templates/assignment-template.md).
- Mantenha cada tarefa em `assignments/<nome-da-tarefa>/README.md`.
- Preserve a ordem, os títulos e as seções do template; substitua os textos entre colchetes pelo conteúdo da atividade.
- Não remova seções obrigatórias nem adicione seções extras, a menos que o usuário solicite.

## Conteúdo das seções

- `# 📘 Atividade: [Título da Atividade]`: escolha um título curto e descritivo.
- `## 🎯 Objetivo`: resuma em uma ou duas frases o que o aluno aprenderá ou construirá.
- `## 📝 Tarefas`: organize cada atividade em uma subseção `### 🛠️ [Título da Tarefa]`.
- `#### Descrição`: explique claramente o que o aluno deve fazer.
- `#### Requisitos`: comece com “O programa concluído deve:” e liste resultados específicos e verificáveis em tópicos.
- Inclua exemplos de entrada e saída em blocos de código quando ajudarem a esclarecer o resultado esperado.

## Padrões educacionais

- Escreva em português claro, com tom amigável e adequado ao nível da atividade.
- Defina objetivos de aprendizagem claros e requisitos que possam ser verificados.
- Mantenha estilo e nomes consistentes com as demais tarefas do projeto.