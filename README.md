# Self-Advocacy OS

A Claude Code project that helps you prepare for high-stakes career conversations: negotiation, promotion, and opportunity decisions.

This is not a chatbot prompt. It is a reusable workspace where your evidence, your context, and your standing instructions stay connected across every scenario you prepare for.

## What this project does

1. **Gathers your scattered evidence** into one place and maps each win to its source, business value, and proof strength
2. **Flags gaps** in your case before someone else finds them
3. **Drafts your ask** with a primary position and a fallback
4. **Anticipates pushback** with likely objections and prepared responses
5. **Lets you practice** by role-playing the decision-maker so you hear the hard questions before the real meeting
6. **Saves everything** so you can revisit, revise, and reuse

## Three scenarios

- **Negotiation** - compensation, title, rate, or scope conversations
- **Promotion** - building and presenting a promotion case with a visibility plan
- **Opportunity decisions** - choosing between competing options and setting boundaries on the ones that do not deserve your time

## Getting started

### Step 1: Install Claude Code

If you do not have Claude Code yet:
- Visit [claude.ai/code](https://claude.ai/code) for installation instructions
- You need a Claude account with Claude Code access
- Claude Code runs in your terminal (Mac, Windows, or Linux)

### Step 2: Open this project

```bash
cd self-advocacy-os
claude
```

Claude Code will read the project instructions automatically.

### Step 3: Fill in your inputs

Open the three files in `inputs/` and replace the prompts with your real situation:

- `inputs/wins.md` - Your accomplishments, metrics, and outcomes
- `inputs/context.md` - Who the decision-maker is and how they operate
- `inputs/ask.md` - What you want and what fallback would still be useful

For opportunity decisions, also fill in:
- `inputs/opportunities.md` - The options you are choosing between

### Step 4: Add your evidence

Drop any supporting files into the `evidence/` folder:
- Project notes, brag logs, feedback screenshots, metrics exports, scope documents
- Sanitize anything confidential. Remove names, client identifiers, or internal data you would not want stored in a project folder.

### Step 5: Run a scenario

Type one of these in Claude Code:

**Negotiation:**
```
Prepare a negotiation prep packet using my input files and evidence. Save to outputs/
```

**Promotion:**
```
Build a promotion case using my evidence. Include next-level pattern detection, proof gaps, validators, and a 30-day visibility plan. Save to outputs/
```

**Opportunity decision:**
```
Read my opportunities file. Score each option and recommend the strongest. Draft boundary language for declining the others. Save to outputs/
```

### Step 6: Practice

```
Role-play as my manager based on the context file. Push back realistically. Score my responses on clarity, proof, tone, and next ask.
```

## Project structure

```
self-advocacy-os/
  CLAUDE.md                             <- Standing instructions (the brain)
  START_HERE.md                         <- 5-minute quickstart guide
  README.md                             <- You are here
  LICENSE                               <- MIT License
  inputs/
    wins.md                             <- Your accomplishments (fill this in)
    context.md                          <- Decision-maker and dynamics
    ask.md                              <- What you want
    opportunities.md                    <- Options to evaluate
  evidence/
    README.md                           <- What to put here
    (drop your files here)
  outputs/
    README.md                           <- What gets saved here
    (prep packets saved here)
  examples/
    negotiation/                        <- Full example with sample output
      wins.md, context.md, ask.md
      project-notes.md, feedback.md, metrics.md
      sample-output.md
    promotion/                          <- Full example with sample output
      wins.md, context.md, ask.md
      sample-output.md
    opportunity/                        <- Full example with sample output
      opportunities.md
      sample-output.md
  docs/
    install-claude-code.md              <- Step-by-step installation
    how-it-works.md                     <- How the project works
    privacy.md                          <- Privacy and data safety
```

## Privacy

Everything stays on your machine. Claude Code runs locally. Your evidence files, input files, and outputs never leave your computer unless you choose to share them.

Do not put passwords, Social Security numbers, or financial account details in any file. You do not need them for self-advocacy preparation.

## Tips

- Start with one real conversation, not three hypothetical ones
- Be specific in your wins file. "Improved efficiency" is weak. "Reduced reporting prep from 4 hours to 45 minutes" is strong.
- The tool will flag weak proof. That is a feature, not a failure. Better to know now than in the meeting.
- Run the role-play more than once. Revise your answers. The goal is not to memorize lines. The goal is to hear your own case clearly.
- Save your outputs. Come back to them when the situation changes.

## Credit

Created by Sumaiya Shrabony for the Women in Tech Summit 2026.

Connect: [@thedata_ai.girl](https://instagram.com/thedata_ai.girl) | [Ground Truth on Substack](https://sumaiyashrabony.substack.com)
