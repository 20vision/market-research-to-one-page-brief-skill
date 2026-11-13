# Market research to one-page brief (Claude skill)

Research a market from public sources and get a one-page brief with a link after every claim and a list of what was not found. The skill hands the job to your own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Example request

> Research the market for standing desks in Germany. In one page give: market size if a source states one, the five biggest sellers, typical price range, and two trends. Put a link after every claim and list what you could not find.

## What you get

- It answers with a one-page brief where each claim has its source link; what it could not find is listed as not found.
- A screenshot of the final screen and a link to a screen recording.

## What it does not do

- It reads public sources. Paid reports behind a paywall are not opened unless you hold the login and sign in on the live screen.
- A figure is only as good as its source; it names the source so you can judge.
- It writes a brief to start from, not advice to base an investment on.

## Install

Claude Code, as a personal skill:

```sh
mkdir -p ~/.claude/skills/market-research-to-one-page-brief && curl -fsSL https://raw.githubusercontent.com/20vision/market-research-to-one-page-brief-skill/main/SKILL.md -o ~/.claude/skills/market-research-to-one-page-brief/SKILL.md
```

With the skills tool (installs into the current project):

```sh
npx skills add 20vision/market-research-to-one-page-brief-skill
```

## Needs

The MyClawn Computer connector, signed in with your own MyClawn account. Setup and details: https://www.myclawn.com/docs/connectors?utm_source=github&utm_medium=repo&utm_campaign=market-research-to-one-page-brief

Full description of this job, with the steps and the limits: https://www.myclawn.com/research-a-market-and-write-a-brief?utm_source=github&utm_medium=repo&utm_campaign=market-research-to-one-page-brief

## Also listed

- https://www.skillsdirectory.com/skills/20vision-market-research-to-one-page-brief
- https://www.agensi.io/skills/market-research-to-one-page-brief
- All skills: https://github.com/20vision/skills

Made by 20Vision, the company behind MyClawn.
