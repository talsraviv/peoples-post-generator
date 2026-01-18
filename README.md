Last week I violated my own rule of social media: I posted a rant that wasn't actionable.

My rant went like this:

- For the last 3 years, most AI content was designed to induce FOMO (I'll spare you the examples.)

- Influencers and algorithms symbiotically profit from keeping us impressed and confused (what Aman Khan refers to as a "race to the bottom").

- I can think of no better name than "[AI-hype-industrial complex](https://www.archives.gov/milestone-documents/president-dwight-d-eisenhowers-farewell-address)."

Then I shared these utterly unhelpful tips:

- We need real operators sharing what they're doing at work

- If you feel like an impostor, remember it doesn't have to be fancy or novel.

- You won't be cringe if you stay 1) personal and 2) practical

The problem with this is *real operators don't have time.* Not to write posts, not to "learn social media," and definitely not in public. I told people to post more but gave them no way to actually do it.

**So I'm making up for it by open-sourcing the AI instructions I've personally been using to write my social posts.** ["The People's Post Generator"](https://github.com/talsraviv/peoples-post-generator) is an AI [Skill](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview), which is a fancy term for a collection of text files that a chat LLM can autonomously decide to pull into a conversation.

## The People's Post Generator

[![Propaganda posters are the LinkedIn cringe posts of the mid-20th century](https://substack-post-media.s3.amazonaws.com/public/images/6f105332-24f8-4f75-ae98-31189803da9a_2816x1536.png)](https://substack-post-media.s3.amazonaws.com/public/images/6f105332-24f8-4f75-ae98-31189803da9a_2816x1536.png)

*Propaganda posters are the LinkedIn cringe posts of the mid-20th century.*

I've been organically growing a little folder of text files to help me write my social posts. It helped me take a messy idea (Slack screenshot, Whatsapp chat export, Granola transcript, or just speech-to-text rant) and collaboratively work it into a post I was proud of.

I did this without Prompt Engineering™️. Each time I saw a way to make AI work better for me, I'd add another line of instruction. If I came across an example I liked, I'd copy-paste it in.

Slowly, it became useful. When the topic of social posts came up in conversation, I found myself zipping up the text files and sharing it with colleagues. Why not share it with everyone?

A Skill is just a folder with text files:

[![A Skill is just a folder with text files](https://substack-post-media.s3.amazonaws.com/public/images/9a7f8053-dd8e-4af4-bc11-4ae28f7cf2b8_499x521.png)](https://substack-post-media.s3.amazonaws.com/public/images/9a7f8053-dd8e-4af4-bc11-4ae28f7cf2b8_499x521.png)

You can [read each text file yourself](https://github.com/talsraviv/peoples-post-generator). It's essentially:

- A lightweight process (gather materials, focus on a thesis, converge on a hook, write the post, evaluate the result)

- Bank of examples (non-cringe "hooks," posts, calls to action)

- Guides to good writing (how not to sound like AI, a directive to [write like you talk](https://paulgraham.com/talk.html), and a TLDR of [*The Elements of Style*](https://en.wikipedia.org/wiki/The_Elements_of_Style))

Here's how to use it, no technical skills required:

### 1. Download the zip file to your computer

Head over to the [People's Post Generator Github page](https://github.com/talsraviv/peoples-post-generator) and download the zip file:

[![Download the zip file](https://substack-post-media.s3.amazonaws.com/public/images/139131ef-cc54-4a6a-bc79-cf98dbadaa27_986x864.png)](https://substack-post-media.s3.amazonaws.com/public/images/139131ef-cc54-4a6a-bc79-cf98dbadaa27_986x864.png)

### 2. Give it to your AI of choice

#### [ChatGPT tutorial](https://www.talraviv.co/i/184941256/chatgpt-tutorial)

#### [Claude web tutorial](https://www.talraviv.co/i/184941256/claude-web-tutorial)

#### [Cursor tutorial](https://www.talraviv.co/i/184941256/cursor-tutorial)

#### [Claude Code/Claude Cowork tutorial](https://www.talraviv.co/i/184941256/claude-codeclaude-cowork-tutorial)

### 3. Make it your own

The folder `make-it-yours` is well, completely yours! Once it's on your computer, feel free to delete anything, add your own ideas, or remove examples that you don't like. (In fact, you can edit the whole thing, `SKILL.MD`, included.)

### 4. [Optional] Propose improvements with a pull request

Most of the changes you'll make to this will be personal (examples you like, your personal bar for posting something). However, you might come across ideas that might be relevant to other people using this skill (whatever their taste). For example, a better conversation experience, or a way of making this skill more likely to get picked up by AI.

**These are the shared values that make this "The People's Post Generator." If you submit a PR, it should align with these:**

1. Personal over prescriptive - "how I did X" not "how to do X"

2. Practical over philosophical - actionable takeaways, not vibes

3. No nearsighted hacks - no "comment for my PDF", no manufactured hypertension or [broetry](https://fenwick.media/rewild/magazine/dead-broets-society-behind-the-strange-story).

If you think there's a way to make this better that affects the common denominator for everyone, I would love for you to open an issue or even make a pull request:

1. Open a coding agent (Cursor, Claude Code, etc.)

2. Give it [this URL](https://github.com/talsraviv/peoples-post-generator) and tell it `I want to make a pull request to this github repository but not sure what to do.`

Let AI guide you from there!
