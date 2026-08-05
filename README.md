# very-first-repo
Portfolio project for my job application purposes

---

# 100Hires Portfolio Project

**Applicant:** Zahra Fitriansya ([Github](https://github.com/Frianz13), [LinkedIn](www.linkedin.com/in/frianz13))  


---

## About This Project

This repository documents my process of completing a technical portfolio task as part of a job application for a Junior Growth Marketing Specialist role at 100Hires.

My background is in Content Creation and Graphic Design, with experience in visual storytelling and digital media. I also have a background in AI evaluation : writing prompts, running model experiments, and reporting model weaknesses. This task felt like a natural extension of that curiosity. I approached it the same way I approach any creative challenge, with adaptability, research, and honesty about what did and didn't work.

---

# Task 1 — Environment Setup

## About This Task

**Date:** May 20, 2026

 This task required installing a set of AI-assisted development tools setting up a public GitHub repository, and documenting the entire process, including any obstacles encountered along the way.

## Tools Installed

| Tool | Details |
|---|---|
| Cursor IDE v3.4.20 | Downloaded from https://cursor.com/ |
| VS Code | Used as alternative after Cursor issue (see below) |
| Claude Code | Installed as VS Code extension |
| Codex | Installed as VS Code extension |
| Git 2.54.0 | Downloaded from https://git-scm.com/ |

---

## Steps Completed

1. Downloaded and installed Cursor IDE (v3.4.20)
2. Attempted to install Claude Code and Codex extensions inside Cursor
3. Investigated the issue thoroughly (documented in detail below)
4. Switched to VS Code as an alternative IDE
5. Successfully installed Claude Code and Codex as VS Code extensions
6. Created a public GitHub repository
7. Installed Git 2.54.0 and configured user credentials in the terminal
8. Cloned this repository locally and opened it in VS Code
9. Wrote this README, committed, and pushed to GitHub

---

## Issues Encountered & How I Solved Them

### Cursor IDE — Extensions Tab Not Found

**Cursor version:** 3.4.20

After installing Cursor, I was unable to find the Extensions tab anywhere in the interface. The task required going to Extensions → search "Claude Code" and "Codex", but that entry point simply did not exist in my installation.

Before attempting the installation, I watched YouTube tutorials to understand the process. Every tutorial I found showed the Extensions tab working without any issues, which gave me confidence to proceed. However, when I opened Cursor myself, the UI looked noticeably different from what was shown in those videos.

On closer inspection, the most recent tutorial available was already several months old, with no newer content covering my version. This suggested that Cursor had updated its interface at some point, and the Extensions system may have changed or broken in the process.

From there, I tried every approach I could find:

- **Keyboard shortcut:** Pressed `Ctrl+Shift+X` — no response at all, not even an error message
- **View menu:** Went through every item in the View menu — no Extensions option
- **Activity Bar:** Right-clicked the left sidebar — Extensions was not listed
- **AI assistants:** Asked multiple AI tools for help; every one gave the same standard answers (use Ctrl+Shift+X, check the View menu) that did not apply to what I was actually seeing
- **Professional mentor:** Consulted a mentor directly — they also could not locate the Extensions tab in my version of Cursor and confirmed that the standard steps were not working
- **Direct URL method:** On the mentor's suggestion, typed `cursor:extension/anthropic.claude-code` directly into the browser, which automatically redirected to the Cursor app. This did trigger a response, but instead of opening an extension page, Cursor threw an error in the bottom-right corner:
  > *Cannot read properties of undefined (reading 'activeEditor')*

  This confirmed that the Extensions system itself was broken in my installation, not just the UI navigation.

After exhausting all options, I found myself wondering whether the broken Extensions tab was perhaps intentional, a deliberate test of how I handle an obstacle that has no clean solution. I raised this with my mentor, who acknowledged it as a genuine possibility and suggested switching to VS Code as a plan B if Cursor remained unresolvable.

Before making the switch, I weighed the decision myself. The original task specified Cursor, and I was aware I was deviating from that. But after considering the options : continuing to troubleshoot an issue that neither I nor an experienced developer could resolve, versus switching to a well-supported IDE and delivering a finished, documented project, I made the independent call that VS Code was the right move. The end goal was a working project with honest documentation, and I'm confident that goal was met.

**Resolution:** I switched to **VS Code**, where the Extensions tab is clearly visible in the Activity Bar by default. I was immediately able to search for and install both Claude Code and Codex from there without any issues.

---

## Reflection

This process reinforced something I already believe : real-world problem solving is rarely a straight line. The ability to research independently, know when to pivot, and document failure honestly is just as valuable as following instructions perfectly.

I chose full transparency in this README.md file rather than glossing over the obstacle. If anything, hitting this wall and working through it is a more accurate demonstration of how I actually operate.

---

# Task 2 — Research Project : Cold Outreach for B2B SaaS

## About This Task

**Date:** June 16, 2026

For the second task I chose one topic and built a small research collection around it. The brief: pick a topic, find credible expert practitioners (not random blog posts), and gather their material into the `/research` folder so it reads like the start of a real playbook. I focused on people who actively teach **cold outreach for B2B SaaS**, vetted every source individually, and kept notes on what I found.

## Topic

From the eight topics offered, I chose **Cold Outreach Pipeline for B2B SaaS**, the one closest to what I already do by instinct (I run informal outreach for my own creative service) and the most structured and repeatable to research. The full reasoning is in [`research/sources.md`](research/sources.md#why-this-topic).

## Research Folder

Everything lives in [`/research`](research):

| Path | What's inside |
|---|---|
| `sources.md` | Master doc : why this topic, how I chose and collected the experts, the full list, patterns I noticed, and a finding on the Indonesian market |
| `youtube-transcripts/` | Transcripts, one subfolder per expert, pulled with yt-dlp and cleaned |
| `linkedin-posts/` | Key posts per expert, linked and summarized |
| `other/` | Supporting references |

**11 practitioners** in total : 6 through YouTube (Jason Bay, Josh Braun, John Barrows, Morgan J. Ingram, Armand Farrokh & Nick Cegelski from 30 Minutes to President's Club) and 5 through LinkedIn (Jed Mahrle, Will Allred, Florin Tatulea, Mark Colgan, Kevin Dorsey). Plus a note on the local Indonesian market.

## Reflection

Going in, I had no idea what this topic was. I first heard "Cold outreach pipeline for B2B SaaS" from the employer of 100Hires himself. I'd seen the words "pipeline," "B2B," and "SaaS" around before, but never knew what they meant. Through this task I finally do: cold outreach is reaching out to promote your business *first*, to people who don't know you yet; B2B (Business to Business) means selling to other businesses rather than consumers; and SaaS (Software as a Service) means the business runs on software that does the serving.

The hardest part was the searching. Scrolling LinkedIn for posts actually relevant to this topic was genuinely tough, they're mixed in with everyone's other business content, so I had to look carefully. It was harder still with local practitioners, who I expected to fit but who rarely post about cold outreach at all.

What I'm quietly proud of : I checked every source myself instead of trusting them blindly from AI assistant's search results, and that caught several that were mislabeled: videos credited to the wrong person, and a panel that wasn't a single expert. Catching those kept the whole collection honest. And what it taught me about myself is that I can pick up a completely unfamiliar, professional topic fast and that something I'd been doing on instinct for my own small business turned out to be the real thing, just without the vocabulary. I wasn't as far behind as I assumed.

---


# Task 3 — Playbook / SOP : Cold Outreach for B2B SaaS

## About This Task

**Date:** August 5, 2026

The third task asked me to turn the research from Task 2 into something usable : a playbook or standard operating procedure, built entirely from the practitioners I collected, with every recommendation traced back to the person it came from. Beyond the procedure itself, the brief asked for the parts most write-ups leave out : where the experts contradict each other and which side I take, what I decided to leave out, at least one idea of my own, the weaknesses of the result, and whose material I would not recommend following.

The full document is in [`playbook/README.md`](playbook/README.md).

## What's In It

| Section | Contents |
|---|---|
| **A. The pipeline** | 30 recommendations across 6 stages, from choosing who to contact through to handling the objection. Every one cited |
| **B. Where experts disagree** | 5 conflicts, and my position on each |
| **C. What I rejected and why** | 3 techniques I left out, with the reasoning |
| **D. My original ideas** | 2 ideas that came from me rather than the sources |
| **E. Weaknesses of this playbook** | 6 things I can see wrong with it |
| **F. Who I would NOT recommend following** | One test, applied to every source, and where it lands |

**49 citations, all linked. All 11 practitioners used.**

## The Constraint I Set

The playbook is written for a **first-time sender with no budget** : one person, one inbox, no paid data tools, no sales team. That was a deliberate choice. Most of the material I collected quietly assumes a funded B2B SaaS sales organisation, and a fair amount of it depends on paid software without saying so. Where a recommendation only works if you buy something, I say so and give the version that survives without it. For the same reason I define the trade vocabulary the first time it appears, since two months ago I did not know what any of it meant either.

## Reflection

The hardest part of this task was not writing it. It was checking it.

I went back to the original transcripts and posts repeatedly, and each pass found something : quotations that had drifted a word or two from what was actually said, a date I had gotten wrong by a year, a count of sources that was simply incorrect. The most uncomfortable find was a conflict between two experts that I had nearly written up as a genuine disagreement, until I went back and confirmed that one of them had never made the claim at all. It would have read convincingly. It was not true.

That experience shaped the whole document. It is why Section F judges sources by whether their claims can be checked without buying their product, and why I kept a figure in Section A that I explicitly say I would not plan around. It is also why Section E exists in the form it does : I would rather list the problems with this myself than have someone find them.

The other thing this task gave me was Section D. Every practitioner I read writes for a market where cold contact is ordinary. Mine is not. In Indonesia the financial regulator has effectively told the public that unsolicited contact offering something of value is itself a warning sign, and none of the eleven address a market that starts from there. Working out what you actually do about that, using the structure of the deliverability stage as the model, is the part of this document that is genuinely mine.
