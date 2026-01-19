# The People's Post Generator

_A free AI Skill for writing posts you're proud of with ChatGPT, Cursor, and Claude._

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

I recently violated my own rule of social media: I posted a rant that wasn't actionable.

TLDR my rant: Most AI content induces fear and FOMO. Influencers and algorithms symbiotically profit from keeping us impressed and confused. Aman Khan calls it a "race to the bottom," and we feel like we're in an "AI-hype-industrial complex."

**The solution is for real operators to share how they're really using AI at work.**

If you feel inhibited: It doesn't have to be novel or fancy. We're all hungry to know what **you're** doing, what's working—or not—for **you**.

Except operators don't have time. Not to write posts, not to "learn social media," and definitely not in public. I asked you to post more, with no way to do it.

**So, I'm open-sourcing the AI Skill I use to write my social posts.** "The People's Post Generator" is an AI [Skill](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview), basically a folder of text files that an LLM can pull into conversation when relevant.

## How I made this

I've been growing a little folder of text files to help me write my social posts. It helps me take a messy idea (Slack screenshot, Whatsapp chat export, Granola transcript, or just speech-to-text rant) and smoosh it into a post I'm proud of.

My process goes like this:

1. Get excited about something, start screen recording (e.g. Loom, Screen Studio, Cap, etc.)

2. Copy the transcript into AI chat (Cursor in my case) and tag the `@peoples-post-generator` folder

3. AI then asks me one question at a time to get more context out of me, deciding together on the focus, and drafting the post.

4. I share back my drafts, and AI holds me accountable to my own bar for publishing.

These text files grew through use, not Prompt Engineering™️. Each time AI flubbed, I added a line of instruction. If I came across an example I liked, I'd copy-paste it in.

Slowly, it became useful to me. When friends mentioned social posts, I'd zip the folder and send it over. After the seventh time, I decided to share it with the world.

## Quick start guide

A Skill is a folder with text files:

<img src="https://substack-post-media.s3.amazonaws.com/public/images/9a7f8053-dd8e-4af4-bc11-4ae28f7cf2b8_499x521.png" alt="A Skill is just a folder with text files" width="250">

You can [read each text file yourself](https://github.com/talsraviv/peoples-post-generator). It contains:

- A lightweight process

- Bank of examples (non-cringe "hooks," posts, calls to action)

- Guides to good writing (how not to sound like AI, a directive to [write like you talk](https://paulgraham.com/talk.html), and a TLDR of [*The Elements of Style*](https://en.wikipedia.org/wiki/The_Elements_of_Style))

You can use it in with favorite LLM:

### 1. Download the zip file to your computer

Head over to the [People's Post Generator Github page](https://github.com/talsraviv/peoples-post-generator) and download the zip file:

<img src="https://substack-post-media.s3.amazonaws.com/public/images/139131ef-cc54-4a6a-bc79-cf98dbadaa27_986x864.png" alt="Download the zip file" width="450">

### 2. Give it to your LLM of choice

#### ChatGPT/Gemini tutorial

*These steps are the same for Gemini, using "Gems."*

<a href="https://www.talraviv.co/i/184941256/chatgpt-tutorial"><img src="https://substack-video.s3.amazonaws.com/video_upload/post/184941256/ed8d598b-2aa6-4395-92c2-d7224bc366ec/transcoded-00001.png" alt="ChatGPT tutorial" width="450"></a>

#### Claude web tutorial

<a href="https://www.talraviv.co/i/184941256/claude-web-tutorial"><img src="https://substack-video.s3.amazonaws.com/video_upload/post/184941256/b542c695-d6e9-4252-b5b2-77e432686f0f/transcoded-00001.png" alt="Claude web tutorial" width="450"></a>

#### Cursor tutorial

*These steps work for any VSCode-based AI code editor (e.g. Antigravity, Cline, etc.)*

<a href="https://www.talraviv.co/i/184941256/cursor-tutorial"><img src="https://substack-video.s3.amazonaws.com/video_upload/post/184941256/8dec030d-4e17-40d4-bba1-08ebf17e17d1/transcoded-00001.png" alt="Cursor tutorial" width="450"></a>

#### Claude Code/Claude Cowork tutorial

<a href="https://www.talraviv.co/i/184941256/claude-codeclaude-cowork-tutorial"><img src="https://substack-video.s3.amazonaws.com/video_upload/post/184941256/585d76a1-3259-47ee-bc63-7347bcecb863/transcoded-00001.png" alt="Claude Code/Claude Cowork tutorial" width="450"></a>

### 3. Give AI a messy idea

I love Gary Vaynerchuk's commandment to "document, don't create." This AI skill is perfect for raw records of conversations and experiences. Throw any of these into the chat box and ask it to use the skill to help you turn it into a post:

- Screen recording transcript (my favorite)

- Slack thread screenshot

- Whatsapp chat export

- Meeting transcript (Peter Yang did this [mid-call](https://www.linkedin.com/posts/talsraviv_i-wanna-point-out-how-peter-yang-just-casually-activity-7416178300777254912-Bvz4?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAFRsvgBbHaQ1TYcarvEXfzpmkj3TOqADps))

- Or just rant into your favorite speech-to-text app

### 4. Make it your own

This skill works out-of-the-box. However, the folder `make-it-yours/` is well, completely yours. Once it's on your computer, feel free to delete anything, add your own ideas, or remove examples that you don't like. (In fact, you can edit the whole thing, `SKILL.MD`, included.)

### 5. [Optional] Contribute improvements

Most of the changes you'll make to this will be personal (examples you like, your personal bar for posting something). However, you might find ideas that are relevant to other people using this skill (whatever their taste). For example, a better conversation experience, or a way of making this skill more likely to get picked up by AI.

If you find a universal improvement, I would love for you to open an issue or even make a pull request:

1. Open a coding agent (Cursor, Claude Code, etc.)

2. Tell it: 

```I want to make a pull request to this github repository but not sure what to do: https://github.com/talsraviv/peoples-post-generator```

Let AI hold your hand through the process.

## Power to the humans

I created this for myself, gradually and organically. I needed something that would hold me accountable to my own standards when I'm tired and tempted to just hit publish. 

Now that it belongs to everyone, real people can call me out when I don't follow my own rules, not just AI.

## Acknowledgements

This skill owes a lot to the [Maven](https://maven.com/) team, both for their excellent guides: [The antidote to fluffy content: Tactical, Actionable, Concrete, Specific (TACS)](https://maven.com/resources/tacs-approach-to-engaging-content), [Spiky point of view](https://help.maven.com/en/articles/6728747-spiky-point-of-view), and [Leveraging social media](https://help.maven.com/en/articles/6732935-leveraging-social-media), and for everything I've absorbed osmotically from the team itself. 

Thank you to [Laura Ackerman](https://www.linkedin.com/in/lauraesquibelackerman/) for her advice to "write like you're telling a friend about something you're excited about."

Special thank you to [Teresa Torres](https://www.producttalk.org/), who has been a personal example of what "personal and practical" looks like done right. Her visible success with those principles is proof that you don't have to choose between being genuine and being effective. 
