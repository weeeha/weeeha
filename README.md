# Nick Vyhouski

**Product designer who ships production code and builds the systems other designers ship with.** 14+ years across complex B2B software: AI products, data-heavy dashboards, design systems as production infrastructure.

[vyhouski.com](https://vyhouski.com) · [LinkedIn](https://linkedin.com/in/nick-vyhouski) · mvyhouski@gmail.com · Montreal 🇨🇦

**Now:**

- **Pegbo** - Design system and product UI for a pre-construction CRM. 111 components on a three-tier token architecture (shadcn/Radix/Base UI primitives, Pegbo composites, a 22-component AI tier), the prototyping repo the team explores screen directions in, and a bid-coverage workspace that shows package risk on the 3D building model, so a package short of bidders lights up where it sits.
- **[Ten8](https://ten8.ai)** - Founding Designer. AI coworker orchestration for logistics. Shipped the production design system: 112 components across 17 surfaces on a 271-token semantic system ([Storybook](https://ten8-component-library.vercel.app)), with Storybook running as an MCP server so AI tooling generates on-system.
- **[PermitNav](https://permitnav.ca)** - Senior Product Designer (AI & design systems). AI building-permit copilot for Metro Vancouver. Design specs, prototypes and production UI, all shipped through an agentic Claude Code workflow against the product repos.

### Design systems that enforce their own rules

The Pegbo library above, a 95-component personal library, and a governance kit, built on one idea: a rule that matters is a check that runs.

- **Contrast is a unit test.** Every status foreground is measured against the fill it actually sits on, and the build fails below 4.5:1.
- **Every component ships a machine-readable contract.** When to use it, what to reach for instead, and its keyboard behaviour, with one index routing over all 111. Give an agent that and it picks the right component instead of inventing props.
- **Governance as a conformance ladder.** Ten staged specs, three built so far, each built stage paired with a probe that runs against a target repo. A rule and its detector are one record, so they cannot drift apart, and a check that could not run is reported separately from one that failed.
- **Gates on the ordinary things.** Axe on every story in light and dark, because the worst contrast in the system was a dark-mode value a light-only run never sees. Spacing, radius and type scales checked in CI. A post-edit hook that hands an agent the token violations on the lines it just changed.

Also in the set: a governed corpus of iOS competitive audits that fails its own build when a claim drifts from the screenshot it cites, and a runnable app shell where how you browse and how records open are two independent, persisted choices. Private repos, happy to walk through any of it.

### AI-enabled design workflows

Tools that change how design teams work, not just what they ship.

- **[Super-Design-Skills](https://github.com/weeeha/Super-Design-Skills)** - designer skills for Claude Code: brainstorming, critique, design QA, spec writing, handoff
- **[Super-Design-Lead](https://github.com/weeeha/Super-Design-Lead)** - design-leadership methodology plugin for design managers
- A personal plugin of 28 workflow skills that runs the rest of the practice: company research, application drafting, interview debriefs, ship-and-deploy, fleet deploys, and a model-fit check that keeps the expensive model on the work that needs it
- Design-adjacent automations built around a real token migration: two-way Figma-variables ↔ code-tokens sync, token-table generation, automated rebinding of Figma node trees between token systems
- Run a ~15-designer community with biweekly sessions on AI tooling and best practices

### Agent-driven experiences

Designing for AI-native surfaces by building them.

- **[AgentCommandHQ](https://github.com/weeeha/AgentCommandHQ)** - command dashboard for an AI agent squad: Kanban, multi-thread chat, observability ([demo](https://agent-command-hq.vercel.app))
- **[agent-rpg](https://github.com/weeeha/agent-rpg)** - the same agent-squad problem, explored as a cyberpunk command HQ ([demo](https://agent-rpg.vercel.app))
- **[AI-Orb](https://github.com/weeeha/AI-Orb)** - audio-reactive orb for AI voice interfaces: the visual presence of an agent that is idle, listening, thinking or speaking. One WebGL fragment program, five finishes, zero runtime dependencies, with a written style guide for the orb as a design language
- **[lifeos-specs](https://github.com/weeeha/lifeos-specs)** - specs for LifeOS, a personal operating system: declarative flows with a completion gate, one sanctioned write path for state, and a local vector index plus knowledge graph as memory. Native iOS client on top, engine local-first with no metered API for the heavy lifting
- **[VisionClaw](https://github.com/weeeha/VisionClaw)** - real-time AI assistant for Meta Ray-Ban smart glasses: voice + vision, Gemini Live
- **[MyMuseumGuide](https://github.com/weeeha/MyMuseumGuide)** - point a phone at an artifact and get it identified, narrated, and read aloud. Vision to streamed narrative to speech, with per-museum theming and a guided tour flow

### Film, and other craft

- **[FilmMaker](https://github.com/weeeha/FilmMaker)** - paste a screenplay, get scenes and shots, and a generated reference image per shot, with style notes that propagate across the board. The storyboard loop is built; the wider studio (flow builder, music and voice libraries, cost visible per step) is specced
- **[Film Design System](https://github.com/weeeha/Image-Generation-Pipeline-)** - a local-first app that manages a film's visual world the way a design system manages a product UI. Characters, props and settings each own a canon of reference images; good outputs get promoted back into it, so a character looks like the same character across hundreds of generations
- **[Video-Generation-Pipeline](https://github.com/weeeha/Video-Generation-Pipeline)** - Seedance 2.5 client with reference packs that hold a person, a place or a motion steady across separate generations, plus the prompt and API knowledge that makes a first attempt land. Grown out of a brand-film pipeline that shipped
- **[SuperClock](https://github.com/weeeha/SuperClock)** - a design system for a display that isn't a rectangle. 14 mini-apps on a 1080×1080 circular LCD, running as a four-device Raspberry Pi fleet over Tailscale, with an in-repo docs site and a written platform spec so new apps land on-system. This summer: a calendar built as a four-level zoom ladder (cover, week, month, year) with swipe navigation, and a radar sidecar so the display responds to presence
- **[tailtop](https://github.com/weeeha/tailtop)** - *htop for your tailnet.* A terminal UI that reads the `tailscaled` daemon already running on your machine. Installs nothing, needs no root

---

*Before this: Sprig (Platform & AI), Pendo, InRule, founding designer at Acies.ai, co-founder of MeetnGreetMe (World Summit Award, 2016). 21 case studies at [vyhouski.com/work](https://vyhouski.com/work).*
