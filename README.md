# Be Brief. Be Brilliant. Be Gone. — Claude Skills

Three Claude skills for communicating with executives, from "Be Brief. Be Brilliant. Be Gone." by Yue Zhao, CPTO, Executive Coach at [The Uncommon Executive](https://theuncommonexecutive.com).

| Skill | What it does |
| --- | --- |
| **exec-update** | Turns a brain dump into a crisp executive update or ask: What Changed / Why It Matters / What I Need. |
| **exec-context** | Builds one-page context files on the executives you work with, then preps you for meetings with them. |
| **exec-practice** | Plays a skeptical, time-pressed executive so you can rehearse an ask, an update, or on-the-spot Q&A, then coaches you. |

The skills work on their own, and work better together: exec-update and exec-practice use the context files that exec-context creates.

## Install in the Claude app (web, desktop, mobile)

1. Download the zip for each skill you want:
   - [exec-update.zip](downloads/exec-update.zip)
   - [exec-context.zip](downloads/exec-context.zip)
   - [exec-practice.zip](downloads/exec-practice.zip)
2. In Claude, make sure code execution and file creation is turned on in Settings > Capabilities.
3. Go to Customize > Skills, click **+**, then **Create skill** > **Upload a skill**, and upload one zip. Repeat for each skill. Don't unzip them first.
4. Make sure each skill is toggled on.

On a Team or Enterprise plan, you can share the skills with colleagues from the same menu once you've uploaded them. If you don't see the option to upload, your admin may need to turn skills on.

## Install in Claude Code

Copy the skill folders into your personal skills folder:

```
git clone https://github.com/theuncommonexec/exec-skills.git
cp -r exec-skills/skills/* ~/.claude/skills/
```

## Use them

Just ask. For example:
- "Here's my brain dump for my update to the CFO, make it brief and brilliant."
- "Build a context file for Priya, our VP of Sales."
- "Play my skeptical VP of Product. I need to ask for 3 more weeks on the launch."

## License

Free to use and share with credit to Yue Zhao, The Uncommon Executive.
