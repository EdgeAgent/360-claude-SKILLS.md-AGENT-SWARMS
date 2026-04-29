# Claude Skills 360 — Installation Guide

Get up and running in under 2 minutes.

## Requirements

- **Claude Code** — Any plan (Free, Pro, or Max). Pro/Max recommended for agents.
- **OS** — macOS, Linux, or Windows with WSL
- **Terminal** — bash or zsh
- **License key** — Received via email after purchase (format: CS360-XXXX-XXXX-XXXX-XXXX)

---

## Install (One Command)

Open your terminal and run:

```bash
curl -fsSL https://claudeskills360.com/install.sh | bash
```

The installer will:
1. Prompt for your license key
2. Validate your key against our license server
3. Register your device (up to 3 devices per license)
4. Download the latest bundle
5. Install all skills, agents, and swarms to your Claude Code directories
6. Save your license key for future updates

**Total time: under 2 minutes**

---

## Step-by-Step Walkthrough

### 1. Run the command

```bash
curl -fsSL https://claudeskills360.com/install.sh | bash
```

### 2. Enter your license key when prompted

```
Enter your license key:
(Format: CS360-XXXX-XXXX-XXXX-XXXX)
> CS360-A7B2-K9M4-P3X8-W6L1
```

### 3. Wait for installation to complete

```
✓ License valid! Activations remaining: 2
✓ Downloading skills bundle...
✓ Skills installed:  74
✓ Agents installed:  28
✓ Swarms installed:  7
✓ License saved to:  ~/.claude/.cs360-license
```

### 4. Verify it worked

Open Claude Code and run:

```
/skills saas-idea-to-mvp
```

You should see the skill content load immediately.

---

## What Gets Installed

| Location | Contents | Count |
|----------|----------|-------|
| `~/.claude/skills/` | Professional skill files | 74 |
| `~/.claude/agents/` | Autonomous agent files | 28 |
| `~/.claude/swarms/` | Multi-agent orchestrators | 7 |
| `~/.claude/.cs360-license` | Your license key (for updates) | 1 |

### Total Bundle
- **74 production-ready skills** (150-250 lines each)
- **28 specialized agents** (for common workflows)
- **7 multi-agent swarms** (for complex automations)
- **Complete documentation** (CHEATSHEET.md, QUICKSTART.md, guides)

---

## Updating

To get the latest bundle, simply re-run the installer. Your saved license key will be detected automatically:

```bash
curl -fsSL https://claudeskills360.com/install.sh | bash
# Press Enter to use saved key
```

---

## Uninstalling

To remove all installed files:

```bash
# Remove all CS360 skills
rm -rf ~/.claude/skills/

# Remove all CS360 agents
rm -rf ~/.claude/agents/

# Remove all CS360 swarms
rm -rf ~/.claude/swarms/

# Remove license key
rm -f ~/.claude/.cs360-license
```

Or to just remove individual skills:

```bash
rm -f ~/.claude/skills/affiliate-site-generator.md
rm -f ~/.claude/skills/saas-idea-to-mvp.md
# ... continue for others
```

---

## Troubleshooting

### "Command not found: curl"

Install curl first:
- **macOS**: `brew install curl`
- **Ubuntu/Debian**: `sudo apt-get install curl`
- **Windows**: Use WSL terminal (not PowerShell)

### "License validation failed: Invalid license key"

- Confirm your key format is exactly `CS360-XXXX-XXXX-XXXX-XXXX` (all caps)
- Check for extra spaces or characters — copy-paste directly from your email
- Keys are case-sensitive — must be UPPERCASE

### "Maximum activations reached"

Your key has been used on 3 devices. To activate a new device:
1. Email hello@claudeskills360.com with your old device
2. We'll deactivate your oldest device
3. Run the installer again on your new device

### "Could not reach the license server"

- Check your internet connection
- Try: `curl -s https://claudeskills360.com` — if it fails, there's a network issue
- If behind a corporate proxy, the installer may need proxy configuration

### "Permission denied"

Try running directly instead of piping:

```bash
curl -fsSL https://claudeskills360.com/install.sh -o /tmp/install-cs360.sh
bash /tmp/install-cs360.sh
```

### Skills not showing up in Claude Code

1. Verify files were copied: `ls ~/.claude/skills/ | head -10`
2. **Restart Claude Code completely** (quit → reopen, not just refresh)
3. Try loading a skill by name: `/skills saas-idea-to-mvp`
4. Confirm you're in a project with Claude Code active
5. Check that files have .md extension: `ls ~/.claude/skills/*.md | wc -l` (should show 65)

### Agents or swarms not loading

1. Verify agent files: `ls ~/.claude/agents/ | wc -l` (should show 28)
2. Verify swarm files: `ls ~/.claude/swarms/ | wc -l` (should show 7)
3. Restart Claude Code
4. Check the agent/swarm documentation files for usage instructions

### Windows: Installation fails

Ensure you're using WSL (Windows Subsystem for Linux), not PowerShell or CMD:
1. Install WSL: `wsl --install` in PowerShell (as admin)
2. Open "Ubuntu" or your WSL distro from the Start menu
3. Run the installer from the WSL terminal

### macOS: "Operation not permitted"

You may need to grant Terminal permissions:
1. Go to System Preferences → Security & Privacy → Privacy tab
2. Select "Files and Folders" on the left
3. Find Terminal and grant access to your home directory
4. Try the installation again

---

## License Terms

- Each license key supports **3 device activations**
- You may deactivate an old device to activate a new one (email support)
- The bundle is for your personal or business use — not for redistribution
- **All sales are final** — this is a digital product
- Updates are free for the lifetime of your license

---

## Support

**Email**: hello@claudeskills360.com
**Setup Guide**: https://claudeskills360.com/setup

We respond within 24 hours on business days.

---

## Next Steps

1. After installation completes, open Claude Code
2. Read **QUICKSTART.md** to learn your first 10 skills
3. Use **CHEATSHEET.md** as a reference guide
4. Load your first skill: `/skills saas-idea-to-mvp`

**Happy building!**
