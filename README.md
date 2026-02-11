# slow build with claude code

free tools for product managers — try them interactively through claude code.

## what's inside

**pre-read generator** — paste a meeting transcript, get a pre-read for the next one. it remembers what happened — decisions, action items, open questions — and carries them forward so nothing gets lost between meetings. the more you use it, the better it gets. from here you can add calendar auth, connect to MCPs, or automate sending pre-reads to attendees.

**feedback analyzer** — paste customer feedback, get it sorted and prioritized. bugs, feature requests, ux issues, praise — all bucketed so you can actually see what's going on. use it to spot patterns, generate ideas, or draft PRDs. layer in your company goals and product context to make it even more useful.

## get started

```bash
git clone https://github.com/justirma/slowbuild-with-claude-code.git
cd slowbuild-with-claude-code
claude
```

then run `/start`.

## commands

| command | what it does |
|---|---|
| `/start` | setup and pick your first tool |
| `/feedback-analyzer` | analyze customer feedback |
| `/preread-generator` | generate meeting pre-reads |
| `/next` | what's next after trying the tools |

## learning modes

when you start, you pick how you want to learn:

- **just use it** — straight to results, minimal hand-holding
- **walk me through it** — same tool, but i'll explain what's happening and why along the way

## requirements

- [claude code](https://claude.ai/download)
- [anthropic api key](https://console.anthropic.com/)

## more coming soon

i like building things and i'll keep adding tools as i learn. please be patient if you find any bugs :)

subscribe to [slobuild.substack.com](https://slobuild.substack.com) to stay up to date.

## license

MIT
