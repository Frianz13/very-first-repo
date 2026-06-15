# Research : Cold Outreach Pipeline for B2B SaaS

## Why this topic

Out of the eight topics offered, I had to choose one. A few I set aside quickly, not at random, but because they centered on channels I don't actually use : one was built around Reddit, one around live webinars, and another around newsletters. One more simply didn't pull me in. I wanted a topic I could speak to from real habit, not fake familiarity. In the end I chose "Cold Outreach Pipeline for B2B SaaS" for two reasons : it's a system, not a guess. A pipeline is structured and repeatable, which fits the way I actually think, and it's a topic I already have a foothold in, since I've been running an informal version of outreach for my own creative service. That meant I could research it from real experience instead of starting from zero.

I'll be honest about my starting point. I had seen "B2B" and "SaaS" online before and always scrolled past, assuming they were for people in a different field than mine. Once I realized they actually mattered for this role, I stopped nodding along and looked them up properly. "Cold outreach" and "pipeline" were brand new words to me too.

What surprised me was realizing I had already been doing a rough version of this without the vocabulary for it. Running my own creative service (Frianz Digiverse), I promote my business through WhatsApp Status seen by thousands of contacts and in various group chats with many strangers, but I deliberately offer to people I already know first, so they can leave a testimonial and hopefully refer me to their own network. I've even had a B2B job in miniature : a local merchant ordered my service to design promotional banners for their goods. (As for SaaS, honestly, nearly every tool I use is free; the only thing I "subscribe" to is mobile data or a Wi-Fi plan.)

So the topic that looked the most foreign at first turned out to be the closest to what I already do by instinct. That's why I picked it.

## Approach

**How I chose the experts :** I focused on people who actively teach cold outreach for B2B SaaS, real practitioners (founders, sales leaders, coaches, podcast hosts), not generic blog posts or random Google results. I used an AI assistant (Claude) to help surface candidates and pull their material, but I vetted every source myself, checking the actual speaker or author before including it. That mattered : the AI's first suggestions included a few mislabels, a video credited to the wrong speaker, and a multi-speaker panel treated as one expert, which I caught and corrected.

**How I collected the material :** YouTube transcripts were pulled with `yt-dlp` (run and cleaned with help from Claude), from each video's caption track. Most are YouTube auto-generated captions (~95% accurate); one is publisher-provided. They were then cleaned, timestamps and markup stripped, HTML entities decoded, and reformatted into readable paragraphs. LinkedIn posts were collected by linking to the original public post and summarizing the key tactic in my own words.

**Folder structure :**
- `youtube-transcripts/` — one subfolder per expert
- `linkedin-posts/` — one file per expert
- `other/` — supporting references (e.g., local-market sources)

## Experts

Eleven practitioners, plus an Indonesian-market note (see Findings).

### YouTube (transcripts in `youtube-transcripts/`)
1. **Jason Bay** — founder, Outbound Squad. Cold email + cold call frameworks. *(2 transcripts)*
2. **Armand Farrokh & Nick Cegelski** — 30 Minutes to President's Club (top sales podcast). A large-scale personalized cold email experiment. *(1 transcript)*
3. **Josh Braun** — low-pressure cold calling. *(3 short transcripts)*
4. **John Barrows** — AE/SDR training: prospecting, cold call openers, follow-up. *(6 short transcripts)*
5. **Morgan J. Ingram** — outbound & video prospecting. *(1 transcript)*

### LinkedIn (posts in `linkedin-posts/`)
6. **Jed Mahrle** (Practical Prospecting) — cold email frameworks + warm-calling replies. *(3 posts)*
7. **Will Allred** (Lavender) — cold email copy + deliverability experiments. *(3 posts)*
8. **Florin Tatulea** — data-driven outbound experiments. *(3 posts)*
9. **Mark Colgan** — fixing broken outbound / building predictable pipelines. *(3 posts)*
10. **Kevin "KD" Dorsey** — sales leadership & outbound: tiered prospecting ("3 Is"), KPIC video framework, cold-email data quality. *(3 posts older/evergreen)*

### Indonesian / local market
See **Findings** below. Supporting reference saved in `other/`.

## What I noticed : patterns across experts

Looking across everyone I collected, a few things kept repeating :

- **Relevance beats volume.** This was the idea that came up the most, in different words from Jed Mahrle, Will Allred, Mark Colgan, and Florin Tatulea : knowing the specific buyer and their real situation matters far more than blasting a big list or leaning on clever personalization tricks. Mark Colgan goes furthest, he says *who* you target is the single biggest lever, more than messaging or tools.
- **It's a system, multi-touch and multi-channel.** Follow-ups, and combining email with calls, show up again and again (Jason Bay; Jed Mahrle even calls people who already replied), not one-and-done.
- **Deliverability and data quality decide whether cold email is even seen** (Will Allred, Kevin Dorsey).
- **Handle objections by acknowledging first, not pushing harder** (Florin Tatulea's 4-step framework, Jason Bay's call teardowns).

One thing genuinely surprised me. In Indonesia, a call or message from someone you don't know is usually assumed to be a scam, so I'd never thought of cold outreach as something *normal*. It was a small surprise to realize that for businesses abroad, this kind of outreach isn't just accepted, it's expected, even necessary.

And it turned out I'd already been doing a rough version of it. For my own creative service I offer through WhatsApp Status seen by thousands of contacts (some I don't actually know, cloned from my parents' contacts), and in WhatsApp groups mostly with strangers in them. I've offered face-to-face when the setting allowed, and I once printed brochures for my digital services and handed them out wherever I stopped. I just never had the words "cold outreach" for any of it.

## Findings : the Indonesian / local market

When I looked for Indonesian practitioners who publicly teach cold outreach for B2B SaaS, I found very little. On LinkedIn I found two people in the field : Putri Aisyah Pradika (Head of Sales at Mekari Qontak, Indonesia's #1 SaaS company) and Alfin Sharil Widantoro. Plus the SAB agency's blog on the topic. But the two individuals rarely post anything relevant : mostly reshares, or the occasional job opening. SAB doesn't credit an individual author, though its About page lists the team behind it. (Indonesian email content like the KIRIM.EMAIL "KEPO" podcast also leans toward permission-based email *marketing* rather than cold *outbound*.)

Why so little? A few guesses from my thoughts. The people who actually do this may simply be too busy running their businesses to stop and document how it works. The audience for such a specific niche may also feel too small to write for. And cold outreach sits awkwardly against a local culture that tends to be wary of contact from strangers. A message or call from someone unknown is easily met with suspicion, which may make people hesitant to teach it openly.

So my takeaway is itself a finding : in Indonesia, B2B SaaS cold outreach seems to be widely practiced but rarely documented publicly. That's a content gap I noticed firsthand. It's a bit of a shame, because I know there are young people like me who would want to learn this and would have a hard time finding it. If my own business ever grows into the kind of thing we've been studying here, and if I have the time, I might be the one to make that content, like the way those experts do.

