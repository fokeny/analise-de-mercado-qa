# Análise de Mercado para QA Júnior — Infográfico Interativo

## 🚀 Acesso Rápido
Visualize o infográfico interativo diretamente no navegador:  
**https://fokeny.github.io/analise-de-mercado-qa/**

---

## 📖 Sobre o Projeto
Este projeto é uma **Single-Page Application (SPA)** que apresenta um **infográfico interativo** sobre o mercado de trabalho para profissionais de **Qualidade de Software (QA) Júnior** no Brasil.

A análise foi compilada a partir de dados extraídos de **15 vagas reais**, oferecendo um panorama claro e visual sobre:
- **Hard Skills** mais requisitadas (automação, APIs, gestão de bugs, SQL, Git/CI-CD, etc.).
- **Soft Skills** mais valorizadas (proatividade, organização, comunicação, trabalho em equipe, atenção aos detalhes).
- **Faixa salarial de referência** para a posição júnior (valores podem variar por região/empresa/benefícios).
- **Tendências e tecnologias emergentes** na área (Playwright, BDD/Cucumber, CI/CD, etc.).
- **Plano de desenvolvimento de 6 meses** com projetos práticos para compor portfólio.

**Objetivo**: servir como um **guia visual e prático** para estudantes e profissionais que buscam se posicionar de forma competitiva no mercado de QA.

---

## ✨ Funcionalidades
- **Gráficos interativos** com Chart.js (barras horizontais e anel).
- **Design responsivo** com Tailwind CSS (layout adaptado para desktop e mobile).
- **Navegação em página única** (SPA), com seções fluídas e conteúdo consolidado.
- **Detalhamento das 15 vagas** analisadas, com as principais skills por vaga.
- **Fontes e Referências** com links diretos para verificação.

---

## 🛠️ Tecnologias Utilizadas
- **HTML5** – estrutura semântica do conteúdo.
- **Tailwind CSS (CDN)** – design utility-first, rápido e responsivo.
- **JavaScript (ES6+)** – lógica e manipulação do DOM.
- **Chart.js (CDN)** – renderização dos gráficos.
- **Google Fonts (Inter)** – tipografia.

> Como as bibliotecas são carregadas via **CDN**, é recomendável estar **conectado à internet** ao abrir a página.

---

## 📊 Fonte dos Dados
A análise é baseada em **15 anúncios de vagas** para “Analista de QA Júnior” (ou cargos similares) em plataformas de emprego no Brasil. A **referência salarial** utiliza médias públicas do **Glassdoor**.  
Os links das vagas e referências estão listados na seção **“Fontes e Referências”** da própria página.

---

## ▶️ Como rodar localmente
Projeto **estático** (somente HTML/CSS/JS). Não requer build.

### Opção 1 — Abrir diretamente no navegador
1. Baixe ou clone o repositório.
2. Abra o arquivo **`index.html`** com duplo clique.

### Opção 2 — Servir localmente
- **VS Code + Live Server**
  1. Instale a extensão *Live Server*.
  2. Clique com o botão direito em `index.html` → **Open with Live Server**.
- **Python 3.x**
  ```bash
  # na pasta do projeto
  python -m http.server 5500
  # acesse: http://localhost:5500/index.html
  ```
- **Node (http-server)**
  ```bash
  npx http-server . -p 5500
  # acesse: http://localhost:5500
  ```

> **Obs.**: por usar CDNs, mantenha a conexão com a internet para carregar Tailwind/Chart.js/Fonts.

---

## 🌐 Como publicar (GitHub Pages)
1. Faça **push** do projeto para um repositório público no GitHub.
2. Vá em **Settings → Pages**.
3. Em **Source**, selecione a *branch* (ex.: `main`) e a pasta **`/root`**.
4. Salve. A URL ficará no formato: `https://<seu-usuario>.github.io/<nome-do-repo>/`  
   (Ex.: **https://fokeny.github.io/analise-de-mercado-qa/**).

---

## 📄 Observações
- Valores salariais e exigências podem variar conforme empresa, região e momento do mercado.
- Recomenda-se **atualizar os dados periodicamente** (mensal/trimestral) e registrar a data da coleta no README.

