# Skills de Claura

Las skills que usamos en [Claura](https://claura-ai.com) con nuestros clientes, publicadas para que las uses en tu agente de IA (Claude Code, Claude, Cursor, Codex o Gemini CLI). No son demos: son las mismas que corren en nuestro trabajo diario, sin las partes que dependen de nuestras herramientas internas.

| Skill | Para qué sirve |
|---|---|
| [`web-seo-checklist`](skills/web-seo-checklist/SKILL.md) | Control de SEO, AEO y GEO punto por punto (107 puntos) antes de lanzar o al tocar una web: metadata, imagen para compartir, JSON-LD, sitemap, blog, analítica, Core Web Vitals y contenido citable por ChatGPT, Perplexity y Google AI Overviews. [Ficha y ejemplos](https://claura-ai.com/skills/web-seo-checklist-control-de-seo-para-webs). |

Vamos sumando una por vez.

## Por qué confiar en estas skills

- **Salen de trabajo real.** Cada punto del control existe porque algo se rompió en una web de verdad, y donde sirve el punto cuenta el caso.
- **No inventan datos.** Lo que falta (horarios, reseñas, precios) va a una lista de pedidos, nunca se rellena.
- **Se leen enteras antes de instalar.** `web-seo-checklist` es texto plano: no trae scripts ni pide claves. Si una skill futura trae un script, va en su carpeta a la vista.
- **Se mantienen.** Cuando cambia una regla de Google o de las IAs, actualizamos la skill aquí.

## Cómo instalarlas

**Cualquier agente** (Claude Code, Cursor, Codex, Gemini CLI y otros), con el instalador [skills](https://github.com/vercel-labs/skills). Con `-g` queda para todos tus proyectos:

```
npx skills add Claura-LLC/skills --skill web-seo-checklist -g
```

Te pregunta en qué agentes instalarla.

**Claude Code**, como plugin:

```
/plugin marketplace add Claura-LLC/skills
/plugin install claura-marketing@claura-skills
```

**A mano**: copia la carpeta de la skill a `~/.claude/skills/` (Claude Code) o a `~/.agents/skills/` (Cursor, Codex y Gemini CLI la leen). En Codex se llama con `$web-seo-checklist`.

**Claude (app)**: comprime la carpeta de la skill en un ZIP y súbela desde Customize, Skills, botón «+», «Create skill» y «Upload a skill». Necesita la ejecución de código prendida.

Después pídele a tu agente, por ejemplo: «corre el web-seo-checklist sobre esta web».

## Con el MCP de Claura

Todas funcionan solas. Si eres cliente de Claura y conectas Claude, ChatGPT o Claude Code a tu cuenta con el
[MCP de Claura](https://claura-ai.com/mcp), la skill trabaja con los datos reales de tu marca: tu Search Console, tu
analítica, tu web publicada y lo que las IAs dicen de ti, sin que tengas que pegarlos a mano.

## Licencia

MIT. Úsalas, cámbialas y compártelas. Si te sirven, cuéntalo.

---

Hechas por [Claura](https://claura-ai.com), agencia de marketing con IA. Directorio completo de skills de marketing, propias y de la comunidad: [claura-ai.com/skills](https://claura-ai.com/skills).
