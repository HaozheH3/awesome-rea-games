# Contributing to Awesome REA-Decompiled Games

Thanks for helping people find game decompilations, source reconstructions, recompilations, ports, and playable demos. Corrections to an existing entry are as welcome as new projects.

## What belongs here

- Game decompilation and source reconstruction projects, including projects made with [REA](https://github.com/morluto/rea).
- Recompilations and native ports built from reconstructed or recovered game code.
- Launchers and companion tools when they serve a game project already in the list.
- Public playable demos, including projects whose source code is private. Creator-shared original browser games go in **Playable showcases**.

Name the project for what it does. A decompilation, a port, and a launcher for the same game should have separate rows under one game heading. Describe REA use only when the project itself documents it. Do not add ROMs, disc images, or commercial game assets.

## Add a game or project

Open a pull request that adds the project to the appropriate game and category in [README.md](README.md). If the game already has a heading, add one row to its three-column table. If it is a new game, add a heading, one representative image with a source credit, a short English introduction, and the project table. Reuse the game's image across its projects by placing it once below the game heading.

Include these details in the pull request:

- **Game:** The original title, release year, platform, and edition or region when relevant.
- **Project:** Its canonical repository or website, plus a short description of its distinctive work and current status.
- **Type:** Source reconstruction, recompilation, native port, engine work, launcher, or playable demo.
- **Links:** A demo or release page when available, and the creator's original X post or other discovery source when relevant.
- **Image:** The image's source page and its reuse terms or permission if you add a new image.

A project row uses this format:

```markdown
| **Project name** | [Source](https://example.com/repo) · [Play](https://example.com/demo) | One or two sentences about this project's distinctive features and status. |
```

Keep Internet Archive uploads and same-title GitHub repositories as separate links unless their authors connect them. Include the original creator post when you have one.

## Before opening a pull request

- [ ] The project is under the right game and category, without a duplicate row.
- [ ] The games, projects, and categories badges match the counts in the README.
- [ ] Links open the resource described by their labels.
- [ ] The description says what this particular project does and how it differs from other projects for the same game.
- [ ] A new game has one representative image with a source credit and reuse basis.
- [ ] Original creator posts, demos, and Archive links are retained where relevant.
- [ ] No ROMs, disc images, or commercial game assets are included in the pull request.

Small fixes to titles, descriptions, links, and image credits are welcome too.
