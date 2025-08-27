# Análise de Mercado para QA Júnior

Infográfico interativo que resume **competências mais exigidas**, **tendências do mercado**, **faixa salarial de referência** e um **plano de desenvolvimento de 6 meses** para iniciar na carreira de QA/Analista de Testes Júnior.

> Versão publicada: https://fokeny.github.io/analise-de-mercado-qa/

---

## O que o projeto mostra

1. **Competências (Skills)**
   - **Hard skills** (gráfico de barras): automação de testes (Selenium/Cypress), testes de API (Postman/Swagger), gestão de bugs (Jira/TestRail), SQL, Git/CI-CD etc.
   - **Soft skills** (gráfico de rosca): proatividade, organização, comunicação, trabalho em equipe e atenção aos detalhes.
   - Os percentuais representam a **frequência de citação** dessas habilidades em **15 vagas** analisadas.

2. **Faixa Salarial de Referência**
   - Indicativo para QA/Analista de Testes **Júnior no Brasil**.
   - Valores **variáveis** por região, empresa e benefícios (referência: dados públicos como Glassdoor).

3. **Tendências do Mercado**
   - Ênfase em **automação** e **testes de API** mesmo em vagas júnior.
   - Uso de **Jira/TestRail** para rastreabilidade.
   - Diferenciais: **SQL**, **Git**, **CI/CD**; crescimento de **Playwright** e colaboração com **BDD (Cucumber)**.

4. **Plano de Desenvolvimento (6 meses)**
   - Roteiro mensal com **projetos práticos** (exploração, API com Postman, automação Web com Cypress, SQL e projeto final integrando UI→API→BD) para compor portfólio.

5. **Detalhamento das Vagas**
   - Cartões com as principais skills solicitadas por **cada vaga** da amostra (Desbravador, FITec, Deliver IT, etc.).

6. **Fontes e Referências**
   - Links para as **vagas consultadas** e referência salarial (Glassdoor).

---

## Como rodar localmente

Este projeto é **estático** (HTML + Tailwind via CDN + Chart.js via CDN).

> **Importante**: é necessário estar **conectado à internet** para carregar as bibliotecas das CDNs.

### Opção 1 — Abrir direto no navegador
1. Baixe/clon​e o repositório.
2. Dê **duplo clique** no arquivo `index.html`.
3. Pronto!

### Opção 2 — Usar um servidor local
- **VS Code + Live Server**: clique com o botão direito em `index.html` → *Open with Live Server*.
- **Python (3.x)**:
  ```bash
  # na pasta do projeto
  python -m http.server 5500
  # depois acesse: http://localhost:5500/index.html
  ```
- **Node (http-server)**:
  ```bash
  npx http-server . -p 5500
  # acesse: http://localhost:5500
  ```
---

## Créditos
- **Tecnologias**: HTML5, TailwindCSS (CDN), Chart.js (CDN), Google Fonts (Inter).
- **Dados**: coletados de 15 vagas júnior + referência salarial pública (Glassdoor).
