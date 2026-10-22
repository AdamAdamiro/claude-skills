# Claude skills for LinkedIn writing

Six free skills for writing LinkedIn posts with Claude. Each one is a folder with a single `SKILL.md`. They are MIT licensed, need no sign-up and no account anywhere, and none of them posts anything. You copy the text out and post it yourself.

## Install

**Claude Code:** copy a skill folder into your skills directory.

```
cp -r linkedin-hook-mining ~/.claude/skills/
```

Restart Claude Code. The skill runs when your request matches its description, or when you ask for it by name.

**Claude.ai:** zip the skill folder and upload it as a custom skill in your settings.

## The six skills

| Folder | What it does |
|---|---|
| `linkedin-hook-mining` | Finds the opening lines of your best posts and writes new ones in the same shape with new words |
| `linkedin-post-goal` | Makes you pick one goal for a post and reshapes the draft for it |
| `linkedin-proof-card` | Records a result, a quote or a number with its source, date and limits |
| `linkedin-comment-mining` | Turns the questions, objections and phrasing in your comments into post ideas |
| `linkedin-right-to-say-it` | Checks a draft sentence by sentence for what you can defend, and fixes the rest |
| `linkedin-post-check` | Runs four checks by hand on a finished post: first line, concrete detail, proof and stock patterns |

## What these skills will not do

They write text, and you decide what gets posted. They never invent a number or a quote. If a figure is missing, they ask you for it or leave it out. They are a set of rules Claude follows, not a detector, so they cannot tell you whether a post "sounds human". Nobody can honestly promise you an undetectable post, and these skills don't.

## Who made them

[Adamiro](https://adamiro.com/?utm_source=github&utm_medium=repo&utm_campaign=claude-skills), a Swedish company. Its software reads what a B2B company's buyers are asking, drafts LinkedIn posts from the company's own material and schedules them once someone approves. These skills are the parts of that method you can run by hand.

## Licence

MIT. See [LICENSE](LICENSE).
