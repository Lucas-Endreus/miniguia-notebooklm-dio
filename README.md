# 📚 Caderno Temático com NotebookLM
## Engenharia de Prompts aplicada à IA Generativa

> Projeto desenvolvido como parte do desafio da DIO em parceria com a Fundação Bradesco.

---

# 🎯 Objetivo

Este projeto tem como objetivo demonstrar a utilização do **NotebookLM** como ferramenta de aprendizagem ativa, utilizando Inteligência Artificial Generativa para organizar conhecimentos, sintetizar documentos e construir um material de estudos reutilizável.

Além de atender aos requisitos do desafio, este repositório registra todo o processo de aprendizado, incluindo pesquisa, curadoria de fontes, engenharia de prompts, experimentos realizados e consolidação do conhecimento adquirido.

---

# 🚀 Objetivos de Aprendizagem

Ao final deste projeto pretendo ser capaz de:

- Compreender os fundamentos da Engenharia de Prompts;
- Aprender boas práticas para interação com modelos de IA Generativa;
- Utilizar o NotebookLM como ambiente de pesquisa e organização do conhecimento;
- Desenvolver prompts mais eficientes;
- Documentar experimentos realizados durante o aprendizado;
- Criar um material reutilizável para futuras consultas.

---

# 🧠 Tema Escolhido

## Engenharia de Prompts para IA Generativa

A Engenharia de Prompts é uma das competências mais importantes para profissionais que trabalham com Inteligência Artificial.

Ela consiste na criação de instruções claras, estruturadas e contextualizadas para obter respostas mais precisas, úteis e confiáveis dos Grandes Modelos de Linguagem (LLMs).

---

# 📖 Curadoria de Fontes

As seguintes fontes foram utilizadas para construção deste Caderno Temático:

## 1. OpenAI

https://platform.openai.com/docs

Documentação oficial contendo conceitos sobre modelos de linguagem, boas práticas e engenharia de prompts.

---

## 2. Google Prompt Engineering Guide

https://developers.google.com/machine-learning/resources/prompt-eng

Guia com técnicas de construção de prompts eficientes.

---

## 3. Microsoft Learn

https://learn.microsoft.com/training/

Conteúdo sobre IA Generativa, Microsoft Copilot e Prompt Engineering.

---

## 4. Documentação NotebookLM

https://notebooklm.google/

Ferramenta utilizada para organização dos estudos.

---

## 5. Conteúdos da DIO

https://www.dio.me/

Materiais utilizados durante o Bootcamp.

---

# 🤖 Engenharia de Prompts

Durante os estudos diversos prompts foram testados.

Cada experimento ajudou a entender como pequenas alterações na escrita podem modificar completamente a qualidade da resposta.

---

## Prompt 1

**Objetivo**

Obter uma definição simples.

```text
Explique Engenharia de Prompts para uma pessoa que nunca estudou Inteligência Artificial.
```

### Resultado

Resposta clara e objetiva.

### Aprendizado

Prompts simples funcionam bem para introdução ao assunto.

---

## Prompt 2

```text
Explique Engenharia de Prompts utilizando exemplos do dia a dia.
```

### Resultado

A IA respondeu utilizando analogias.

### Aprendizado

Adicionar contexto melhora significativamente a compreensão.

---

## Prompt 3

```text
Compare Zero-shot, One-shot e Few-shot Prompting em formato de tabela.
```

### Resultado

Comparação organizada e fácil de entender.

### Aprendizado

Solicitar formatos específicos melhora a organização da resposta.

---

## Prompt 4

```text
Monte um plano de estudos de 7 dias utilizando apenas os documentos enviados ao NotebookLM.
```

### Resultado

Plano personalizado.

### Aprendizado

O NotebookLM consegue utilizar apenas as fontes fornecidas, reduzindo respostas fora do contexto.

---

## Prompt 5

```text
Crie um quiz com 20 perguntas para revisar Engenharia de Prompts.
```

### Resultado

Foi possível revisar o conteúdo de forma prática.

---

# ⚠ Dificuldades Encontradas (Troubleshooting)

| Problema | Solução |
|----------|----------|
| Respostas muito genéricas | Adicionar contexto ao prompt |
| Poucos exemplos | Solicitar exemplos explicitamente |
| Respostas extensas | Definir limite de palavras |
| Conteúdo superficial | Solicitar aprofundamento |
| Informações repetidas | Reformular o prompt |

---

# 📒 Miniguia de Estudos

## O que é Engenharia de Prompts?

É a prática de elaborar instruções eficientes para que modelos de Inteligência Artificial produzam respostas mais precisas, relevantes e contextualizadas.

---

## Principais Técnicas

### Zero-shot

O modelo responde sem exemplos.

---

### One-shot

Um exemplo é fornecido antes da solicitação.

---

### Few-shot

São apresentados vários exemplos para orientar a resposta.

---

### Chain of Thought

Solicita que a IA explique seu raciocínio passo a passo antes da resposta final.

---

### Role Prompting

A IA assume um papel específico.

Exemplo:

> Você é um especialista em Segurança da Informação.

---

### Instruction Prompting

O usuário fornece instruções detalhadas sobre o formato esperado da resposta.

---

### Context Prompting

Fornece contexto adicional para melhorar a precisão.

---

# 📚 Glossário

## IA Generativa

Tecnologia capaz de criar textos, imagens, códigos e outros conteúdos.

---

## LLM

Large Language Model.

Modelo de linguagem treinado com bilhões de palavras.

---

## Prompt

Texto enviado para a IA contendo instruções.

---

## Token

Menor unidade de processamento utilizada pelos modelos de linguagem.

---

## Hallucination

Situação em que a IA produz informações incorretas apresentadas como verdadeiras.

---

## Contexto

Informações adicionais fornecidas ao modelo para melhorar a resposta.

---

# 💡 Prompts Reutilizáveis

## Resumo

```text
Resuma este documento em cinco tópicos principais.
```

---

## Explicação

```text
Explique este conteúdo como se eu tivesse 12 anos.
```

---

## Comparação

```text
Compare estes conceitos em formato de tabela.
```

---

## Revisão

```text
Crie um resumo para revisão de prova.
```

---

## Flashcards

```text
Crie flashcards contendo pergunta e resposta.
```

---

## Quiz

```text
Crie um simulado com 20 questões de múltipla escolha.
```

---

## Plano de Estudos

```text
Monte um cronograma de estudos de sete dias baseado neste conteúdo.
```

---

# 🎓 Aprendizados

Durante este projeto foi possível compreender como o NotebookLM pode ser utilizado como uma ferramenta de apoio ao aprendizado, permitindo organizar documentos, sintetizar conteúdos e produzir materiais de estudo personalizados.

Também ficou evidente que a Engenharia de Prompts é uma habilidade essencial para extrair respostas mais completas, precisas e úteis dos modelos de Inteligência Artificial.

Pequenas alterações na estrutura dos prompts produziram resultados significativamente melhores, demonstrando a importância da experimentação contínua.

---

# 🏆 Conclusão

Este projeto permitiu aplicar conceitos de Inteligência Artificial Generativa, Engenharia de Prompts e Curadoria de Conteúdo utilizando o NotebookLM como ambiente de aprendizagem.

Além de atender aos requisitos do desafio da DIO, este repositório serve como material de consulta para estudos futuros e demonstra a importância da documentação técnica durante o processo de aprendizagem.

---

## 👨‍💻 Autor

**Lucas Endreus**

Bootcamp DIO + Fundação Bradesco

2026
