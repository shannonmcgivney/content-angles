# Content Angles: a Claude skill

Never start a post from a blank page again. This skill gives Claude seven reusable story shapes and writes LinkedIn posts, 30 to 60 second video scripts and emails from them, one at a time or as a full week.

**[⬇️ Download content-angles.zip](https://github.com/shannonmcgivney/content-angles/releases/latest/download/content-angles.zip)**

## The seven angles

| Angle | The shape |
|---|---|
| **Mistake** | The common mistake → why smart people make it → why it backfires |
| **Myth** | The belief → where it comes from → what's actually true |
| **Client** | Their problem and result → what they tried first → what worked |
| **Reframe** | A limiting belief → what feeds it → the truer frame |
| **Problem** | The problem, named precisely → the real cause → the cost of doing nothing |
| **Prescription** | The pain → its root cause → one concrete fix |
| **Origin** | Where you were stuck → what you tried → what changed |

Every piece gets a hook, three beats and one call to action. The skill never makes up client stories, quotes or numbers. If an angle needs a real example, it asks you or leaves a marked placeholder.

## The belief thread (new in v1.1)

Posts that only teach or sell are easy to replace now that AI makes information cheap. The belief thread runs one thing you stand for through four parts of your life, so readers get to know the person behind the posts:

| Area | Covers |
|---|---|
| **Work** | career, clients, skills, your offer |
| **Relationships** | family, friends, hobbies |
| **Health** | mind, body, spirit |
| **Identity** | roots, culture, age, faith, values |

You're the main character in each story: your opinion and your way of doing things. Each area pairs with one of the seven angles. Claude asks for your belief if it can't find it, and it never invents a personal story. You decide how much to share.

## Install

**Claude.ai or the Claude desktop app:** download `content-angles.zip` (don't unzip it), then go to **Customize → Skills → + Add → Upload skill** and pick the zip.

**Claude Code:**

```bash
git clone https://github.com/shannonmcgivney/content-angles.git
cp -R content-angles/skills/content-angles ~/.claude/skills/
```

## Try it

- "Write a LinkedIn post about [topic] using the Myth angle."
- "Batch a week of content on [topic] for [audience]."
- "Turn this idea into a 45-second video script."
- "Here's what I stand for: [belief]. Write me four posts, one for each life area."

Tell Claude who your audience is and what you offer, or keep an about page or offer doc in your project, and it writes for them. You can also edit `SKILL.md` to make it yours.

## Credit

Adapted from the "Fab 5" content prompts in Caitlin Bacher's *Sales Every Day™*, rewritten and extended by McGivney Media. The belief thread is our own take on the "storytelling wheel" idea from a Jun Yuh reel; the text is original.

By McGivney Media.
