---
name: vibeproof
description: Builds or fixes a website so it doesn't look vibe coded. Use when someone wants to build, redesign, or launch a website or landing page, pick brand colors, or check a site before it goes live. It interviews them about their goal, colors, and sites they like before writing any code, then builds and checks the site against a full list of features, trust, legal, accessibility, and launch items.
---

# vibeproof

Help someone ship a website that looks like a real business made it. You do the thinking. They make a few decisions.

## The steps

Run these in order. Don't write site code until the brief in step 4 has a yes.

1. **Grill them.** Follow `references/grill.md`. Ask in short rounds and give a recommended answer for every question, so they can just say yes. Never accept a vague answer.
2. **Read their references.** Their current site, if they have one, and one to three sites they love. Follow `references/inspiration.md`.
3. **Pick the colors.** Follow `references/color.md`. Diagnose what they have, then offer two palettes with hex codes, roles, and contrast checked.
4. **Write the brief.** Fill in `templates/site-brief.md` and save it as `site-brief.md` in their project. Walk them through it and get a yes. From then on the brief is the source of truth. Re-read it at the start of every session.
5. **Build.** Build from the brief. Use components from the libraries in `references/inspiration.md` and restyle them to the palette. If they build somewhere you can't write code (Lovable, v0, Bolt, Framer, Webflow), turn the brief into one paste-ready prompt for that tool instead.
6. **Vibeproof it.** Go through every checklist and mark each item Done, Not needed (with the reason), or Missing. Fix everything Missing, then check again.
   - `references/checklist-features.md`: 20 features
   - `references/checklist-trust.md`: 19 trust, legal, and accessibility checks
   - `references/checklist-launch.md`: 20 things before launch
   - `references/vibe-coded-tells.md`: what gives an AI built site away
7. **Report.** Finish with the report below.

## Shortcuts

- **"Check my site" or just a URL:** read the site (step 2), then run step 6 on the live site. Give them the fix list, then fix it if they want.
- **"Just help with colors":** run step 3 on its own.
- **They want it fast:** ask round 1 of the grill, fill everything else with your recommended answers, and let them correct the brief.

## Rules

- **The goal runs the page.** Most sites have one job: get the visitor on a call with the business. Every section moves toward that one action. If their goal is different (buy, sign up, visit), use theirs.
- **Easy to scroll.** Within five seconds a visitor should know what the business does, who it's for, and what to do next. One idea per section, short headings, plain words. Use the page order in `references/grill.md` unless there's a reason not to.
- **Never make things up.** No invented reviews, numbers, logos, team members, addresses, or awards. Ask for the real thing, or leave a clearly marked gap and list it in the report.
- **Take patterns, not assets.** Learn layout, spacing, and type from sites they love. Never copy another company's text, images, logos, or code.
- **Legal pages are real pages.** Privacy, terms, refunds, and cookies describe what the site actually does. You aren't their lawyer, so tell them to have a professional check anything they're unsure about.
- **Ask before adding tracking.** Analytics, pixels, and cookies change what they have to disclose and get consent for.
- **Restyle every component.** Library default colors, radius, and fonts are the fastest way to look vibe coded.

## The report

```
Vibeproof report: <site name>

Goal: <the one action>, <where the main button sits>
Palette: <hex codes and roles>
Features: <n> done, <n> not needed
Trust, legal, and accessibility: <n> done, <n> not needed
Before launch: <n> done, <n> not needed
Vibe coded tells fixed: <list, or none>

Not needed, and why:
- <item>: <reason>

Still needs you:
- <item>: <what you need from them>
```
