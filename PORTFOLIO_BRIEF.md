# Jason M. Ziegler Portfolio Brief

Status: homepage published; case studies in progress

Last updated: 2026-09-27

## Purpose

Build a clear, credible home for Jason's strongest current work so that a hiring manager, collaborator, or technical peer can understand what he builds, how he thinks, and where to see the work.

The portfolio should help Jason move toward work he cares about by emphasizing practical problem-solving, sustained project ownership, and the ability to use modern AI-assisted development responsibly.

## Primary audience

1. Hiring managers and technical interviewers evaluating Jason for product-minded software, automation, AI tooling, developer-tool, or game-development-adjacent roles.
2. Founders and small teams looking for someone who can turn ambiguous ideas into working tools.
3. Technical collaborators who want enough context to inspect a repository, watch a demonstration, or continue a project with an agent.

## Working positioning

> I explore how software can give people more agency over attention, participation, and value. I am drawn to ambitious systems, then make them real through small, testable steps.

This is the central portfolio thesis. It describes a recurring inquiry rather than claiming that the projects have already achieved broad social impact.

The shorter public expression is:

> I build toward bigger ideas, one real system at a time.

## Thesis evidence map

| Project | Larger question | Concrete evidence | Honest boundary |
|---|---|---|---|
| `Attention` | Can people deliberately direct attention instead of surrendering it to an engagement feed? | Account/authentication prototype and roadmap for one movable, reclaimable Span token plus top people/topics | Delegated attention flow and world visualization were planned, not implemented |
| `Larn-like` | Can participation remain valuable after a player character is gone? | Persistent-world architecture, consequential death, evolving monsters, death sites, and substantial tests | The original player economy remains a design horizon, not a proven live economy |
| `west.net` | Can attention fund creators and communities without advertising or invisible behavioral extraction? | Detailed MVP, full-vision PRD, micropayment research, and 21 adversarial system tests | Research and planning project; no public product has been validated |
| `DoneQuest` | Can AI help shape a person's goals without taking control of the decision? | Capture, proposal, review, and explicit apply workflow with account-scoped credentials | Production deployment and current live features require re-verification |
| `Press S for Worker` | Can coding-agent behavior remain local, inspectable, and controlled by its operator? | Tool loop, memory, model switching, dashboard, and focused reliability tests | Portfolio branch and current demo path still need selection and verification |
| `Grasp of Eternity` | Can many interacting game systems create consequences that feel coherent? | Surface-aware movement, combat, progression, audio iteration, and runtime test discipline | Current gameplay and build state require Unity review before public claims |
| `Little Ecosystem` | Can experimentation make a living system easier to understand? | Aquaponics simulation with persisted experiments and farm layouts | Current Godot runtime and visuals still need re-verification |

The underlying progression is:

1. Make invisible value such as attention, trust, participation, and judgment visible.
2. Give people meaningful control over where that value goes.
3. Make actions consequential without confusing consequence with permanent domination.
4. Design incentives so the host does not silently capture everything participants create.
5. Stress-test the system for exclusion, capture, manipulation, and unintended control.

## Visitor outcomes

Within the first minute, a visitor should be able to:

- understand what Jason builds;
- see three strong projects without scrolling through coursework;
- open a live demo, source repository, video, or case study;
- distinguish current work from historical learning projects;
- find a resume and a reliable contact method.

## Information architecture

### Home

- Short positioning statement.
- One primary call to action: **View selected work**.
- One secondary call to action: **Contact Jason** or **View resume**.
- Three featured-project cards.
- Brief capabilities section.
- Short personal statement about learning, iteration, and building useful systems.

### Work

- A curated set of approximately six flagship projects.
- Supporting projects shown separately and with less visual weight.
- Filters are optional; clarity is more important than interface complexity.

### Case study

Each flagship project should answer:

1. What problem or idea motivated it?
2. What did Jason personally build or decide?
3. What technical approach was used?
4. What was difficult or uncertain?
5. How was it tested or evaluated?
6. What currently works?
7. What remains unfinished or unverified?
8. Where can the visitor see the demo, source, screenshots, or video?

### About

- Current professional direction.
- Relevant prior experience framed as an asset, not an apology.
- Preferred kinds of problems and teams.
- Concise tools and technologies list.

### Contact

- Professional email after the address is confirmed.
- GitHub and LinkedIn.
- Resume link after a current resume is supplied and reviewed.
- Do not publish a personal phone number by default.

## Extended case-study backlog

The homepage initially features Larn-like, Press S for Worker, and DoneQuest. The projects below remain candidates for deeper case studies as their evidence is verified. The Attention-to-west.net lineage is presented separately as evolving research rather than completed product work.

### 1. Press S for Worker

**Story:** Building a local-first coding agent and learning how tool-calling loops, model behavior, memory, and reliability actually work.

**Possible evidence:** architecture diagram, dashboard screenshot, focused test results, short recorded workflow, public repository.

**Required verification before publication:** choose the branch or commit to present and confirm the demo path works on this desktop.

### 2. Grasp of Eternity

**Story:** Iterative Unity game development spanning surface-aware movement, combat, progression, audio direction, testing, and visual design.

**Possible evidence:** gameplay video, selected screenshots, design evolution, system diagram, lessons from playtesting.

**Public boundary:** a case study or build can be public even if source remains private. Current runtime and build status must be verified before making claims.

### 3. DoneQuest

**Story:** A hosted multi-user goal planner with reviewed AI actions, account boundaries, and practical deployment concerns.

**Possible evidence:** sanitized product screenshots, capture-to-review workflow, data-boundary diagram, live link if reverified.

**Required verification before publication:** recheck the live deployment, database migration state, account isolation, and which features are actually available in production.

### 4. Larn-like

**Story:** A browser roguelike with persistent-world systems, evolving consequences, and substantial TypeScript architecture.

**Naming and attribution:** `Larn-like` is a working title for an independent experiment inspired by *Larn*, the 1986 roguelike created by Noah Morgan. Public copy should not present it as an official sequel, port, continuation, or endorsed project. Use "inspired by" rather than "built on" unless a future source-provenance audit establishes a derivative-code relationship. Choose a distinct name before commercialization.

**Possible evidence:** gameplay screenshots or video, system explanation, test results, public source or reviewed safety branch.

**Current case-study evidence:** the case-study page uses an inspected gameplay screenshot and the reviewed `safety/desktop-state-2026-09-26` branch. It prioritizes player-visible proof of the persistent-consequence loop and explains the horizon-to-hypothesis-to-experiment process. A four-image Mara-to-Iris walkthrough now demonstrates the death, persisted legacy site, functional shrine interaction, and evolved trophy-bearing killer in a controlled local production build. Query-gated controls made the walkthrough reproducible but are explicitly identified as verification tooling rather than shipped player-facing UX. The latest local baseline compiled successfully, completed the production build, passed 764 local tests, and completed the full browser walkthrough; Supabase-connected behavior remains a separate opt-in suite that has not been reverified. The page also documents Jason's original concept and direction alongside extensive Claude and Codex assistance with requirements, implementation, tests, and debugging.

**Required verification before publication:** explicitly retain the current technical limitations, confirm the reviewed source branch remains public, and obtain Jason's content approval. The controlled death-to-next-hero walkthrough is complete; the strongest next evidence is independent player use without demonstration controls. Before distributing or monetizing the game, audit code and content provenance, document licensing, and review the permanent product name.

### 5. Little Ecosystem

**Story:** A Godot aquaponics learning simulation with saved experiments and farm-layout persistence.

**Possible evidence:** short interactive or recorded demonstration, before-and-after experiment state, save-system explanation.

**Required verification before publication:** open the current Godot project, confirm the latest runnable state, and capture current visuals.

### 6. PoE Profit Assistant

**Story:** Turning domain-specific Path of Exile data into a useful trading and profit-analysis workflow.

**Possible evidence:** sanitized screenshots, an input-to-result walkthrough, architecture summary, public repository.

**Required verification before publication:** run the current desktop checkout, validate upstream data dependencies, and ensure no account data or credentials appear in the demo.

## Supporting work

These can strengthen the portfolio without competing with the flagship case studies:

- `PobToText`: focused Python utility and strong example of a clear input/output tool.
- `transcribe-video`: practical offline AI utility; verify current GPU and non-GPU behavior.
- `open-fleet`: agent-workflow case study; prefer a sanitized recording if connected services complicate a live demo.
- `slumberfalls-wp-theme`: client-oriented WordPress and frontend work.
- `UrbanSim`: promising lightweight browser demo after its local-only source is reviewed and published.
- Voice Trainer or RPG Dice Battle: potential immediate browser demonstration after testing and repository reconciliation.

Coursework should remain discoverable on GitHub but should not occupy flagship portfolio space.

## Project status vocabulary

Use consistent labels so unfinished work remains credible:

- **Live**: the public deployment was checked recently and its advertised workflow works.
- **Demo**: a bounded interactive or recorded demonstration is available.
- **In development**: active work exists, but the project is not presented as finished.
- **Case study**: the process and decisions are public even when the app or source is not.
- **Source available**: the linked repository intentionally represents the work being described.
- **Private source**: screenshots, video, or architecture are public while the repository remains private.
- **Historical**: useful learning work that is no longer presented as current practice.

Dates of last verification should be stored with project data, even if the date is not shown prominently on every card.

## Content and privacy rules

- Never publish API keys, tokens, cookies, private database contents, customer data, or local environment files.
- Do not imply that a repository branch is deployed unless the deployment was verified separately.
- Do not call a technical candidate approved when human listening, visual review, gameplay review, or production validation is still pending.
- Do not publish a personal phone number by default.
- Review family details, location precision, old social accounts, and personal email addresses before carrying them forward from historical sites.
- Use screenshots only when their contents and provenance are understood.
- Label course projects and experiments accurately.

## Visual and interaction direction

Working default for the first prototype:

- content-first and professional, with personality coming from project imagery and concise writing;
- dark or neutral foundation with one restrained accent color;
- strong typography and generous spacing;
- project cards that expose status and available evidence immediately;
- responsive from small phones through desktop;
- keyboard accessible, visible focus states, semantic headings, sufficient contrast, and reduced-motion support;
- minimal JavaScript and no framework dependency unless the content model later justifies one.

The visual direction remains open to Jason's review before implementation is treated as final.

## Technical direction

- Static HTML, CSS, and small progressive-enhancement JavaScript modules.
- Project content stored in a simple, reviewable format rather than embedded across many components.
- No server runtime required for the main portfolio.
- GitHub Pages as the first deployment target.
- Custom-domain configuration only after the current Apache site and DNS are backed up and documented.
- Individual applications remain in their own repositories and hosting environments.

## First-release acceptance criteria

- Homepage, work index, about/contact content, and at least three complete case studies.
- Every public claim checked against the relevant repository or running application.
- Every button and external link tested.
- No secrets or unintended personal data in source or rendered pages.
- Usable at narrow mobile, tablet, and desktop widths.
- Keyboard navigation and visible focus states work.
- Images have useful alternative text and reasonable file sizes.
- A not-found page exists.
- Local review is approved before commit and push.
- GitHub Pages is verified before any custom-domain change.

## Decisions needed from Jason

These questions should be answered during content review; they do not block the initial wireframe:

1. Which roles should the opening copy target most directly?
2. Should the public name be `Jason Ziegler` or `Jason M. Ziegler`?
3. Which professional email address should be published?
4. Is New Braunfels, Texas useful context, or should location be broader or omitted?
5. Is a current resume available, and should it be downloadable?
6. Which visual tone feels most authentic: understated technical, game-inspired, editorial, or something else?
7. Which three projects should appear above the fold at launch?

## Immediate next build step

After Jason reviews this brief, create a low-fidelity page structure and content schema using placeholder-safe copy. Do not publish or change DNS during the prototype stage.
