<h1>
  <img src="https://emojis.slackmojis.com/emojis/images/1680554188/65018/cat-roomba-exceptionally-fast.gif?1680554188" width="30"/>
  Olá, eu sou o Luan
  <img src="https://media.tenor.com/J6xeNjc2CfMAAAAi/duck-dancing-transparent-duck.gif" width="55"/>
</h1>

[![typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=900&color=F0713F&vCenter=true&width=640&lines=backend+em+Node.js+%2F+TypeScript+%2F+NestJS;desktop+nativo+em+C%23+%2F+.NET+8+%2F+WinUI+3;e+um+n%C3%BAcleo+em+Rust+quando+precisa+ser+r%C3%A1pido)](https://github.com/lbss9)

Desenvolvedor backend. Passo a maior parte do tempo em **Node.js e TypeScript** (NestJS, Fastify, filas, Postgres),
e a outra parte construindo **apps nativos para Windows em C#/.NET** e um pouco de **Rust** onde a performance manda.

Gosto de regra de negócio bagunçada virando sistema claro. De janela sem borda com acrílico. De ver o deploy passar
na primeira. Café do lado é opcional, mas recomendado.

```console
luan@lbss9:~$ neofetch

        ▄▄▄▄▄▄▄▄▄▄▄▄        luan@lbss9
      ▄██████████████▄      ------------------------------------
     ████  ██████  ████     OS         Windows 11
     ████  ██████  ████     Shell      pwsh · bash
     ██████████████████     Editor     VS Code
      ▀██████████████▀      Backend    Node.js · TypeScript · NestJS · Fastify
        ██  ▀▀▀▀  ██        Desktop    C# · .NET 8 · WinUI 3 · Windows App SDK
        ██        ██        Systems    Rust · Tauri · UniFFI
       ▄██▄      ▄██▄       Data       PostgreSQL · SQLite · MongoDB · Redis
                            Infra      Docker · GitHub Actions · AWS · Nginx
                            Uptime     no GitHub desde 2022
                            Locale     pt_BR.UTF-8 · en_US
```

## O que estou construindo

<table>
<tr>
<td colspan="2" valign="top">

### 🐈 [PostCat](https://github.com/lbss9/postcat)

Cliente de API para desktop, **leve e local-first**: sem conta, sem nuvem, coleções e histórico ficam na sua máquina.
Motor HTTP em **Rust** (reqwest + rustls), casca em **Tauri 2**, interface em **React + TypeScript**.

- Construtor completo: query e path params, headers, form-data, urlencoded, raw (JSON/JS/HTML/XML) e binário
- Coleções, pastas, ambientes com `{{variáveis}}` viradas em chips clicáveis
- Scripts pré e pós-envio num sandbox isolado (Web Worker) com API própria `pc.*` e testes no painel de resposta
- Importa Collection v2.1 e OpenAPI/Swagger, exporta de volta
- Motor de temas em JSON com hot reload, janela sem decoração, menus de contexto próprios, en + pt-BR

![Tauri](https://img.shields.io/badge/Tauri_2-24C8D8?style=flat-square&logo=tauri&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
[![last commit](https://img.shields.io/github/last-commit/lbss9/postcat?style=flat-square&color=F0713F&label=last%20commit)](https://github.com/lbss9/postcat/commits/main)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 [Lumenhop](https://github.com/lbss9/lumenhop)

Monitor de ping silencioso para Windows. Um flyout acrílico no canto da tela mostra, num relance, se o que importa está no ar.

- WinUI 3 + .NET 8, self-contained
- ICMP contínuo por alvo, cores por latência
- Bandeja do sistema, auto-update via Velopack
- pt-BR e inglês · Windows 10/11

[![release](https://img.shields.io/github/v/release/lbss9/lumenhop?style=flat-square&color=2EE6C7&label=release)](https://github.com/lbss9/lumenhop/releases/latest)

</td>
<td width="50%" valign="top">

### 📺 [Beamcast](https://github.com/lbss9/Beamcast)

Salas de compartilhamento de tela self-hosted e cifradas de ponta a ponta. Projeto de estudo sobre captura, codecs e transmissão em tempo real.

- WinUI 3 + .NET 8; host em ASP.NET Core (Docker)
- Captura na GPU, H.264/HEVC por hardware, áudio por processo
- AES-256-GCM: o host nunca vê o conteúdo
- Presets até 2160p/120fps, reconexão automática

[![release](https://img.shields.io/github/v/release/lbss9/Beamcast?style=flat-square&color=FF4D6D&label=release)](https://github.com/lbss9/Beamcast/releases/latest)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐙 [OctoWatch](https://github.com/lbss9/OctoWatch)

Feed de Actions, PRs, branches e commits dos seus repositórios, direto do desktop. Um único núcleo em Rust, uma interface nativa por sistema.

- Núcleo Rust (octocrab + tokio) com cache ETag
- Windows em WinUI 3, macOS em SwiftUI (menu bar), Linux em GTK4 planejado
- Bindings C# e Swift gerados via UniFFI
- Review e merge de PR sem abrir o navegador

![status](https://img.shields.io/badge/status-em%20desenvolvimento-F5A623?style=flat-square)

</td>
<td width="50%" valign="top">

### 🎮 [VirtualGameCard](https://github.com/lbss9/VirtualGameCard)

Backend em C#/.NET 10 para compra e entrega de gift cards digitais, com um microserviço de pagamento separado.

- ASP.NET Core, PostgreSQL, EF Core, OpenAPI
- JWT com refresh token rotativo em cookie `HttpOnly`
- Compra idempotente, webhook com HMAC, transações
- Pagamentos em AWS Lambda + SQS, deploy em Render + Neon

[demo](https://lbss9.github.io/VirtualGameCardFrontend/) · [frontend](https://github.com/lbss9/VirtualGameCardFrontend) · [payment service](https://github.com/lbss9/VirtualGameCardPaymentService)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💬 [ChatIn](https://github.com/lbss9/ChatIn)

Chat em tempo real full stack: autenticação completa, conversas diretas e grupos, perfil editável com badges e marcações.

- NestJS + MongoDB Atlas + Socket.IO
- Next.js estático no GitHub Pages, API no Render
- Refresh token, recuperação de senha, upload de assets

</td>
<td width="50%" valign="top">

### 🍔 Zap Food · 🪽 Angelus

Dois ecossistemas que uso pra exercitar arquitetura: um de delivery, outro de jogo.

- [Zap Food](https://github.com/lbss9/zap-food-restaurant-management-backend): admin de delivery em NestJS + MongoDB + RabbitMQ + Redis, com [webhook Stripe](https://github.com/lbss9/zap-food-stripe-payment-webhook-intent) separado e [dashboard em React](https://github.com/lbss9/zap-food-restaurant-management-front)
- [Angelus](https://github.com/lbss9/angelus-backend): backend de um MMORPG web 3D em .NET 10 com Clean Architecture, CQRS e SignalR, mais o [cliente em React](https://github.com/lbss9/AngelusFrontend)

</td>
</tr>
</table>

Também tem bastante coisa privada: ERPs, automações, bots de Discord e Minecraft, APIs com filas e workers. Nem tudo pode ser público, mas aparece na atividade.

## Ferramentas

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nodejs,ts,nestjs,express,cs,dotnet,rust,tauri,react,nextjs,postgres,mongodb,redis,docker,githubactions,aws,nginx,linux,windows&perline=10" alt="stack" />
  </a>
</p>

## Atividade

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lbss9/lbss9/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lbss9/lbss9/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/lbss9/lbss9/output/github-snake.svg" />
</picture>

<a href="https://github.com/lbss9">
  <img src="https://streak-stats.demolab.com?user=lbss9&theme=dark&hide_border=true&background=00000000&ring=F0713F&fire=F0713F&currStreakLabel=F0713F&locale=pt_BR&date_format=j%20M%5B%20Y%5D" alt="streak" />
</a>

## Onde me achar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luan-barbosa-a02015190/)
[![Email](https://img.shields.io/badge/luan.barbosa.dev%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luan.barbosa.dev@gmail.com)

<br/>

<p align="center">
  <img src="https://i.giphy.com/ln7z2eWriiQAllfVcn.webp" width="90">
  <img src="https://4.bp.blogspot.com/-bToewCkyym8/Wq6rLG2d6BI/AAAAAAAC8rg/1owMqD_Te3MEsspstepc-Q5iBW7wDjluQCLcBGAs/s1600/p26.gif" width="90">
</p>

<p align="center">
  <sub><i>"The only way to learn a new programming language is by writing programs in it."</i> — Dennis Ritchie</sub>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=lbss9&color=F0713F&style=flat-square&label=visitas" alt="visitas" />
</p>
