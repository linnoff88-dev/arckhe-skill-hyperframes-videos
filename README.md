# ðŸŽ¬ HyperFrames â€” VÃ­deos explicativos com Claude Code

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso completo, no formato **INEMA.CLUB**, sobre a Skill **`video-explicativo`**: como criar vÃ­deos
explicativos narrados (HTML â†’ MP4) com o Claude Code e o framework [HyperFrames](https://github.com/heygen-com/hyperframes) â€”
animados, em PT-BR, renderizados **localmente, sem chave de API**, nos formatos 16:9 (YouTube) e 9:16 (Shorts/Reels).

> Este curso nasceu de um vÃ­deo que foi, ele mesmo, **feito por uma Skill**.

## ðŸŒ Acesse o curso

**https://inematds.github.io/skill-hyperframes-videos/**

## ðŸ“š As 4 trilhas

| Trilha | Tema | O que cobre |
|--------|------|-------------|
| ðŸ§© **T1 â€” Skills no Claude Code** | Fundamentos | O que Ã© uma Skill, o `SKILL.md`, `name` + `description`, divulgaÃ§Ã£o progressiva, onde vivem |
| ðŸŽ¬ **T2 â€” Pipeline: HTML â†’ MP4** | PrÃ¡tico | Setup, roteiro, narraÃ§Ã£o TTS (Kokoro), composiÃ§Ã£o em GSAP, lint/inspect, render 16:9 e 9:16 |
| ðŸ”§ **T3 â€” Por dentro do skill** | AvanÃ§ado | Estrutura do skill, house style dark premium, o gerador `build-index.mjs`, gotchas de produÃ§Ã£o |
| ðŸ’¡ **T4 â€” AplicaÃ§Ãµes & Prompts** | PrÃ¡tico | YouTube, Shorts, onboarding, aulas, lanÃ§amentos + biblioteca de prompts prontos |

## ðŸ“¦ A Skill

A Skill `video-explicativo` estÃ¡ incluÃ­da neste repositÃ³rio:

- Pasta navegÃ¡vel: [`skill/video-explicativo/`](skill/video-explicativo/)
- Download: [`downloads/video-explicativo.zip`](downloads/video-explicativo.zip)

Instale copiando a pasta para `~/.claude/skills/` (global) ou `.claude/skills/` (projeto) e peÃ§a um vÃ­deo
ao Claude Code: *"faÃ§a um vÃ­deo explicativo sobre X, em 16:9 e 9:16, terminando com a CTA do INEMA.CLUB."*

### Stack
- **HyperFrames** (HTML â†’ MP4 via Chrome headless + FFmpeg)
- **Kokoro** (TTS local PT-BR, voz `pf_dora`, sem chave de API)
- **GSAP** (animaÃ§Ã£o das cenas)

## ðŸ—‚ï¸ Estrutura do repositÃ³rio

```
index.html                 # Landing
curso/
  index.html               # Ãndice das trilhas
  trilha1..4/
    index.html             # Ãndice da trilha (mapa + mÃ³dulos)
    modulo-X-Y.html        # PÃ¡ginas de mÃ³dulo (16 no total)
skill/video-explicativo/   # A Skill, navegÃ¡vel
downloads/                 # .zip da Skill
```

---

ConteÃºdo do [**INEMA.CLUB**](https://inema.club) Â· 2026

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>