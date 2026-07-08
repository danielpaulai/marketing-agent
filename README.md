# Your Marketing Agent OS

Extract your voice once. Then every skill writes like you, forever.

One shared file, `VOICE-DNA.md` (the ledger), and four skills that read it: text posts, image posts, carousels, and a complete offer document. Built for the AI Marketing Agent Summit.

## Install (2 lines, 90 seconds)

Open Claude Code in any folder and run:

```
claude plugin marketplace add danielpaulai/marketing-agent
claude plugin install marketing-agent@marketing-agent
```

No API keys. No connectors. Nothing to configure.

## First run: get measured (do this once)

Make a folder for your agent and start Claude Code in it:

```
mkdir my-marketing-agent && cd my-marketing-agent
claude
```

Then say:

> Extract my voice. Here are 5 posts I wrote, a transcript of me talking, and a few client replies.

The **extract-voice** skill interviews you, analyzes your real writing, and saves `VOICE-DNA.md` in the folder. That file is the ledger. Every other skill reads it first and skips the questions it answers.

## The skills

| Skill | What it does | Say this |
|---|---|---|
| **extract-voice** | Builds `VOICE-DNA.md` from your real writing | "Extract my voice" |
| **write-post** | LinkedIn post in your voice + animated preview | "Write me a post about X" |
| **image-post** | One ready-to-paste image prompt, on brand | "Image post about X" |
| **build-carousel** | Full carousel deck + one image prompt per slide | "Make me a carousel about X" |
| **build-offer** | Guided offer interview + animated offer document | "Build my offer" |

## The three triggers

1. **The command.** Type the request. You pull the trigger.
2. **The ask.** Just describe what you need ("I need a post for tomorrow"). Claude picks the right skill itself.
3. **The clock.** A routine. Say it once, it runs forever. This is the standing order.

### The standing-order routine (copy this)

In Claude Code, say:

> Create a routine: every morning at 7am, look at my business in VOICE-DNA.md, find one fresh, on-trend content idea for it, write the post in my voice using the write-post skill, and leave the post and an image prompt for it in a file called today-post.md.

Claude sets up the schedule. You wake up, open `today-post.md`, post it. Done before coffee.

## Requirements

- Claude Code installed (`npm install -g @anthropic-ai/claude-code`, or download the desktop app)
- A Claude account (Pro or Max recommended)

Measured once. Fits forever.
