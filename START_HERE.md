# Start Here

You have one conversation you keep postponing. Start there.

## 5-minute setup

### 1. Install Claude Code (if you have not already)

See `docs/install-claude-code.md` for step-by-step instructions.

You need:
- A Claude account with Claude Code access
- A terminal (Mac Terminal, Windows PowerShell, or Linux terminal)

### 2. Open this project

```bash
cd self-advocacy-os
claude
```

Claude Code reads the project instructions automatically. You do not need to paste a prompt.

This project also includes local skill cards in `skills/`. They teach Claude Code how to handle voice, research, skepticism, and human-readable wording without depending on any external skill install.

### 3. Pick your scenario

Tell Claude Code what you need:

**Negotiation:**
"I need to prepare for a compensation conversation. Walk me through the setup."

**Promotion:**
"I want to build a promotion case. Help me get started."

**Opportunity decision:**
"I have three opportunities and I need to decide which one deserves my time."

Claude Code will ask you to fill in your input files. Answer in your own words. Be specific.

### 4. Add your evidence

Drop any supporting files into the `evidence/` folder:
- Project notes
- Feedback screenshots or quotes
- Metrics and outcomes
- Scope documentation

Sanitize anything confidential first.

Claude Code will use the `skills/` folder to pressure-test the evidence, flag weak claims, and keep the final language direct.

### 5. Run it

Once your inputs and evidence are in place:

```
Create a negotiation prep packet using my files. Save to outputs/
```

Or:

```
Build my promotion case. Save to outputs/
```

Or:

```
Score my opportunities and recommend the best one. Save to outputs/
```

### 6. Practice

```
Role-play as my manager. Push back realistically. Score my responses.
```

## Want to see examples first?

Browse the `examples/` folder. Each scenario has filled-in inputs, evidence, and a sample output so you can see what the project produces before you start.

## Privacy

Everything runs locally on your machine. Your files never leave your computer. See `docs/privacy.md` for details.
