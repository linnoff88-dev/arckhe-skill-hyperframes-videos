ï»¿# ê°Å¸Å½Â¬ HyperFrames ê¢â¬â VêÂ­deos explicativos com Claude Code

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso completo, no formato **INEMA.CLUB**, sobre a Skill **`video-explicativo`**: como criar vêÂ­deos
explicativos narrados (HTML ê¢â â MP4) com o Claude Code e o framework [HyperFrames](https://github.com/heygen-com/hyperframes) ê¢â¬â
animados, em PT-BR, renderizados **localmente, sem chave de API**, nos formatos 16:9 (YouTube) e 9:16 (Shorts/Reels).

> Este curso nasceu de um vêÂ­deo que foi, ele mesmo, **feito por uma Skill**.

## ê°Å¸ÅÂ Acesse o curso

**https://inematds.github.io/skill-hyperframes-videos/**

## ê°Å¸âÅ¡ As 4 trilhas

| Trilha | Tema | O que cobre |
|--------|------|-------------|
| ê°Å¸Â§Â© **T1 ê¢â¬â Skills no Claude Code** | Fundamentos | O que êÂ© uma Skill, o `SKILL.md`, `name` + `description`, divulgaêÂ§êÂ£o progressiva, onde vivem |
| ê°Å¸Å½Â¬ **T2 ê¢â¬â Pipeline: HTML ê¢â â MP4** | PrêÂ¡tico | Setup, roteiro, narraêÂ§êÂ£o TTS (Kokoro), composiêÂ§êÂ£o em GSAP, lint/inspect, render 16:9 e 9:16 |
| ê°Å¸âÂ§ **T3 ê¢â¬â Por dentro do skill** | AvanêÂ§ado | Estrutura do skill, house style dark premium, o gerador `build-index.mjs`, gotchas de produêÂ§êÂ£o |
| ê°Å¸âÂ¡ **T4 ê¢â¬â AplicaêÂ§êÂµes & Prompts** | PrêÂ¡tico | YouTube, Shorts, onboarding, aulas, lanêÂ§amentos + biblioteca de prompts prontos |

## ê°Å¸âÂ¦ A Skill

A Skill `video-explicativo` estêÂ¡ incluêÂ­da neste repositêÂ³rio:

- Pasta navegêÂ¡vel: [`skill/video-explicativo/`](skill/video-explicativo/)
- Download: [`downloads/video-explicativo.zip`](downloads/video-explicativo.zip)

Instale copiando a pasta para `~/.claude/skills/` (global) ou `.claude/skills/` (projeto) e peêÂ§a um vêÂ­deo
ao Claude Code: *"faêÂ§a um vêÂ­deo explicativo sobre X, em 16:9 e 9:16, terminando com a CTA do INEMA.CLUB."*

### Stack
- **HyperFrames** (HTML ê¢â â MP4 via Chrome headless + FFmpeg)
- **Kokoro** (TTS local PT-BR, voz `pf_dora`, sem chave de API)
- **GSAP** (animaêÂ§êÂ£o das cenas)

## ê°Å¸ââê¯Â¸Â Estrutura do repositêÂ³rio

```
index.html                 # Landing
curso/
  index.html               # êÂndice das trilhas
  trilha1..4/
    index.html             # êÂndice da trilha (mapa + mêÂ³dulos)
    modulo-X-Y.html        # PêÂ¡ginas de mêÂ³dulo (16 no total)
skill/video-explicativo/   # A Skill, navegêÂ¡vel
downloads/                 # .zip da Skill
```

---

ConteêÂºdo do [**INEMA.CLUB**](https://inema.club) êÂ· 2026

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>