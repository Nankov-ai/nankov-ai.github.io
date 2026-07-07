# Nodeflow · Website de Portfolio · Contexto para Claude Code

## Quem sou eu

Fernando Costa (Nando) — founder da Nodeflow, empresa de criação de apps e automação de agentes com IA.
Estou em part-time na Norauto (gestão de categoria internacional) e a construir a Nodeflow em simultâneo.
Background: gestão + IA aplicada. Stack habitual: React 18 + TypeScript + Vite + Tailwind + Gemini API.

---

## Estado actual do projecto

**Site live:** `https://nodeflow.pt` (custom domain — antigo: `https://nankov-ai.github.io`, redireccionado automaticamente)  
**Repositório:** `https://github.com/Nankov-ai/nankov-ai.github.io`  
**Branch:** `main` — deploy automático via GitHub Pages  
**Stack do site:** HTML + CSS + JS · single-file (`index.html`)  
**Domínio:** `nodeflow.pt` registado no PTisp (2026-07-02, expira 2027-07-02) — DNS gerido via PTisp Parqueamento (Gestor de DNS). HTTPS activo via GitHub Pages (Let's Encrypt).

**Nota deploy:** GitHub Pages Actions mostra "deploy timeout" desde que o custom domain foi configurado — o site funciona correctamente em `nodeflow.pt`. Problema cosmético nos logs, esperado resolver-se sozinho em 24-48h após estabilização do domínio.

**Último deploy:** 2026-07-07 — T&C gate + PT/EN modais + fix refresh bypass + separador PT/EN·✕

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
- Stone: `#aba6a1` (texto secundário, labels — ajustado para WCAG AA ~5.3:1)

**Tipografia:**
- Wordmark / headings: DM Mono — weights 300/400/500
- Slogan / corpo emocional: Fraunces Italic Light 300
- **Fontes self-hosted** em `fonts/` (woff2) — sem Google Fonts (GDPR)

**Logótipo:** Grid modular 2×2 — inline SVG no `index.html`  
**Tom:** Técnico, preciso, sem ruído. Minimalista e sóbrio.

---

## Apps no portfolio (17 cards)

### 01 · Portal de Notas de Despesa
- **Stack:** HTML / CSS / JavaScript / pdf-lib
- **Link:** `https://nankov-ai.github.io/nota-despesa-nodeflow`
- **Repositório:** `https://github.com/Nankov-ai/nota-despesa-nodeflow`
- **Local:** `c:/projetos/Nodeflow/Nota Despesa Nodeflow/`
- **O que faz:** Formulário de despesas com assinatura digital, geração de PDF, exportação CSV, integração Gmail. 33 centros de custo. Single-file.
- **Cliente-alvo:** PMEs e multinacionais com processo de reembolso manual
- **Status:** Operacional · Versão Nodeflow-branded

### 02 · VisionAI+ Demo
- **Stack:** React + Gemini API + Cloud Run
- **Link:** `https://visionai-app-769195178908.europe-west1.run.app/`
- **O que faz:** Demo white-label da plataforma VisionAI+ — análise de imagem e documentos com IA, pronta a adaptar ao contexto de qualquer empresa.
- **Cliente-alvo:** Empresas que queiram avaliar a plataforma antes de uma implementação à medida
- **Status:** Demo online

### 03 · NVisionAI+
- **Stack:** React 18 + TypeScript + Vite + Tailwind + Firebase Auth + Gemini API + Google Cloud Run
- **Link:** `https://app-norautovisionai-dev-325763202780.europe-west1.run.app/`
- **Local:** `c:/projetos/6. norauto-visionai+/`
- **O que faz:** Interface RAG bilíngue PT/FR, 6+ casos de uso operacionais (stock, logística, e-commerce), validador de ideias, arquitectura proxy segura
- **Versão:** v2.9.5
- **Cliente-alvo:** Multinacionais com operação em PT/FR sem equipa técnica de dados
- **Status:** Versão Norauto congelada. Reformulação white-label em curso.

### 04 · Nodeflow O2C Reader
- **Stack:** Node.js + Express + Gemini API + pdf.js + RAG local
- **Link:** `https://nodeflow-o2c.onrender.com/` (Render free tier — ~30s arranque)
- **Repositório:** `https://github.com/Nankov-ai/hiperfrio-o2c-rag`
- **Local:** `c:/projetos/4. hiperfrio-o2c-rag/`
- **O que faz:** Sistema RAG para análise de documentos O2C. Lê PDFs de encomendas, cruza com catálogo e SLA locais, sugere peças, gera ordens de trabalho, integra com ERP PHC, voz-para-texto.
- **Cliente-alvo:** Empresas de distribuição com processo O2C manual
- **Status:** v2.1 operacional · White-label (AIssist)

### 05 · Análise de Crédito Habitação
- **Stack:** React 18 + TypeScript + Gemini API + Recharts + jsPDF + pdf.js
- **Link:** `https://nankov-ai.github.io/Analise-Credito-Habitacao/`
- **Local:** `c:/projetos/5. análise-propostas-de-crédito-habitação-final/`
- **O que faz:** Comparação visual de propostas de crédito em TAN, TAEG, seguros, custos totais. Leitura de PDFs, chat IA, exportação de relatório PDF. API key inserida pelo utilizador na UI.
- **Cliente-alvo:** Famílias, brokers imobiliários, consultores financeiros
- **Status:** Operacional

### 06 · Alpha2026
- **Stack:** HTML / JavaScript / Gemini API
- **Link:** `https://nankov-ai.github.io/2026-Alpha/`
- **Local:** `c:/projetos/8. Alpha2026/`
- **O que faz:** Briefing diário com Gemini, registo de decisões estruturado, tracker KPIs semanal, STT em PT, export .md/.txt
- **Cliente-alvo:** Gestores, founders, profissionais de alta performance
- **Status:** Operacional · Uso pessoal activo

### 07 · Logic Gate Trainer
- **Stack:** React 18 + TypeScript + Gemini API + React Router
- **Link:** `https://nankov-ai.github.io/Treinador_de_Logica/`
- **Local:** `c:/projetos/2. logic-gate-trainer/`
- **O que faz:** Exercícios de portas lógicas gerados por Gemini, sistema de jogo com streak/scoreboard/histórico, hints com IA, confetti
- **Cliente-alvo:** Plataformas e-learning, escolas técnicas, formação em TI
- **Status:** Operacional

### 08 · Treino e Diagnóstico Ocular
- **Stack:** React 18 + TypeScript + localStorage
- **Link:** `https://nankov-ai.github.io/Treino-Ocular/`
- **Local:** `c:/projetos/1. treino-e-diagnóstico-ocular/`
- **O que faz:** 6 exercícios visuais guiados, diagnóstico ocular (acuidade, Amsler, questionário), regra 20-20-20, histórico de diagnósticos
- **Cliente-alvo:** Clínicas de oftalmologia, ópticas, plataformas de saúde digital
- **Status:** Operacional

### 09 · Gestor de Quotas
- **Stack:** React 18 + TypeScript + Gemini API
- **Link:** `https://nankov-ai.github.io/Gestor-de-Quotas/`
- **Local:** `c:/projetos/3. gestor-de-quotas---azp-(modo-de-teste)/Gestor-de-Quotas/`
- **O que faz:** Gestão de quotas de associados com IA integrada
- **Cliente-alvo:** Associações desportivas, culturais, profissionais
- **Status:** Operacional · modo teste

### 10 · Automagic Mail · Envio com Rastreio
- **Stack:** Python + Flask + Google Apps Script + HTML
- **Link:** `https://nankov-ai.github.io/Envio-de-emails-com-registo/`
- **Repositório:** `https://github.com/Nankov-ai/Envio-de-emails-com-registo`
- **Local:** `c:/projetos/Envio de emails com registo/`
- **O que faz:** Portal web que envia dezenas ou centenas de emails de uma só vez, cada um personalizado com o nome, empresa e dados específicos de cada contacto (via CSV). Links UTM automáticos por destinatário para rastreio de cliques no Google Analytics. Pixel de rastreio de aberturas via GAS (limitado — Apple Mail/Gmail bloqueiam). Registo automático de todos os envios em Google Sheets. Suporte a anexos.
- **Cliente-alvo:** PMEs e equipas comerciais que precisam de rastreio de campanhas sem serviços pagos
- **Status:** Operacional
- **Landing page:** `c:/projetos/Envio de emails com registo/index.html` — Nodeflow-branded, sem referências ao cliente. Ficheiros da cliente em `Clientes/Marina Ferreira/`
- **Nota:** Não mencionar marcas concorrentes (ex: Mailchimp) em nenhum texto do site ou landing page

### 11 · Vocaliz
- **Stack:** HTML / CSS / JavaScript (Web Speech API)
- **Link:** `https://nankov-ai.github.io/Vocaliz/`
- **Local:** `c:/projetos/Vocaliz/`
- **O que faz:** Leitor TTS com suporte a 8 formatos (txt, md, csv, html, srt, pdf, docx, xlsx), detecção de tabelas, controlo de voz/velocidade/pitch, barra de progresso.
- **Cliente-alvo:** Utilizadores com dificuldades de leitura, profissionais em movimento, plataformas de acessibilidade
- **Status:** Operacional

### 12 · NeoOtto
- **Stack:** HTML / CSS / JavaScript / ChatGPT
- **Link:** `https://nankov-ai.github.io/NeoOtto.github.io/`
- **Local:** `c:/projetos/NeoOtto/`
- **O que faz:** Agente de IA especializado em identificar oportunidades de negócio. Diagnóstico de contexto, benchmark de mercado, recomendações práticas em linguagem executiva.
- **Cliente-alvo:** Gestores e empresas que querem perceber onde a IA pode gerar impacto real
- **Status:** Operacional

### 13 · HealHour
- **Stack:** HTML / CSS / JavaScript · PWA
- **Link:** `https://nankov-ai.github.io/Healing-jejum/`
- **Repositório:** `https://github.com/Nankov-ai/Healing-jejum`
- **Local:** `c:/projetos/2H HealHour/`
- **O que faz:** PWA de tracking de jejum intermitente. Anel de progresso em tempo real, fases metabólicas, protocolos configuráveis (16h, 18h, 24h), histórico. Instalável no telemóvel.
- **Cliente-alvo:** Pessoas que praticam jejum intermitente sem apps pagas
- **Status:** Operacional
- **Nota:** `manifest.json` e `<title>` renomeados de "Jejum" → "HealHour" (2026-06-18) — o nome antigo aparecia nas notificações e painel de apps do Chrome. Para reflectir a mudança, o utilizador tem de desinstalar e reinstalar a PWA.

### 14 · OutOfBox
- **Stack:** Next.js + TypeScript + Prisma + IA
- **Link:** `https://outofbox.onrender.com` (Render free tier — ~30s arranque)
- **Local:** `c:/projetos/OutOfBox/`
- **O que faz:** Coach de mentalidade com IA. Transforma pensamentos limitantes em perguntas de crescimento. Cada desafio é ressignificado como oportunidade.
- **Cliente-alvo:** Profissionais e líderes que querem desenvolver mentalidade de crescimento
- **Status:** Operacional

### 15 · English Adventure
- **Stack:** HTML / CSS / JavaScript
- **Link:** `https://nankov-ai.github.io/English-Adventure/`
- **Local:** `c:/projetos/English Adventure/`
- **O que faz:** App de aprendizagem de inglês para crianças com 4 jogos interactivos: Match, Quiz, Unscramble e Complete the Sentence. Vocabulário de partes do corpo, pontuação em tempo real, sistema de hints.
- **Cliente-alvo:** Escolas, professores de inglês e plataformas de ensino para crianças
- **Status:** Operacional

### 16 · Voz Afiada
- **Stack:** Gemini · IA Agent
- **Link:** `https://gemini.google.com/gem/1aRNCCqYq-TJREAyE_DZerH9gEiVl6REZ?usp=sharing`
- **O que faz:** Diagnóstico cirúrgico da comunicação verbal — sem filtros. Identifica fillers, fraqueza de autoridade e estrutura ineficiente. Reescreve. Exige.
- **Cliente-alvo:** Fundadores, comerciais e executivos que negoceiem, apresentem ou liderem
- **Status:** Em desenvolvimento · Lançamento em breve
- **Nota estratégica:** Potencial para produto standalone com waitlist — posicionamento diferenciador, sem concorrência directa no segmento de crítico de comunicação

### 17 · AudiNote
- **Stack:** Kotlin + Jetpack Compose + Gemini API (`gemini-3.5-flash`) + Room v3 + Hilt + Android (Min SDK 31)
- **Landing page:** `https://nankov-ai.github.io/Ouvinte---AudiNote/`
- **Repositório landing:** `https://github.com/Nankov-ai/Ouvinte---AudiNote`
- **Local:** `c:/projetos/Ouvinte/` (nome interno: Ouvinte; nome público: AudiNote)
- **APK:** `APP Android/AudiNote-v1.0.0.apk` (flavor `distribution` — sem chaves, utilizador insere as suas)
- **O que faz:** App nativa Android para gravar palestras/reuniões com auto-split inteligente (17 MB). Transcreve com Gemini (diarização de oradores), traduz para pt-PT, extrai tópicos, fact-check via Google Custom Search, gera perguntas inteligentes por orador. Pastas de projeto, PDF unificado de pasta, partilha de áudio (.m4a). PIN de acesso. Persistência total em Room DB.
- **Cliente-alvo:** Profissionais, founders e estudantes que não podem perder o que ouvem
- **Status:** Beta · Acesso antecipado (APK distribuído manualmente via email)
- **Nota site:** Card com botão "Quero testar" que abre modal com formulário RGPD-compliant → compõe email para nodeflow.pt@gmail.com com dados do candidato
- **AI Act:** Art. 50 aplicável — aviso incluído no card e no modal

---

## Decisões técnicas tomadas

### Site (index.html)
- **Single-file** HTML + CSS + JS — sem build tools, sem dependências
- **Deploy:** GitHub Pages via repo `nankov-ai.github.io` (branch `main`)
- **Tipografia:** DM Mono + Fraunces — **self-hosted** em `fonts/` (woff2), sem Google Fonts
- **Animações:** CSS transitions apenas (sem Framer Motion)
- **Responsivo:** mobile-first, max-width 1280px com clamp padding
- **Back-to-top:** botão discreto 30px, aparece ao scroll, desaparece após 1.5s inactividade e perto do footer
- **Localhost para preview:** `python -m http.server 3000` em `c:/projetos/Nodeflow/` (parar: `taskkill /f /im python.exe`)

### Hero
- **Layout duas colunas:** texto à esquerda + painel de métricas à direita (colapsa para coluna única abaixo de 900px)
- **Painel de métricas:** 3 processos reais com tempos antes/depois + barras animadas + 3 stats (−94% tempo, 0 erros, 17 apps)
- **CTAs:** "Fale connosco" (primário verde) + "Ver portfolio →" (ghost)
- **Keyword highlight:** "Mais impacto." em Signal green

### Cards do portfolio

**Ordem actual dos cards (por impacto empresarial decrescente):**
```
01 · Faturix (strategic)
02 · VisionAI+ Demo (strategic)
03 · Nodeflow O2C Reader (strategic)
04 · NVisionAI+ (strategic)
05 · AudiNote (featured, audinate-card)
06 · Voz Afiada (featured, voz-afiada-card)
07 · NeoOtto
08 · OutOfBox
09 · Análise de Crédito Habitação (strategic)
10 · Gestor de Quotas
11 · Alpha2026
12 · Logic Gate Trainer
13 · Automagic Mail
14 · Portal de Notas de Despesa
15 · Vocaliz
16 · HealHour
17 · Treino e Diagnóstico Ocular
18 · English Adventure
19 · LipRead (coming soon)
```
*Nota: os títulos das secções de detalhe acima mantêm a numeração original — a ordem de apresentação no site é a desta lista.*

- **Formato:** Desafio → Resultado (não só features técnicas)
- **Botão "Fale connosco":** email picker contextual por card (Gmail / Outlook / Copiar) — gerado em JS, excluindo `.audinate-card`
- **Hierarquia visual:** `.strategic` (cards 01, 02, 03, 04, 09, 19) com borda Signal subtil; `.featured` (cards 05 AudiNote e 06 Voz Afiada) com glow máximo
- **Total:** 19 cards + 1 CTA card verde no final
- **Regra de copy:** nunca mencionar marcas de terceiros (Mailchimp, etc.) — usar "serviços externos", "serviços pagos" ou similar
- **Cards expansíveis:** tagline (desafio/resultado) sempre visível; "Para quem", stack tags e "Fale connosco" colapsados por defeito atrás de botão "Ver mais ↓" / "Ver menos ↑". Implementado via JS que cria `.card-details` wrapper + `.card-toggle` button após a tagline. O contact wrap (`card-contact-wrap`) é injectado para dentro do `.card-details`. `.audinate-card` incluído (card-note movido para dentro de card-bottom para ficar dentro do card-details). Excluído apenas do contact-wrap JS (tem fluxo próprio de beta access via `audinate-open-btn`).
- **Expansão sincronizada por linha (desktop):** clicar "Ver mais ↓" num card expande todos os cards da mesma linha em simultâneo (detectado via `getBoundingClientRect().top` com tolerância de 10px). Em mobile (< 700px) cada card expande independentemente.
- **"Para quem:" em Signal green:** `.card-client strong { color: var(--signal) }` — destaca o label em todos os cards expandidos.
- **Voz Afiada — caixa de feedback:** `.voz-afiada-card` tem class própria; excluído do contact-wrap automático; injected via JS dentro de `.card-details` com botão "Já testaste? Diz-nos o que achaste →" que abre email picker (Gmail / Outlook / Copiar) com assunto pré-preenchido "Feedback Voz Afiada". Status: "Gemini Gem · Em testes".

### PT/EN Bilingue
- **Switcher:** botões PT/EN no nav e no footer de ambos os sites
- **Mecanismo:** `html[data-lang="en"]` no elemento `<html>` via `setAttribute`
- **CSS:** `.lang-en { display:none }` por defeito; `html[data-lang="en"] .lang-pt { display:none }` + `html[data-lang="en"] .lang-en { display:inline }` + `html[data-lang="en"] .lang-en.lang-blk { display:block }`
- **Atenção (bug resolvido):** usar `.lang-en.lang-blk` e NÃO `.lang-blk` — especificidade igual causaria `.lang-pt` visível em EN
- **Persistência:** `localStorage('nf-lang')` — valor `'pt'` ou `'en'`
- **Nomes de produto:** nunca traduzir — "Notas de Despesa", "Análise de Crédito", etc. ficam sempre em PT
- **Sites cobertos:** `index.html` (Nodeflow) e `c:/projetos/Ouvinte/index.html` (AudiNote landing page)

### Privacidade & Segurança (GDPR + AI Act)
- **Google Fonts removido** — fontes servidas localmente de `fonts/`
- **`rel="noopener noreferrer"`** em todos os 21+ links externos
- **Modal de privacidade** no footer (link "Privacidade") — sem cookies, sem analytics, fontes locais
- **Aviso AI Act Art. 50** adicionado a todas as apps com IA interactiva: NeoOtto, Alpha2026, O2C Reader, Logic Gate Trainer, Gestor de Quotas, Análise de Crédito, OutOfBox, NVisionAI+
- **Pilar "Privacidade & Segurança"** na secção Sobre (substituiu "Publicação imediata")
- **Parágrafo de privacidade** no texto da secção Sobre

### Open Graph & LinkedIn
- **Ficheiro:** `og-image.png` (1200×630, gerada a @2x via Puppeteer) — committed com `git add -f` (está no `.gitignore`)
- **Conteúdo:** fundo Ink, lado esq logótipo grid 2×2 + "NODEFLOW" em DM Mono, lado dir slogan em Fraunces Italic + linha Stone + "19 SOLUÇÕES OPERACIONAIS · IA APLICADA · NANKOV-AI.GITHUB.IO"
- **Meta tags no `<head>`:** `og:type`, `og:url`, `og:title`, `og:description`, `og:image` (1200×630), `twitter:card`, `twitter:image`
- **URL da imagem:** `https://nankov-ai.github.io/og-image.png`
- **Regenerar:** usar Puppeteer com HTML template no scratchpad (DM Mono + Fraunces carregadas de `fonts/`)

### Cloudflare Web Analytics
- **Script** adicionado antes de `</body>` no `index.html`
- **Token:** `6cd3ccdf96774611bb3e1f52aff7e023`
- **Dashboard:** dash.cloudflare.com → Analytics → Web Analytics
- **GDPR-compliant:** sem cookies, sem rastreio individual de visitantes
- **Custo:** gratuito, sem limites de pageviews

### Favicon & Ícone Mobile
- **Ficheiro:** `favicon.svg` — logótipo Nodeflow (grid 2×2: topo-esq Paper, topo-dir outline, baixo-esq outline, baixo-dir Signal green), fundo `#0e0e0e`
- **`<head>`:** `<link rel="icon" type="image/svg+xml" href="favicon.svg">` + `<link rel="apple-touch-icon" href="favicon.svg">`
- **Problema resolvido:** sem favicon definido, o browser mobile usava o ícone em cache do HealHour (PWA com manifest)

### Datas de actualização nos cards
- **Mecanismo:** cada card tem `<div class="card-date">` com `<span class="lang-pt">` e `<span class="lang-en">` (formato: `Abr 2026` / `Apr 2026`)
- **Posição:** JS move `.card-date` para o `.card-top` em runtime → `justify-content: space-between` coloca-o à direita: `01 · ● status · · · · · · · Abr 2026`
- **Datas usadas:** retiradas do `git log` de cada repositório local (dois sem repo local usam Abr 2026)
- **Vocaliz:** actualizado para Jun 2026 (2026-06-18)

### Contacto
- **Email picker** em todos os botões "Fale connosco" do site (nav, hero, CTA card, secção contacto, cada card, modelos de colaboração)
- **Sem formulários externos** — usa Gmail e Outlook web directamente
- **Email:** `nodeflow.pt@gmail.com`

### Verificação Humana (Human Gate)
- **Ficheiro:** `index.html` (Nodeflow) — overlay full-screen antes do site carregar
- **Mecanismo:** `sessionStorage('nf-human')` — não repete na mesma sessão
- **3 desafios em sequência** (ordem mais difícil para IA primeiro):
  1. **C — Sequência de nós:** 4 nós no ecrã, 3 acendem em ordem aleatória, utilizador reproduz clicando. Auto-replay ao fim de 4s se inactivo. Botão "Repetir →" após erro com sequência nova.
  2. **A — Arrastar nó:** drag do ● até ao ○ com trail SVG animado. Reset se soltar fora.
  3. **B — Deslizar:** slide do thumb até ao fim do track. Reset se soltar a meio.
- **Progresso:** 3 dots no card acendem progressivamente
- **Zero dependências externas** — sem reCAPTCHA, hCaptcha, Cloudflare
- **Botão "Repetir →"** inserido via `hint.after(retryBtn)` — fora do `hg-area` (que tem `position:relative` com nós `position:absolute`). Não usar `area.appendChild` ou o botão sobrepõe os nós.
- **PT/EN bilingue:** botões PT/EN no topo do card (canto direito). Idioma detectado via `localStorage('nf-lang')` — mesma chave do switcher do site. Função global `hgSetLang(l)` e `hgT(pt, en)` antes do IIFE. Todos os textos (instruções, hints, botões, footer) respondem ao idioma em tempo real. `hgRefreshInstr` actualiza o `instr.innerHTML` sem reiniciar o desafio.

### Termos e Condições
- **Ficheiro fonte:** `termos-condicoes.md` — versão v2026-07-05, 12 artigos
- **Ecrã obrigatório (`termosGate`):** aparece após Human Gate, antes do site. Guarda aceitação em `localStorage('nf-terms')` — persiste entre sessões (aceite uma vez, não volta a aparecer). Não fecha com Escape nem clique fora — única saída é "Compreendo e aceito".
- **4 pontos no resumo:** Verificação obrigatória · Apoio à decisão · EU AI Act Art. 50 · Portfolio de protótipos (disclaimer de responsabilidade)
- **"Ver termos completos →":** abre modal secundário com termos condensados (7 secções, bilingue PT/EN). Ao fechar, volta ao termosGate — não permite entrar no site sem aceitar.
- **Link no footer:** "Termos" ao lado de "Privacidade" — abre modal de resumo voluntário (pode fechar livremente, aceitação já registada).
- **Mecanismo `fromGate`:** `termosFullOverlay.dataset.fromGate` — flag para saber se o modal completo foi aberto a partir do gate obrigatório ou do footer.
- **Header do modal completo:** título à esquerda; à direita — PT/EN + separador vertical `1px` + botão ✕ (não usar `position:absolute` no close — fica `position:static` dentro do flex).
- **Bypass por refresh corrigido:** verificação de `nf-terms` dentro de `DOMContentLoaded` — o elemento `termosGate` ainda não existe quando o script do Human Gate corre.
- **Inspiração UX:** PolicyModal do VisionAI+ (`c:/projetos/Visionai+/src/components/PolicyModal.tsx`)

### Secções do site
1. Hero (duas colunas: slogan/CTAs + painel métricas)
2. Stats (19 apps / 12 com IA / 7 só automação / 5 sectores)
3. Portfolio (19 cards + CTA card verde)
4. Como trabalhamos (Diagnóstico → Construção → Entrega)
5. Modelos de colaboração (MVP Rápido · Projecto à Medida · White-label)
6. Sobre a Nodeflow (texto + 4 pillars: Execução real, IA integrada, Privacidade & Segurança, Código limpo)
7. Contacto
8. Footer (com link "Privacidade" → modal)

---

## Ficheiros nesta pasta

| Ficheiro/Pasta | Descrição |
|---|---|
| `index.html` | Site completo — HTML + CSS + JS single-file |
| `fonts/` | Fontes woff2 self-hosted (DM Mono + Fraunces) + `fonts.css` |
| `favicon.svg` | Logótipo Nodeflow (grid 2×2) como favicon — corrige ícone mobile |
| `CLAUDE.md` | Este ficheiro — contexto completo para o Claude Code |
| `diagrams.md` | Diagramas Mermaid do projecto (portfolio, processo, arquitectura, roadmap) |
| `.gitignore` | Exclui `Ideias/` e `Nota Despesa Nodeflow/` (ficheiros locais, não publicar) |

---

## Roadmap

### Fase 1 · Concluída
- [x] Secção "Como trabalhamos"
- [x] Cards com formato Desafio → Resultado
- [x] Email picker contextual em todos os CTAs
- [x] Secção de modelos de colaboração
- [x] Self-host Google Fonts (GDPR)
- [x] Política de privacidade (modal no footer)
- [x] Aviso AI Act Art. 50 em muitas apps com IA — confirmado nas apps: Análise de Crédito, Logic Gate Trainer, Gestor de Quotas (barra no topo). A verificar nas apps: NeoOtto, OutOfBox, Alpha2026, Faturix. Apps SEM IA (não precisam): Notas de Despesa, Automagic Mail, Vocaliz, HealHour, English Adventure, Treino Ocular
- [x] Hero duas colunas com painel de métricas
- [x] Hierarquia visual no portfolio (strategic / featured)
- [x] Contraste WCAG AA nos textos secundários
- [x] Card 17 · AudiNote com modal RGPD-compliant e beta access form
- [x] Landing page AudiNote (`c:/projetos/Ouvinte/index.html`) publicada em GitHub Pages
- [x] Site PT/EN bilingue — switcher no nav e footer de ambos os sites
- [x] Favicon `favicon.svg` (grid 2×2 Nodeflow) — corrige ícone mobile (browser usava cache do HealHour)
- [x] Data de última actualização em todos os 17 cards — posicionada no `card-top` à direita (JS move `.card-date` para o `.card-top` em runtime; `justify-content: space-between` alinha à direita)
- [x] Card 18 · LipRead (em desenvolvimento) — botão âmbar "Em breve →"
- [x] Card 19 · Faturix (strategic) — landing page em `https://nankov-ai.github.io/Agente-local/`
- [x] Card 07 substituído — Automagic Mail com rastreio UTM, Google Sheets, Flask portal; landing page em `https://nankov-ai.github.io/Envio-de-emails-com-registo/`
- [x] Stats actualizados para 19 apps · 12 com IA · 7 só automação · 5 sectores
- [x] Verificação humana (Human Gate) — 3 desafios sequenciais sem dependências externas (sequência de nós → arrastar → deslizar)
- [x] Human Gate PT/EN bilingue — botões PT/EN dentro do card, textos de todos os desafios e hints traduzidos; sincronizado com `localStorage('nf-lang')`
- [x] Cards expansíveis — tagline sempre visível, "Para quem" + stack tags + contacto colapsados com "Ver mais ↓"
- [x] Expansão sincronizada por linha — clicar "Ver mais" expande todos os cards da mesma linha (desktop); independente em mobile
- [x] "Para quem:" em Signal green em todos os cards
- [x] Voz Afiada — status "Gemini Gem · Em testes" + caixa de feedback "Já testaste?" com email picker
- [x] Reordenação do portfolio por impacto empresarial decrescente (IA primeiro, automação depois)
- [x] AudiNote incluído na estrutura expansível "Ver mais ↓" (igual aos outros cards)
- [x] H1 hero aumentado no mobile (≤480px): `3.4rem` (era `2.6rem`)
- [x] Contadores animados na secção stats — IntersectionObserver, easing cúbico, 1200ms
- [x] OG image (`og-image.png`) e meta tags Open Graph/Twitter Card — preview rico no LinkedIn
- [x] Cloudflare Web Analytics — cookie-free, GDPR-compliant, gratuito
- [x] Domínio próprio `nodeflow.pt` — registado PTisp, DNS configurado, HTTPS activo via GitHub Pages

### Fase 2 · Em aberto
- [ ] Gráficos dinâmicos — crescimento de apps ao longo do tempo (stand-by — complexidade backend)
- [x] T&C implementados — ecrã obrigatório entre Human Gate e site (`termosGate`), modal de resumo com 4 pontos + modal de termos completos. Link "Termos" no footer para consulta posterior.
- [ ] Verificar e adicionar aviso AI Act nas apps que ainda não têm: NeoOtto, OutOfBox, Alpha2026, Faturix
- [ ] Decidir se os cards do portfolio mostram etiqueta `🤖 IA` para apps com IA generativa
- [ ] `.gitignore` — `Termos e Condições IA.pdf` está na pasta local mas não commitado (correcto — ficheiro interno)

### Fase 3 · Futuro
- [ ] Dashboard de leads (lead → proposta → cliente)
- [ ] Login + demos privadas para clientes específicos
- [ ] Painel de métricas interno

### Fase 4 · Novo produto
- [ ] Agente de marketing/folhetos para retalho
- [ ] Voz Afiada — produto standalone com waitlist (quando lançar)

---

## Skills relevantes para este projecto

| Skill | Quando usar |
|---|---|
| `nando-global` | Activar no início de cada sessão — QA Rules P1/P2/P3 (aplicar só em decisões com peso, não em ajustes triviais) |
| `termos-condicoes-pt` | Actualizar ou expandir os T&C do site |
| `aiact` | Verificar compliance AI Act em apps com IA |
| `faturix` | Trabalhar no projecto Faturix (card 01) |
| `b2b-outbound-automation` | Quando escalar prospecção de clientes B2B |
| `agent-prompt-builder` | Melhorar system prompts da Voz Afiada, NeoOtto e outros agentes |
| `stop-slop` | Rever copy do site — remove padrões de escrita IA (travessões, advérbios, estruturas formulaicas) |

**Repositório das skills:** `https://github.com/Nankov-ai/anthropics-skills`  
**Localização local:** `C:\Users\Utilizador\.claude\skills\`  
**Nota:** skills locais não têm git remote — sincronizar manualmente com o repositório GitHub se necessário.

---

## Como trabalhar comigo

- Fala comigo em **português de Portugal**
- Quando tiveres dúvidas sobre decisões de produto ou marca, pergunta — não assumas
- Prefiro código limpo e bem estruturado a código rápido e sujo
- Commita com mensagens claras em inglês (convenção: `feat:`, `fix:`, `refactor:`, `docs:`, `copy:`)
- Não adicionar features não pedidas, não criar ficheiros desnecessários
- Actualiza este ficheiro sempre que houver mudanças relevantes no projecto
