# SyncMate-GPT Version Status

## Current Status

**Project maturity:** Functional Custom GPT prototype / tech-demo  
**Application maturity:** Not yet alpha  
**Primary focus:** Emotional modeling, adaptive companion behavior, and jMonkeyEngine development support through Custom GPT prompting.

SyncMate-GPT is currently a functional Custom GPT prototype. It is intended to test behavior, prompting structure, emotional-state simulation, and development-assistant usefulness before being expanded into a full application.

## Active Version

**Local repository version:** `0.2.0-prototype`  
**Published GPT version:** `0.1.0-prototype`  
**Public GPT link status:** Behind local source  
**Current source of truth:** Repository files

Public GPT link:

<https://chatgpt.com/g/g-69f755206898819197e236aa504caf04-syncmate-for-jmonkeyengine>

## Version Meaning

| Version Label | Meaning |
|---|---|
| `prototype` | Experimental behavior test. Not a finished app. |
| `gpt` | Custom GPT configuration, instructions, knowledge files, and prompt behavior. |
| `app` | Future functional application code. |
| `alpha` | Future early app build with real persisted state and usable application features. |

## Current Components

| Component | Status | Notes |
|---|---:|---|
| Custom GPT | Functional prototype | Main working artifact. |
| Prompt instructions | Active | Used to shape SyncMate behavior. |
| Emotional modeling | Experimental | Tested through prompting and simulated state. |
| jMonkeyEngine support | Active | Core technical support domain. |
| Gradle project structure | Planned / in progress | Intended migration to multi-project layout. |
| Persistent memory engine | Not implemented | Future application-layer responsibility. |
| Desktop application | Not implemented | Future Java/JavaFX application target. |
| Multi-user support | Out of scope | Possible future endeavor, not current focus. |

## Deployment State

The public GPT link may not reflect the latest local repository state.

When updating the public GPT, compare the live GPT configuration against the repository source files and then update this section.

| Item | Current State |
|---|---|
| Local repo ahead of public GPT | Yes |
| Public GPT needs update | Yes |
| Changelog updated | See `CHANGELOG.md` |
| Next deployment target | Sync latest Custom GPT instructions and knowledge files |

## Development Direction

Short-term goal:

> Improve and test the Custom GPT prototype as a prompt-level emotional modeling experiment.

Medium-term goal:

> Move the Custom GPT materials into a Gradle multi-project structure under `:custom-gpt`.

Long-term goal:

> Expand SyncMate from a Custom GPT prototype into a functional application with application-managed state, emotional modeling, memory, and development-assistant features.

## Suggested Future Module Map

```text
syncmate-gpt
├─ :custom-gpt   -> Custom GPT instructions, knowledge, prompts, and tests
├─ :app-core     -> Future emotional-state engine and prompt composer
├─ :app-desktop  -> Future JavaFX desktop interface
└─ :experiments  -> Small isolated tests and prototypes
```

## Update Rules

Update this file when:

- The public GPT is updated.
- The local repository version changes.
- The project moves into a new maturity stage.
- A new Gradle subproject is added.
- The project gains real application functionality.

Do not use this file as a changelog. Historical changes belong in [`CHANGELOG.md`](https://github.com/Mark-Picknell/syncmate-gpt/blob/main/changelog.md).

## Last Reviewed

Date: 2026-05-09

Reviewer: Mark Picknell
