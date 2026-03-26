# 🧠 claude-skills

A collection of custom skills for [Claude](https://claude.ai) / [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

---

## 📦 Installation

<details>
<summary>🖥️ <strong>Claude Code (CLI / Desktop / Web)</strong></summary>

<br>

### Option 1: Clone directly into your skills directory

```bash
# Navigate to your Claude skills directory
cd ~/.claude/skills

# Clone the repo
git clone https://github.com/d3v0psdan/claude-skills
```

### Option 2: Copy individual skills

```bash
# Copy just the skill(s) you want
cp -r prompt-improver ~/.claude/skills/prompt-improver
```

### Option 3: Manual install

1. Download the skill folder (e.g. `prompt-improver/`)
2. Place it in `~/.claude/skills/`
3. That's it — Claude Code discovers skills automatically on next launch

<br>

> **📁 Expected structure:**
> ```
> ~/.claude/
> └── skills/
>     └── prompt-improver/
>         └── prompt-improver.md
> ```

</details>

<details>
<summary>💡 <strong>Verify it's installed</strong></summary>

<br>

Once installed, type the skill's slash command in Claude Code:

```
/prompt-improver
```

If Claude recognizes it, you're good to go. If not, double check the folder is in `~/.claude/skills/` and restart Claude Code.

</details>

---

## 🛠️ Skills

<details>
<summary>✨ <strong>prompt-improver</strong> - Turn brain dumps into perfectly structured prompts</summary>

<br>

Analyzes your prompt's complexity and rewrites it in the optimal format - clean Markdown for simple prompts, structured XML for complex ones.

**Usage:** `/prompt-improver` then paste your prompt.

**Example:**

```
❌ "help me make a chatbot that does support stuff and is nice and uses our api"
✅ Structured XML with <role>, <context>, <task>, <constraints>, <output_format>
```

</details>

---

## 🤝 Contributing

Have a skill to share? Open a PR with your skill folder and add an entry to this README following the format above.

## 📄 License

MIT
