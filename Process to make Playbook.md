# How I made this playbook

Here's the actual process I followed,

## 1. Picked my 10 experts

Earlier in this project I had already shortlisted 10 LinkedIn/B2B growth experts and saved their bios in `research/sources.md`. So I started from that list instead of picking new people.

## 2. Went and read their actual posts, one by one

For each expert, I opened their LinkedIn profile myself and manually read through their recent posts. I copied the real post text and the real link for each one into the `research/linkedin-posts/` folder, one file per expert.

For 2 experts (Adam Robinson and Lara Acosta), they don't post much on LinkedIn directly, so instead I found full YouTube videos of theirs and used those as the source instead.

## 3. Messed it up the first time, and fixed it

Honestly, my first pass at this was bad. I was shortening links and updating dates in a hurry, and I ended up pasting the same 5 shortened links across almost every expert's file by mistake. Claude caught this when I asked it to build the playbook and pointed out that all the links were identical, which obviously wasn't right since these are 10 different people.

So I went back, opened each expert's profile again, and manually fixed every single link so it actually pointed to that person's real post. Then I did a second pass and made sure the dates matched too.

## 4. Gave Claude the actual post content, not just links

Even after fixing the links, Claude flagged that having a link and a date isn't enough to write a real recommendation with a citation — it needed to know what the post actually said. So for the experts where I had real substance, I copied and pasted the full post text directly into the conversation for Claude to read and use.

I did this in batches — Amelia Sordell, Rosanna Campbell, and Matt Barker first, then Santosh Sarangi and Sameer Alam, then Shweta Pandey, Shreya Jain, and Nancy Pezarkar. Some of these posts turned out to not really be about LinkedIn growth at all (like Santosh Sarangi's posts, which are mostly about Google Ads), and I told Claude to be honest about that instead of forcing them into the playbook where they didn't fit.

## 5. Used Claude to organize and write the actual playbook

Once I had real post content for most of the experts, I asked Claude to help me build the playbook itself — pull out real recommendations with sources attached, find actual places where two experts disagreed, and help me think through which ideas to reject, which one to add as my own, and which experts I wouldn't personally recommend and why.

I didn't just accept whatever it gave me first. A few rounds of back and forth:
- I asked it to restructure the "where experts disagree" section so it matched the exact format the task asked for (Author A / Author B / which side I take)
- I asked for a Word doc version once the content was solid
- I asked it to rewrite the whole thing in simpler, plainer English because the first version read too corporate/stiff for how I actually write

## 6. What's actually mine vs what Claude helped with

To be clear about where the work came from:
- **Finding the experts, reading their real posts, and pulling the actual content** — that was me, done manually by opening LinkedIn myself.
- **Catching my own mistakes** (duplicate links, thin data) — partly me noticing something felt off, partly Claude flagging it directly when I gave it the data to work with.
- **Organizing everything into a playbook format, spotting the disagreements, drafting the "rejected," "original idea," "weaknesses," and "who I wouldn't recommend" sections** — I worked through this with Claude, giving it the real research and reacting to/adjusting what it produced, rather than writing every sentence myself from scratch.
- **Final wording and tone** — I asked for a rewrite in simpler English once I saw the first draft, since it didn't sound like me.

## What I'd do differently next time

If I did this again, I'd read the actual post content and grab the real link at the same time, instead of doing links first and content later — doing it in two separate passes is what caused the duplicate-link mistake in the first place.