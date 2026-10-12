# Claude Code skills for this repo

Claude Code loads these automatically when it works in this repository.

| Skill | Source | Pinned commit | Use it for |
|---|---|---|---|
| humanizer | https://github.com/blader/humanizer (MIT) | 225a6f3 | Rewriting site copy so it doesn't read as AI-written. Run `/humanizer` or ask "humanize the copy in index.html". |
| scroll-craft | https://github.com/nateherkai/scroll-craft (MIT) | 75d81f7 | Designing scroll-driven landing pages. Ask "use scroll-craft to redesign the hero". |

scroll-craft notes: its scripts need Node.js, Playwright and ffmpeg. Image/video generation uses kie.ai (paid, needs KIE_AI_API_KEY in a local .env that is never committed). It can also build entirely from our own photos.

To update a skill, re-copy its folder from the source repo.
