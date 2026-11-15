# Skills de Claura

Las skills que usamos en [Claura](https://claura-ai.com) con nuestros clientes, publicadas para que las uses en tu agente de IA (Claude Code, Claude, Cursor, Codex o Gemini CLI). No son demos: son las mismas que corren en nuestro trabajo diario, sin las partes que dependen de nuestras herramientas internas.

| Skill | Para qué sirve |
|---|---|
| [`web-seo-checklist`](skills/web-seo-checklist/SKILL.md) | Control de SEO, AEO y GEO punto por punto (107 puntos) antes de lanzar o al tocar una web: metadata, imagen para compartir, JSON-LD, sitemap, blog, analítica, Core Web Vitals y contenido citable por ChatGPT, Perplexity y Google AI Overviews. [Ficha y ejemplos](https://claura-ai.com/skills/web-seo-checklist-control-de-seo-para-webs). |

Vamos sumando una por vez.

## Cómo instalarlas

**Claude Code**, como plugin:

```
/plugin marketplace add Claura-LLC/skills
/plugin install claura-marketing@claura-skills
```

**Claude Code**, a mano: copiá la carpeta de la skill a `.claude/skills/` de tu proyecto o a `~/.claude/skills/`.

**Claude (app)**: comprimí la carpeta de la skill en un ZIP y subila desde Customize, Skills, «Upload a skill».

**Cursor, Codex o Gemini CLI**: copiá el `SKILL.md` a la carpeta de reglas o skills de tu agente, o referencialo desde tu archivo de instrucciones.

Después pedile a tu agente, por ejemplo: «corré el web-seo-checklist sobre esta web».

## Con el MCP de Claura

Todas funcionan solas. Si además conectás Claude, ChatGPT o Claude Code a tu cuenta de Claura con el
[MCP de Claura](https://claura-ai.com/mcp), la skill trabaja con los datos reales de tu marca: tu Search Console, tu
analítica, tu web publicada y lo que las IAs dicen de vos, sin que tengas que pegarlos a mano.

## Licencia

MIT. Usalas, cambialas y compartilas. Si te sirven, contalo.

---

Hechas por [Claura](https://claura-ai.com), agencia de marketing con IA. Directorio completo de skills de marketing, propias y de la comunidad: [claura-ai.com/skills](https://claura-ai.com/skills).
