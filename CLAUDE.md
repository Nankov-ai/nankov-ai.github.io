# Nodeflow · Website de Portfolio · Contexto para Claude Code

## Quem sou eu

Fernando Costa (Nando) — founder da Nodeflow, empresa de criação de apps e automação de agentes com IA.
Estou em part-time na Norauto (gestão de categoria internacional) e a construir a Nodeflow em simultâneo.
Background: gestão + IA aplicada. Stack habitual: React 18 + TypeScript + Vite + Tailwind + Gemini API.

---

## Estado actual do projecto

**Site live:** `https://nankov-ai.github.io`  
**Repositório:** `https://github.com/Nankov-ai/nankov-ai.github.io`  
**Branch:** `main` — deploy automático via GitHub Pages  
**Stack do site:** HTML + CSS + JS · single-file (`index.html`)

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

**Logótipo:** Grid modular 2×2 — inline SVG no `index.html`  
**Tom:** Técnico, preciso, sem ruído. Minimalista e sóbrio.

---

## Apps no portfolio (14 cards)

### 01 · Portal de Notas de Despesa
- **Stack:** HTML / CSS / JavaScript / pdf-lib
- **Link:** `https://nankov-ai.github.io/Nota-Despesa/`
- **O que faz:** Formulário de despesas com assinatura digital, geração de PDF, exportação CSV, integração Gmail. 33 centros de custo. Single-file.
- **Cliente-alvo:** PMEs e multinacionais com processo de reembolso manual
- **Status:** Operacional · Pitch activo na Norauto

### 02 · VisionAI+
- **Stack:** React 18 + TypeScript + Vite + Tailwind + Firebase Auth + Gemini API + Google Cloud Run
- **Link:** `https://app-norautovisionai-dev-325763202780.europe-west1.run.app/`
- **O que faz:** Interface RAG bilíngue PT/FR, 6+ casos de uso operacionais (stock, logística, e-commerce), validador de ideias, arquitectura proxy segura
- **Versão:** v2.9.5
- **Cliente-alvo:** Multinacionais com operação em PT/FR sem equipa técnica de dados
- **Status:** Versão Norauto congelada. Reformulação white-label em curso.

### 03 · Nodeflow O2C Reader
- **Stack:** Node.js + Express + Gemini API + pdf.js + RAG local
- **Link:** `https://nodeflow-o2c.onrender.com/` (Render free tier — ~30s arranque)
- **Repositório:** `https://github.com/Nankov-ai/hiperfrio-o2c-rag`
- **O que faz:** Sistema RAG para análise de documentos O2C. Lê PDFs de encomendas, cruza com catálogo e SLA locais, sugere peças, gera ordens de trabalho, integra com ERP PHC, voz-para-texto.
- **Cliente-alvo:** Empresas de distribuição com processo O2C manual
- **Status:** v2.1 operacional · White-label sem referências a cliente

### 04 · Análise de Crédito Habitação
- **Stack:** React 18 + TypeScript + Gemini API + Recharts + jsPDF + pdf.js
- **Link:** `https://nankov-ai.github.io/Analise-Credito-Habitacao/`
- **O que faz:** Comparação visual de propostas de crédito (TAN, TAEG, seguros, custos), leitura de PDFs, chat IA, exportação de relatório PDF. API key inserida pelo utilizador na UI.
- **Cliente-alvo:** Famílias, brokers imobiliários, consultores financeiros
- **Status:** Operacional

### 05 · Alpha2026
- **Stack:** HTML / JavaScript / Gemini API
- **Link:** `https://nankov-ai.github.io/2026-Alpha/`
- **O que faz:** Briefing diário com Gemini, registo de decisões estruturado, tracker KPIs semanal, STT em PT, export .md/.txt
- **Cliente-alvo:** Gestores, founders, profissionais de alta performance
- **Status:** Operacional · Uso pessoal activo

### 06 · Logic Gate Trainer
- **Stack:** React 18 + TypeScript + Gemini API + React Router
- **Link:** `https://nankov-ai.github.io/Treinador_de_Logica/`
- **O que faz:** Exercícios de portas lógicas gerados por Gemini, sistema de jogo com streak/scoreboard/histórico, hints com IA, confetti
- **Cliente-alvo:** Plataformas e-learning, escolas técnicas, formação em TI
- **Status:** Operacional

### 07 · Treino e Diagnóstico Ocular
- **Stack:** React 18 + TypeScript + localStorage
- **Link:** `https://nankov-ai.github.io/Treino-Ocular/`
- **O que faz:** 6 exercícios visuais guiados, diagnóstico ocular (acuidade, Amsler, questionário), regra 20-20-20, histórico de diagnósticos
- **Cliente-alvo:** Clínicas de oftalmologia, ópticas, plataformas de saúde digital
- **Status:** Operacional

### 08 · Gestor de Quotas
- **Stack:** React 18 + TypeScript + Gemini API
- **Link:** `https://nankov-ai.github.io/Gestor-de-Quotas/`
- **O que faz:** Gestão de quotas de associados com IA integrada
- **Cliente-alvo:** Associações desportivas, culturais, profissionais
- **Status:** Operacional · modo teste

### 09 · Automagic · Envio de Emails
- **Stack:** Python (smtplib) + Google Apps Script + HTML
- **Link:** `https://nankov-ai.github.io/Envio-de-emails-em-massa---Script/`
- **O que faz:** Envio automatizado de emails personalizados em massa. Mail merge via Gmail SMTP. Lê CSV/TXT, suporta anexos. App web + executável .exe.
- **Cliente-alvo:** PMEs e equipas comerciais sem orçamento para Mailchimp
- **Status:** Operacional

### 10 · Vocaliz
- **Stack:** HTML / CSS / JavaScript (Web Speech API)
- **Link:** `https://nankov-ai.github.io/Vocaliz/`
- **O que faz:** Leitor TTS com suporte a 8 formatos (txt, md, csv, html, srt, pdf, docx, xlsx), detecção de tabelas, controlo de voz/velocidade/pitch, barra de progresso.
- **Cliente-alvo:** Utilizadores com dificuldades de leitura, profissionais em movimento, plataformas de acessibilidade
- **Status:** Operacional

### 11 · NeoOtto
- **Stack:** HTML / CSS / JavaScript / ChatGPT
- **Link:** `https://nankov-ai.github.io/NeoOtto.github.io/`
- **O que faz:** Agente de IA especializado em identificar oportunidades de negócio. Diagnóstico de contexto, benchmark de mercado, recomendações práticas em linguagem executiva.
- **Cliente-alvo:** Gestores e empresas que querem perceber onde a IA pode gerar impacto real
- **Status:** Operacional

### 12 · HealHour
- **Stack:** HTML / CSS / JavaScript · PWA
- **Link:** `https://nankov-ai.github.io/Healing-jejum/`
- **Repositório:** `https://github.com/Nankov-ai/Healing-jejum`
- **O que faz:** PWA de tracking de jejum intermitente. Anel de progresso em tempo real, fases metabólicas, protocolos configuráveis (16h, 18h, 24h), histórico. Instalável no telemóvel.
- **Cliente-alvo:** Pessoas que praticam jejum intermitente sem apps pagas
- **Status:** Operacional

### 13 · OutOfBox
- **Stack:** Next.js + TypeScript + Prisma + IA
- **Link:** `https://outofbox.onrender.com` (Render free tier — ~30s arranque)
- **O que faz:** Coach de mentalidade com IA. Transforma pensamentos limitantes em perguntas de crescimento. Cada desafio é ressignificado como oportunidade.
- **Cliente-alvo:** Profissionais e líderes que querem desenvolver mentalidade de crescimento
- **Status:** Operacional

### 14 · English Adventure
- **Stack:** HTML / CSS / JavaScript
- **Link:** `https://nankov-ai.github.io/English-Adventure/`
- **O que faz:** App de aprendizagem de inglês para crianças com 4 jogos interactivos: Match, Quiz, Unscramble e Complete the Sentence. Vocabulário de partes do corpo, pontuação em tempo real, sistema de hints.
- **Cliente-alvo:** Escolas, professores de inglês e plataformas de ensino para crianças
- **Status:** Operacional

---

## Decisões técnicas tomadas

### Site (index.html)
- **Single-file** HTML + CSS + JS — sem build tools, sem dependências
- **Deploy:** GitHub Pages via repo `nankov-ai.github.io` (branch `main`)
- **Tipografia:** DM Mono + Fraunces via Google Fonts
- **Animações:** CSS transitions apenas (sem Framer Motion)
- **Responsivo:** mobile-first, max-width 1280px com clamp padding
- **Back-to-top:** botão discreto 30px, aparece ao scroll, desaparece após 1.5s inactividade e perto do footer

### Cards do portfolio
- **Formato:** Desafio → Resultado (não só features técnicas)
- **Botão "Fale connosco":** email picker contextual por card (Gmail / Outlook / Copiar) via `mailto:` com subject e body pré-preenchidos com o nome da app

### Contacto
- **Email picker** em todos os botões "Fale connosco" do site (nav, hero, CTA card, secção contacto, cada card)
- **Sem formulários externos** — usa Gmail e Outlook web directamente
- **Email:** `nodeflow.pt@gmail.com`

### Secções do site
1. Hero (slogan + CTA)
2. Stats (14 apps / 8 com IA / 5 só automação / 5 sectores)
3. Portfolio (14 cards + CTA card verde)
4. Como trabalhamos (Diagnóstico → Construção → Entrega)
5. Sobre a Nodeflow (texto + 4 pillars)
6. Contacto
7. Footer

---

## Ficheiros nesta pasta

| Ficheiro | Descrição |
|---|---|
| `index.html` | Site completo — HTML + CSS + JS single-file |
| `CLAUDE.md` | Este ficheiro — contexto completo para o Claude Code |
| `diagrams.md` | Diagramas Mermaid do projecto (portfolio, processo, arquitectura, roadmap) |

---

## Roadmap

### Fase 1 · Concluída
- [x] Secção "Como trabalhamos"
- [x] Cards com formato Desafio → Resultado
- [x] Email picker contextual em todos os CTAs

### Fase 2 · A fazer
- [ ] Secção de modelos de colaboração (o que ofereces e como contratar)
- [ ] Gráficos dinâmicos — crescimento de apps ao longo do tempo

### Fase 3 · Futuro
- [ ] Dashboard de leads (lead → proposta → cliente)
- [ ] Login + demos privadas para clientes específicos
- [ ] Painel de métricas interno

### Fase 4 · Novo produto
- [ ] Agente de marketing/folhetos para retalho

---

## Como trabalhar comigo

- Fala comigo em **português de Portugal**
- Quando tiveres dúvidas sobre decisões de produto ou marca, pergunta — não assumas
- Prefiro código limpo e bem estruturado a código rápido e sujo
- Commita com mensagens claras em inglês (convenção: `feat:`, `fix:`, `refactor:`, `docs:`)
- Não adicionar features não pedidas, não criar ficheiros desnecessários
