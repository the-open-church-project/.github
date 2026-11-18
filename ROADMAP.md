# The Open Church Project: organization roadmap

This is the global roadmap for the organization. Project-specific details live
in their own roadmap directories.

## Current repositories

The organization currently has one public repository:

| Repository | Status | Purpose |
| --- | --- | --- |
| [`.github`](https://github.com/the-open-church-project/.github) | Active | Project direction, organization documentation, and collaboration guidance |

No product repositories, releases, or completed application features are
documented yet. The other projects below are proposed workstreams.

## Organization view

```mermaid
flowchart TB
    A["Organization foundations<br/>GitHub home and MIT license"]
    B["Define shared workflow,<br/>privacy, accessibility, and licensing"]
    A --> B

    V["Verger<br/>Open worship presenter"]
    S["Scripture voice detection"]
    L["Local and offline operation"]
    B --> V
    B --> S
    B --> L

    P["Integrated service prototype<br/>Voice-led scripture projection"]
    V --> P
    S --> P
    L --> P

    G["Later expansion<br/>Songs, media, and integrations"]
    P --> G
```

## Project portfolio

| Project | Status | Now | Next | Roadmap |
| --- | --- | --- | --- | --- |
| Organization documentation | Active | Keep this map and contribution guidance accurate | Add templates and governance as repositories are created | This document |
| Verger | Proposed | Define the operator and projector workflow | Build and test a focused scripture presentation MVP | [`roadmaps/verger/`](roadmaps/verger/ROADMAP.md) |
| Scripture voice detection | Proposed | Choose reference patterns, languages, and approved scripture sources | Prototype recognition, matching, confirmation, and fallback | [`roadmaps/scripture-voice/`](roadmaps/scripture-voice/ROADMAP.md) |
| Local and offline operation | Proposed | Define on-device audio, data, and model requirements | Make the integrated workflow usable without the internet | [`roadmaps/local-offline/`](roadmaps/local-offline/ROADMAP.md) |

## Cross-project stages

```mermaid
flowchart LR
    A["PAST<br/>Organization foundations"]
    B["NOW<br/>Define requirements"]
    C["NEXT<br/>Build connected MVPs"]
    D["LATER<br/>Integrate and expand"]
    A --> B --> C --> D
```

### Past

- Establish the project’s GitHub home.
- Add an MIT license.
- Define the initial product direction as open, privacy-conscious worship
  presentation with voice-led scripture projection and local operation.

### Now

- Work with churches and service operators to define practical service needs.
- Decide how the projects exchange scripture references and presentation state.
- Set expectations for accessibility, privacy, scripture text licensing, and
  supported languages.

### Next

- Build focused MVPs for presentation, scripture recognition, and local
  operation.
- Test them together in real services with clear operator controls and manual
  fallbacks.

### Later

- Integrate reliable service workflows into a simple installable product.
- Consider songs, media, supported integrations, and ongoing maintenance based
  on community feedback.

These ideas are not commitments. Priorities may change as we learn.
