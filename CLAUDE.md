# Nodeflow · Dashboard de Portfolio · Contexto para Claude Code

## Quem sou eu

Fernando Costa (Nando) — founder da Nodeflow, empresa de criação de apps e automação de agentes com IA.
Estou em part-time na Norauto (gestão de categoria internacional) e a construir a Nodeflow em simultâneo.
Background: gestão + IA aplicada. Stack habitual: React 18 + TypeScript + Vite + Tailwind + Gemini API.

---

## O que quero construir

Um **dashboard de portfolio** da Nodeflow que:

1. Apresenta as apps que já desenvolvi de forma clara e profissional
2. Funciona como prova de conceito para potenciais clientes
3. Reflecte a identidade visual da marca (ver abaixo)
4. Pode evoluir para o website oficial da Nodeflow

---

## Identidade da marca Nodeflow

**Nome:** Nodeflow  
**Slogan principal:** Menos atrito. Mais impacto.  
**Slogan longo:** Do processo manual à vantagem competitiva.

**Paleta:**
- Ink: `#0e0e0e` (principal, fundos escuros)
- Paper: `#f5f4f0` (fundo claro, texto invertido)
- Signal: `#00c896` (acento verde, destaque, nó activo)
- Electric: `#1a1aff` (variante azul, uso pontual)
- Stone: `#9a9690` (texto secundário, labels)

**Tipografia:**
- Wordmark / headings: DM Mono (Google Fonts) — weights 300/400/500
- Slogan / corpo emocional: Fraunces Italic Light 300 (Google Fonts)

**Logótipo:** Grid modular 2×2 — ver `nodeflow_icon_marca.svg`  
**Brand kit completo:** ver `nodeflow_brand_kit_v3.svg`

**Tom:** Técnico, preciso, sem ruído. Minimalista e sóbrio.

---

## Apps a apresentar no portfolio

### 1 · Portal de Notas de Despesa
- **Stack:** HTML / CSS / JavaScript / pdf-lib
- **O que faz:** Formulário de despesas com assinatura digital, geração de PDF, exportação CSV, integração Gmail. 33 centros de custo. Single-file.
- **Cliente-alvo:** PMEs e multinacionais com processo de reembolso manual
- **Status:** Pronto. Em pitch interno na Norauto.

### 2 · Painel de Crescimento Pessoal (Alpha2026)
- **Stack:** HTML / JavaScript / Gemini API
- **O que faz:** Briefing diário com Gemini, registo de decisões estruturado, tracker KPIs semanal, STT em PT, export .md/.txt
- **Cliente-alvo:** Gestores, founders, profissionais de alta performance
- **Status:** Operacional. Uso pessoal activo.

### 3 · VisionAI+
- **Stack:** React 18 + TypeScript + Vite + Tailwind + Firebase Auth + Gemini API + Google Cloud Run
- **O que faz:** Interface RAG bilíngue PT/FR, 6+ casos de uso operacionais (stock, logística, e-commerce), validador de ideias, arquitectura proxy segura
- **Versão:** v2.9.5
- **Cliente-alvo:** Multinacionais com operação em PT/FR sem equipa técnica de dados
- **Status:** Versão Norauto congelada. Reformulação white-label em curso.

### 4 · Logic Gate Trainer
- **Stack:** React 18 + TypeScript + Gemini API + React Router
- **O que faz:** Exercícios de portas lógicas gerados por Gemini, sistema de jogo com streak/scoreboard/histórico, hints com IA, confetti
- **Cliente-alvo:** Plataformas e-learning, escolas técnicas, formação em TI
- **Status:** Operacional. Deployed em GitHub Pages.

### 5 · Análise de Propostas de Crédito Habitação
- **Stack:** React 18 + TypeScript + Gemini API + Recharts + jsPDF + pdf.js
- **O que faz:** Comparação visual de propostas de crédito (TAN, TAEG, seguros, custos), leitura de PDFs, chat IA, exportação de relatório PDF
- **Cliente-alvo:** Famílias, brokers imobiliários, consultores financeiros
- **Status:** Operacional.

### 6 · Treino e Diagnóstico Ocular (Visão+)
- **Stack:** React 18 + TypeScript + localStorage
- **O que faz:** 6 exercícios visuais guiados, diagnóstico ocular (acuidade, Amsler, questionário), regra 20-20-20, histórico de diagnósticos
- **Cliente-alvo:** Clínicas de oftalmologia, ópticas, plataformas de saúde digital
- **Status:** Operacional.

### 7 · Gestor de Quotas AZP
- **Stack:** React 18 + TypeScript + Gemini API
- **O que faz:** Gestão de quotas de associados com IA integrada
- **Cliente-alvo:** Associações desportivas, culturais, profissionais
- **Status:** Em desenvolvimento / modo teste.

### 8 · Hiperfrio O2C Reader (RAG)
- **Stack:** Node.js + Express + Gemini API + pdf.js + RAG local
- **O que faz:** Sistema RAG para análise de documentos O2C (Order-to-Cash). Lê PDFs de encomendas, cruza com memória local (preços, catálogo, compatibilidade, SLA), sugere peças, gera ordens de trabalho, integração com ERP PHC, voz-para-texto.
- **Cliente-alvo:** Empresas de distribuição com processo O2C manual. Cliente actual: Hiperfrio.
- **Status:** v2.1 operacional. Deploy-ready (Render).

### 9 · Envio de Emails em Massa (Automagic)
- **Stack:** Python (smtplib) + Google Apps Script + HTML
- **O que faz:** Envio automatizado de emails em massa com mail merge. Lê lista de destinatários (CSV/TXT), envia via Gmail SMTP, suporta anexos. Disponível como app web e executável standalone (.exe).
- **Cliente-alvo:** PMEs, associações e equipas comerciais sem orçamento para plataformas pagas (Mailchimp, etc.)
- **Status:** Operacional. Versão web + versão executável.

### 10 · Vocaliz
- **Stack:** HTML / CSS / JavaScript (Web Speech API)
- **O que faz:** Leitor de texto em voz alta (TTS). Suporta texto colado, upload de ficheiros (txt, md, csv, html, srt, pdf, docx, xlsx), detecção de tabelas, controlo de voz/velocidade/pitch, barra de progresso.
- **Cliente-alvo:** Utilizadores com dificuldades de leitura, profissionais que consomem conteúdo em movimento, plataformas de acessibilidade
- **Status:** Operacional. Logótipo Nodeflow incluído.

---

## Decisões de stack

**Stack escolhido para o site:** HTML + CSS + JS single-file
- Sem dependências, sem build tools
- Deploy imediato (GitHub Pages / Netlify)
- Animações via CSS transitions (sem Framer Motion)
- Pronto para mostrar a clientes e no LinkedIn

---

## O que o dashboard deve ter (requisitos mínimos)

- [ ] Hero com nome, slogan e identidade visual da Nodeflow
- [ ] Cards de cada app com: nome, descrição curta, stack, status, cliente-alvo
- [ ] Filtro por categoria (B2B / educação / saúde / finanças / produtividade)
- [ ] Design fiel à identidade da marca (paleta + tipografia acima)
- [ ] Responsivo (mobile + desktop)
- [ ] Pronto para mostrar a um potencial cliente

## Extras desejáveis (não obrigatórios na v1)

- [ ] Animações subtis de entrada
- [ ] Modal ou drawer com detalhe de cada app
- [ ] Secção "Sobre a Nodeflow" com posicionamento
- [ ] Formulário de contacto
- [ ] Deploy fácil (Vercel / GitHub Pages)

---

## Ficheiros nesta pasta

| Ficheiro | Descrição |
|---|---|
| `CLAUDE.md` | Este ficheiro — contexto completo para o Claude Code |
| `nodeflow_identidade_marca.md` | Documento vivo de identidade de marca com todas as decisões |
| `nodeflow_brand_kit_v3.svg` | Brand kit visual completo |
| `nodeflow_icon_marca.svg` | Ícone Nodeflow em todas as variantes |
| `Matriz Estratégica de Domínios e Técnicas.jpg` | Framework de Capacidades de IA v1.0 (Fábio Andreosi) |
| `.mcp.json` | Configuração MCP — servidor NotebookLM activo |

---

## Como trabalhar comigo

- Fala comigo em **português de Portugal**
- Quando tiveres dúvidas sobre decisões de produto ou marca, pergunta — não assumas
- Prefiro código limpo e bem estruturado a código rápido e sujo
- Documenta as decisões técnicas relevantes neste ficheiro ou num `DECISIONS.md` separado
- Commita com mensagens claras em inglês (convenção: `feat:`, `fix:`, `refactor:`, `docs:`)
