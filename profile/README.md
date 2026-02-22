# venantvr.web

Projets web, extensions VS Code, qualité CSS, analytics et portfolios — sous la marque **Hack Your Domain**.

## Repos

### Sites et portfolios

**`Html.Portfolio`** <sup>privé</sup>
*HTML / Bootstrap* — Portfolio statique PWA : service worker, données structurées Schema.org (JSON-LD), microdata, design responsive.

**`VueJS.Portfolio`** <sup>privé</sup>
*Vue 2 / Bootstrap* — Portfolio SPA avec Vue.js : composants réactifs, PWA, contenu enrichi Schema.org.

**`NodeJS.Portfolio`** <sup>privé</sup>
*Vue 3 / Node* — Portfolio full-stack : Vue 3 + Vue Router, backend Node.js, diagrammes Mermaid intégrés, PWA.

### Qualité web et SEO

**`NodeJS.CSS.Extractor`** <sup>public</sup>
*Node / Express* — Extracteur de CSS critique : Puppeteer pour le rendering headless, clean-css pour la minification, API REST Express, tests Jest + Supertest.

**`NodeJS.CSS.Refactoring`** <sup>public</sup>
*TypeScript / Playwright* — Plateforme d'intelligence CSS : audit multi-pages avec scoring de confiance, détection de régressions visuelles, CLI `css-audit`, Playwright pour le crawl, Vitest pour les tests.

**`vuejs.lighthouse.llm`** <sup>public</sup>
*Vue 3 / Tailwind* — Dashboard d'analyse Lighthouse augmentée par LLM : scoring détaillé, graphiques Chart.js, export PDF (jsPDF + html2canvas), serveur Node.js backend, store Pinia.

**`Python.Google.Analytics`** <sup>privé</sup>
*Python* — Pipeline d'audit GA4 complet : extraction API Google Analytics, stockage, audit automatisé avec alertes par sévérité, rapports visuels, analyse optionnelle Gemini, import de logs Apache.

### Outillage développeur

**`vuejs.github.llm`** <sup>privé</sup>
*Vue / Vite* — Outils de prompts GitHub + LLM : génération et gestion de prompts structurés, tests Vitest.

**`vuejs.phpstan.gui`** <sup>privé</sup>
*Vue 3 / Tailwind* — Interface graphique web pour PHPStan : visualisation des erreurs d'analyse statique PHP, navigation par fichier et sévérité.

**`vuejs.holon`** <sup>public</sup>
*Vue 3 / TypeScript* — Modélisateur d'architectures holoniques : canvas infini, nesting illimité de composants, persistance IndexedDB (Dexie), store Pinia.

**`typescript-vscode-interface`** <sup>public</sup>
*TypeScript / VS Code API* — Extension VS Code de pilotage par WebSocket : déclenchement de tests, gestion de fichiers, listing de projets, port et tâches configurables.

**`typescript-vscode-paster`** <sup>public</sup>
*TypeScript / VS Code API* — Extension VS Code de collage intelligent : parse de snippets multi-fichiers générés par un LLM, création automatique des fichiers correspondants.

### Messaging

**`nodejs.telegram.aggregator`** <sup>privé</sup>
*Node / TDLib* — Agrégateur de messages Telegram : client TDLib, filtrage par règles YAML, serveur WebSocket temps réel, gestion de sessions.

## Stack

- **Vue.js 3** + **TypeScript** + **Tailwind CSS** pour les frontends
- **Node.js** + **Express** pour les backends et outils CLI
- **Python** pour l'analytics (GA4, Gemini)
- **Playwright** / **Puppeteer** pour le crawl et l'audit CSS
- **Cloudflare Workers** pour le déploiement edge
- **Vite** + **Vitest** pour le build et les tests
