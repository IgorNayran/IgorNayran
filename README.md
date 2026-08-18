<div align="center">

<img src="assets/cosmic-hero-v2.svg" width="100%" alt="Igor Nayran — Software Developer & Builder" />

<br/>

**Sistemas comerciais • ERP • PDV • Mobile • APIs • Fiscal • Automação**  
*Business software • ERP • POS • Mobile • APIs • Fiscal • Automation*

<br/>

![Delphi](https://img.shields.io/badge/Delphi-E62431?style=flat-square&logo=delphi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Firebird](https://img.shields.io/badge/Firebird-EF3B2D?style=flat-square&logo=firebird&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br/>

[![Game](https://img.shields.io/badge/TERMINAL_GAME-111827?style=for-the-badge&logo=gnometerminal&logoColor=67e8f9)](#terminal-access-game)
[![Projects](https://img.shields.io/badge/PROJECTS-111827?style=for-the-badge&logo=github&logoColor=67e8f9)](#projetos-em-destaque--featured-projects)
[![Tech](https://img.shields.io/badge/TECH_GALAXY-111827?style=for-the-badge&logo=stackshare&logoColor=67e8f9)](#tech-galaxy)
[![Focus](https://img.shields.io/badge/ENGINEERING_FOCUS-111827?style=for-the-badge&logo=target&logoColor=a78bfa)](#engineering-focus)
[![Activity](https://img.shields.io/badge/ACTIVITY-111827?style=for-the-badge&logo=githubactions&logoColor=67e8f9)](#atividade--activity)

</div>

<img src="assets/section-divider.svg" width="100%" alt="section divider" />

## Sobre mim / About me

Desenvolvedor focado em **software que resolve problemas reais de operação** — sistemas comerciais, PDV, ERP, mobile, integrações, APIs, automação e rotinas fiscais.

*Developer focused on software that solves real operational problems — business systems, POS, ERP, mobile, integrations, APIs, automation and fiscal workflows.*

<img src="assets/pillars.svg" width="100%" alt="Build Connect Operate" />

<details>
<summary><strong>✦ Como eu penso produto / How I approach product engineering</strong></summary>
<br/>

- **Build:** transformar necessidade operacional em software utilizável no dia a dia.
- **Connect:** integrar desktop, mobile, APIs, pagamentos, fiscal e dispositivos.
- **Operate:** pensar também em banco, deploy, segurança, logs e continuidade operacional.

*I focus on the whole product path: building the application, connecting systems and keeping the solution reliable in real operation.*

</details>

<img src="assets/section-divider.svg" width="100%" alt="section divider" />

## Terminal Access Game

<div align="center">
<img src="assets/terminal-game.svg" width="100%" alt="Terminal Access Game" />
</div>

> **Missão:** atravesse três nós do sistema e libere o acesso.  
> *Mission: solve three system nodes and unlock access.*

<details open>
<summary><strong>▶ START GAME // iniciar desafio</strong></summary>
<br/>

### NODE 01 — API GATEWAY

O cliente envia a mesma requisição de pagamento duas vezes por falha de rede. Qual estratégia evita cobrança duplicada?

<details>
<summary><code>[ A ] Confiar apenas no timestamp do cliente</code></summary>
<br/>

**ACCESS DENIED.** O relógio do cliente não garante unicidade nem processamento único.

`status: FAIL` · tente outra rota.

</details>

<details>
<summary><code>[ B ] Usar uma chave de idempotência persistida no backend</code></summary>
<br/>

**NODE 01 UNLOCKED.** A mesma operação pode ser reconhecida e reaproveitada sem executar novamente.

`status: PASS` · prossiga para o Node 02 abaixo.

### NODE 02 — DATABASE CORE

Você precisa garantir que dados de duas empresas nunca sejam misturados em consultas de uma API multiempresa. Qual abordagem é mais segura?

<details>
<summary><code>[ A ] Receber companyId livremente do frontend e confiar nele</code></summary>
<br/>

**ACCESS DENIED.** Identificadores enviados pelo cliente precisam ser validados contra a identidade autenticada.

</details>

<details>
<summary><code>[ B ] Derivar o tenant da sessão/token e aplicar o filtro também no backend</code></summary>
<br/>

**NODE 02 UNLOCKED.** O isolamento passa a fazer parte da autorização, não apenas da interface.

`status: PASS` · último nó liberado.

### NODE 03 — FISCAL CORE

Um serviço recebe XML fiscal, gera relatórios e permite download posterior. O que deve permanecer fora de logs públicos?

<details>
<summary><code>[ A ] Tokens, credenciais, dados de clientes e conteúdo fiscal sensível</code></summary>
<br/>

## ACCESS GRANTED

```text
NODE-01  API GATEWAY       [PASS]
NODE-02  DATABASE CORE     [PASS]
NODE-03  FISCAL CORE       [PASS]

IDENTITY: SOFTWARE BUILDER
CLEARANCE: REAL-WORLD SYSTEMS
STATUS: ACCESS GRANTED
```

Você chegou ao núcleo. Agora explore os projetos abaixo.

*You reached the core. Continue through the projects below.*

</details>

<details>
<summary><code>[ B ] Tudo, desde que o servidor esteja em produção</code></summary>
<br/>

**ACCESS DENIED.** Produção não transforma informação sensível em informação segura para log.

</details>

</details>

<details>
<summary><code>[ C ] Repetir a operação e corrigir manualmente depois</code></summary>
<br/>

**ACCESS DENIED.** Sistemas de pagamento precisam evitar duplicidade antes de criar inconsistência financeira.

</details>

</details>

</details>

<img src="assets/section-divider.svg" width="100%" alt="section divider" />

## Projetos em destaque / Featured projects

<div align="center">
<a href="https://github.com/IgorNayran/MenuFaz-Showcase"><img src="assets/cards/menufaz.svg" width="49%" alt="MenuFaz" /></a>
<a href="https://github.com/IgorNayran/FichaMovel-Showcase"><img src="assets/cards/fichamovel.svg" width="49%" alt="FichaMovel" /></a>
<br/>
<a href="https://github.com/IgorNayran/BarberShop-Showcase"><img src="assets/cards/barbershop.svg" width="49%" alt="BarberShop" /></a>
<a href="https://github.com/IgorNayran/RastreadorNotas-Showcase"><img src="assets/cards/rastreadornotas.svg" width="49%" alt="RastreadorNotas" /></a>
<br/>
<a href="https://github.com/IgorNayran/ConferirArquivo-Showcase"><img src="assets/cards/conferirarquivo.svg" width="49%" alt="ConferirArquivo" /></a>
</div>

> Os códigos-fonte principais permanecem privados. Os cards acima levam às vitrines públicas dos projetos.  
> *The main source repositories remain private. The cards above open the public project showcases.*

<details>
<summary><strong>🚀 MenuFaz — food service, POS & operations</strong></summary>
<br/>
Plataforma comercial para delivery, balcão, mesas, comandas, financeiro, relatórios, estoque, impressão e dispositivos.

`React` · `Vite` · `JavaScript` · `Node.js` · `Express` · `PostgreSQL` · `Docker` · `Caddy`

[→ Abrir showcase / Open showcase](https://github.com/IgorNayran/MenuFaz-Showcase)
</details>

<details>
<summary><strong>📱 FichaMovel — Android POS & device integration</strong></summary>
<br/>
Aplicativo Android/POS com pagamentos Stone, impressão SUNMI, bridge nativa Kotlin, persistência local e integração com o ecossistema MenuFaz.

`Flutter` · `Dart` · `Android` · `Kotlin` · `Hive` · `AIDL`

[→ Abrir showcase / Open showcase](https://github.com/IgorNayran/FichaMovel-Showcase)
</details>

<details>
<summary><strong>✂️ BarberShop — web/PWA business platform</strong></summary>
<br/>
Plataforma de agendamentos, clientes, pagamentos, assinaturas e gestão operacional, preparada para web e mobile.

`Next.js` · `React` · `TypeScript` · `Tailwind CSS` · `PostgreSQL` · `Prisma` · `NextAuth`

[→ Abrir showcase / Open showcase](https://github.com/IgorNayran/BarberShop-Showcase)
</details>

<details>
<summary><strong>🧾 RastreadorNotas — fiscal desktop engineering</strong></summary>
<br/>
Aplicação desktop fiscal para NF-e, CT-e, XML, estoque, custos e rotinas comerciais com ecossistema ACBr.

`Delphi` · `Object Pascal` · `VCL` · `FireDAC` · `Firebird` · `ACBr`

[→ Abrir showcase / Open showcase](https://github.com/IgorNayran/RastreadorNotas-Showcase)
</details>

<details>
<summary><strong>🛰️ ConferirArquivo — fiscal sync & accounting automation</strong></summary>
<br/>
Sincronização de documentos fiscais, automação contábil, relatórios, downloads e integração entre agentes desktop e serviços centralizados.

`Delphi` · `Go` · `chi` · `pgx` · `PostgreSQL` · `REST API`

[→ Abrir showcase / Open showcase](https://github.com/IgorNayran/ConferirArquivo-Showcase)
</details>

<img src="assets/section-divider.svg" width="100%" alt="section divider" />

## Tech Galaxy

<div align="center">
<img src="assets/tech-constellation.svg" width="100%" alt="Technology constellation" />
</div>

<details open>
<summary><strong>🖥️ Aplicações / Applications</strong></summary>
<br/>

![Delphi](https://img.shields.io/badge/Delphi-E62431?style=for-the-badge&logo=delphi&logoColor=white)
![Object Pascal](https://img.shields.io/badge/Object_Pascal-3776AB?style=for-the-badge)
![VCL](https://img.shields.io/badge/VCL-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)
</details>

<details>
<summary><strong>⚙️ Backend, dados e infraestrutura / Backend, data & infrastructure</strong></summary>
<br/>

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebird](https://img.shields.io/badge/Firebird-EF3B2D?style=for-the-badge&logo=firebird&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=for-the-badge&logo=auth0&logoColor=white)
![FireDAC](https://img.shields.io/badge/FireDAC-Data_Access-1565C0?style=for-the-badge)
![dbExpress](https://img.shields.io/badge/dbExpress-Legacy_Data_Access-475569?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
</details>

<details>
<summary><strong>🧩 Fiscal, pagamentos e integrações / Fiscal, payments & integrations</strong></summary>
<br/>

![ACBr](https://img.shields.io/badge/ACBr-Fiscal-2E7D32?style=for-the-badge)
![NF-e](https://img.shields.io/badge/NF--e-Modelo_55-2E7D32?style=for-the-badge)
![NFC-e](https://img.shields.io/badge/NFC--e-Modelo_65-388E3C?style=for-the-badge)
![CT-e](https://img.shields.io/badge/CT--e-Fiscal-1565C0?style=for-the-badge)
![XML](https://img.shields.io/badge/XML-Documentos-C2410C?style=for-the-badge)
![REST API](https://img.shields.io/badge/REST-API-005571?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![SMTP](https://img.shields.io/badge/SMTP-Email-6D4C41?style=for-the-badge)
![Stone](https://img.shields.io/badge/Stone-Payments-00A868?style=for-the-badge)
![SUNMI](https://img.shields.io/badge/SUNMI-Printing-FF6A00?style=for-the-badge)
![Mercado Pago](https://img.shields.io/badge/Mercado_Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)
</details>

<img src="assets/section-divider.svg" width="100%" alt="section divider" />

## Engineering Focus

<img src="assets/engineering-focus.svg" width="100%" alt="Engineering focus" />

<details open>
<summary><strong>🧠 O que eu costumo resolver / What I usually solve</strong></summary>
<br/>

**Produto:** ERP, POS, mobile, PWA, relatórios e fluxos operacionais.  
**Integração:** REST APIs, pagamentos, fiscal brasileiro, XML, hardware Android e autenticação.  
**Entrega:** Docker, Linux, Caddy, Git, deploy, logs, observabilidade e automação.

*Product engineering, integrations and production delivery — from desktop and mobile clients to APIs, databases and deployment.*
</details>

<img src="assets/section-divider.svg" width="100%" alt="section divider" />

## Atividade / Activity

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/IgorNayran/IgorNayran/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/IgorNayran/IgorNayran/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution animation" src="https://raw.githubusercontent.com/IgorNayran/IgorNayran/output/github-contribution-grid-snake.svg" />
</picture>
</div>

<details>
<summary><strong>✦ Sobre esta animação / About this animation</strong></summary>
<br/>
A animação usa o gráfico público de contribuições do GitHub e é regenerada automaticamente pelo próprio repositório de perfil.

*The animation is generated from the public GitHub contribution grid and refreshed automatically by this profile repository.*
</details>

<img src="assets/section-divider.svg" width="100%" alt="section divider" />

<div align="center">

### Áreas de atuação / Focus areas

`ERP` · `PDV / POS` · `Sistemas comerciais` · `Mobile` · `REST APIs` · `Integrações` · `Automação` · `Fiscal` · `Pagamentos` · `Relatórios` · `Deploy`

<br/>

<img src="assets/cosmic-footer.svg" width="100%" alt="Building software for real-world operations" />

</div>
