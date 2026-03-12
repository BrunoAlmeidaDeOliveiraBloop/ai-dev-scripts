# 🚀 AI Dev Scripts

> 🇧🇷 Este repositório centraliza prompts e scripts de linguagem natural estruturados para transformar o GitHub Copilot em especialistas específicos, otimizando o fluxo de desenvolvimento com foco em qualidade e segurança.
>
> 🇺🇸 This repository centralizes structured prompts and natural language scripts to transform GitHub Copilot into specific experts, optimizing the development workflow with a focus on quality and security.

---

## 🧩 Modos do Copiloto / Copilot Modes

Inspirado na metodologia da **DIO**, este projeto organiza os prompts de acordo com o papel (role) desejado para a IA. Todos os scripts utilizam uma estrutura de resposta em níveis para garantir profundidade técnica.

### ❓ Ask (Technical Mentor)
* **PT:** Focado em mentoria técnica e teoria de Node.js. Explica conceitos complexos usando benchmarking de mercado.
* **EN:** Focused on technical mentoring and Node.js theory. Explains complex concepts using industry benchmarking.
* **Prompts:** [`PT-BR`](prompts/pt/prompt-ask.md) | [`EN`](prompts/en/prompt-ask.md)

### ✏️ Edit (Refactoring Expert)
* **PT:** Refatoração com foco em Clean Code e SOLID. Possui travas de segurança para não quebrar a lógica de negócio.
* **EN:** Refactoring with a focus on Clean Code and SOLID. Features safety locks to avoid breaking business logic.
* **Prompts:** [`PT-BR`](prompts/pt/prompt-edit.md) | [`EN`](prompts/en/prompt-edit.md)

### 🧭 Plan (Software Architect)
* **PT:** Planejamento de arquitetura, escolha de Design Patterns e eficiência algorítmica antes da codificação.
* **EN:** Architecture planning, choice of Design Patterns, and algorithmic efficiency before coding.
* **Prompts:** [`PT-BR`](prompts/pt/prompt-plan.md) | [`EN`](prompts/en/prompt-plan.md)

### 🤖 Agent (Production Specialist)
* **PT:** Executor de tarefas complexas e "Production-Ready". Focado em automação, documentação colaborativa e resiliência.
* **EN:** Executor of complex, "Production-Ready" tasks. Focused on automation, collaborative documentation, and resilience.
* **Prompts:** [`PT-BR`](prompts/pt/prompt-agent.md) | [`EN`](prompts/en/prompt-agent.md)

### 📚 Study (Career Coach)
* **PT:** Mentor socrático para níveis Junior/Trainee. Promove autonomia através de desafios e revelação progressiva.
* **EN:** Socratic mentor for Junior/Trainee levels. Promotes autonomy through challenges and progressive disclosure.
* **Prompts:** [`PT-BR`](prompts/pt/prompt-study.md) | [`EN`](prompts/en/prompt-study.md)

---

## 🛡️ Diferenciais / Key Features

* **Safety First:** Os prompts de `Edit` e `Agent` exigem validação de contexto antes de alterações drásticas.
* **Production-Ready:** Foco em códigos que incluem tratamento de erros, logs e segurança.
* **Socratic Learning:** O modo `Study` não entrega a resposta de bandeja, incentivando o pensamento crítico.

## 🛠️ Tecnologias Base / Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **AI Tool:** GitHub Copilot / ChatGPT / Claude

---

## 📖 Como usar / How to use

### 🇧🇷 Português
1. **Escolha um papel:** Navegue na pasta `prompts/pt/` e escolha o script que melhor se adapta à sua necessidade atual.
2. **Copie e Cole:** Copie o conteúdo do arquivo `.md` e cole no chat do Copilot (ou utilize `@workspace /explain #file:nome-do-arquivo.md` se o arquivo já estiver no seu projeto).
3. **Interaja:** Forneça o contexto do seu código ou tarefa. A IA seguirá a metodologia estruturada de níveis definida no prompt.

### 🇺🇸 English
1. **Choose a Role:** Browse the `prompts/en/` folder and select the script that best fits your current task.
2. **Copy and Paste:** Copy the `.md` file content and paste it into the Copilot chat (or use `@workspace /explain #file:filename.md` if the file is already in your project).
3. **Interact:** Provide your code context or task. The AI will follow the structured levels of response defined in the prompt.
---

## 🎓 Créditos / Credits

Desenvolvido por **Bruno Almeida de Oliveira**. Inspirado pelo curso de IA da [DIO](https://www.dio.me/).