# 🚀 Free Claude Cowork Course (Interactive & Hands-On)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Course Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)](VERSION.md)
[![Claude Desktop](https://img.shields.io/badge/Claude-Desktop%20App-purple.svg)](https://claude.ai/download)
[![Status](https://img.shields.io/badge/Status-100%25%20Free%20%26%20Open-success.svg)](https://github.com/ROHITHELAYARAJA/Claude-)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ROHITHELAYARAJA/Claude-/pulls)

> **Learn Claude Cowork by doing** — the only interactive course taught directly by Claude inside the Claude Desktop Cowork mode.  
> **100% Free and Publicly Available** for professionals, managers, creators, and engineers worldwide.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Why This Course?](#-why-this-course)
- [Quickstart: How to Begin in 3 Minutes](#-quickstart-how-to-begin-in-3-minutes)
- [Choose Your Adventure (9 Real-World Scenarios)](#-choose-your-adventure-9-real-world-scenarios)
- [Complete Course Curriculum](#-complete-course-curriculum)
  - [Module 1: Working with Claude](#module-1-working-with-claude-23-hours)
  - [Module 2: Extending Claude](#module-2-extending-claude-12-hours)
- [Repository File Structure](#-repository-file-structure)
- [How the Interactive Engine Works](#-how-the-interactive-engine-works)
- [Tips for Cowork Success](#-tips-for-cowork-success)
- [Contributing & Community](#-contributing--community)
- [Credits & License](#-credits--license)

---

## 💡 Overview

This repository contains a full, production-tested curriculum that teaches you how to leverage **Claude Cowork** (the desktop workspace mode in Anthropic's Claude Desktop application) for real workplace tasks. 

**Zero coding required.** You do not need to write Python or scripts. Instead, you collaborate with Claude in real time across authentic workplace files — messy spreadsheets, customer complaints, unstructured notes, meeting transcripts, and brand guidelines.

---

## ✨ Why This Course?

- 🚫 **No Passive Videos:** You won't sit through endless video slides. You learn by actually prompting Claude and solving problems.
- 🎯 **Taught by Claude Itself:** Claude acts as your personal tutor, reading the lesson files, assigning realistic challenges, evaluating your responses, and giving you actionable feedback.
- 🏢 **Realistic Business Chaos:** Every scenario gives you messy, unorganized folders modeled after real-life company handovers.
- ⚡ **Full Tool Mastery:** Master file navigation, data synthesis, parallel agents, Word/Excel/PowerPoint generation, web research, and tool connectors (Slack, Notion, Google Workspace).

---

## ⚡ Quickstart: How to Begin in 3 Minutes

Follow these quick steps to launch the course right now:

```bash
# 1. Clone this repository to your local machine
git clone https://github.com/ROHITHELAYARAJA/Claude-.git
```

1. **Install Claude Desktop:** Download and install the official app from [claude.ai/download](https://claude.ai/download).
2. **Switch to Cowork Mode:** Click on the **Cowork** tab (icon located in the left sidebar of the Claude desktop app).
3. **Open the Course Folder:** Select your local `Claude-` repository folder as your active workspace.
4. **Start the Engine:** Send Claude the following message:
   ```text
   I downloaded a Claude Cowork course. Can you start it?
   ```
5. **Begin Learning:** Claude will read `course-structure.json`, welcome you, and guide you directly into **Lesson 1.1**!

> [!TIP]
> You can also inspect [COURSE_GUIDE.md](COURSE_GUIDE.md) for deeper architectural details on how the prompts and scenarios interact.

---

## 🎭 Choose Your Adventure (9 Real-World Scenarios)

Select a scenario that resonates with your daily work or career goals. Every scenario covers all core competencies through tailored context:

| # | Scenario | You'll Play As... | Best For | Focus Area |
|---|---|---|---|---|
| 1 | 🎪 **Event Planning** | Festival Coordinator | Event planners, admins, operations | Vendor logistics, emergency budget cuts |
| 2 | 📚 **Bookstore Turnaround** | New General Manager | Retail, small business, entrepreneurs | Inventory audits, community events |
| 3 | 🚀 **Product Launch** | Product Specialist | Tech, PMs, startups, founders | Post-launch bug recovery, user feedback |
| 4 | 🍽️ **Restaurant Rebrand** | Operations GM | Hospitality, restaurants, food service | Menu redesign, diner legacy retention |
| 5 | 🎨 **Nonprofit Grant** | Development Director | Nonprofits, grant writers, educators | Grant applications, donor pitch decks |
| 6 | ☕ **Loyalty Program** | Retention Manager | Marketing, CRM, customer success | Loyalty revamp, churn reduction |
| 7 | 🏠 **Real Estate** | Senior Real Estate Agent | Realtors, brokers, sales pros | Inherited listings, high-value client CRM |
| 8 | 💼 **Freelancer / Consultant** | Agency Consultant | Freelancers, agency leads, consultants | Client takeover, scope control, deliverables |
| 9 | 👥 **HR / People Ops** | Head of People | HR managers, people ops, talent leads | Onboarding docs, policy manual creation |

*All scenarios build the same foundational skills. Pick the industry you find most engaging!*

---

## 📖 Complete Course Curriculum

```
lesson-modules/
│
├── Module 1: Working with Claude (Core Skills)
│   ├── 1.1-introduction/          # Welcome to Cowork & choosing your scenario
│   ├── 1.2-understanding-claude/  # Prompting mental models and context management
│   ├── 1.3-file-exploration/      # Navigating messy folders and discovering key files
│   ├── 1.4-working-with-files/    # Extracting structured data and cross-file synthesis
│   ├── 1.5-cowork-features/       # Pro tips, keyboard shortcuts & native Cowork features
│   ├── 1.6-agents/                # Parallel processing and running autonomous sub-agents
│   ├── 1.7-document-creation/     # Generating formatted Word docs, spreadsheets & slides
│   ├── 1.8-web-research/          # Live internet search, citations & competitor benchmarking
│   └── 1.9-wrapup/                # Module 1 retrospective and bridge to Module 2
│
└── Module 2: Extending Claude (Integrations & Automation)
    ├── 2.1-connectors/            # Connecting Claude to Slack, Notion, Drive, and GitHub
    ├── 2.2-plugins/               # Installing domain-specific toolkits and integrations
    ├── 2.3-skills-and-commands/   # Custom slash commands and automated role skills
    ├── 2.4-customizing-plugins/   # Personalizing tone, brand voice, and guidelines
    ├── 2.5-your-first-real-workflow/ # Building a custom workflow for your actual job
    └── 2.6-wrapup/                # Final capstone, graduation, and next steps
```

### Module 1: Working with Claude (2-3 hours)
- **1.1 Introduction:** Orient to Claude Desktop Cowork mode and configure your chosen scenario.
- **1.2 Understanding Claude:** Learn how Claude parses workspaces, reads files, and allocates attention.
- **1.3 File Exploration:** Tame inherited disorder and locate mission-critical data in unknown folders.
- **1.4 Working with Files:** Synthesize multi-source documents into clear executive summaries.
- **1.5 Cowork Features:** Power-user techniques, multi-window reference, and shortcut workflows.
- **1.6 Agents:** Dispatch parallel background tasks to accelerate large projects.
- **1.7 Document Creation:** Automatically output executive presentations, budgets, and memos.
- **1.8 Web Research:** Conduct live web searches, synthesize industry benchmarks, and cite sources.
- **1.9 Wrap-up:** Check your progress against acceptance criteria and prepare for integrations.

### Module 2: Extending Claude (1-2 hours)
- **2.1 Connectors:** Link your workspace with Slack, Notion, Google Workspace, and GitHub.
- **2.2 Plugins:** Supercharge Claude with role-specific toolkits for marketing, finance, and engineering.
- **2.3 Skills & Slash Commands:** Create one-line shortcuts for repetitive daily tasks.
- **2.4 Customizing Plugins:** Tailor Claude’s communication tone to your organization's brand identity.
- **2.5 Your First Real Workflow:** Build a real, working system you will use Monday morning.
- **2.6 Course Wrap-up:** Final celebration, course review, and lifetime best practices.

---

## 📂 Repository File Structure

```
.
├── .gitignore                  # Clean repository ignore configuration
├── LICENSE                     # MIT Open Source License
├── README.md                   # Complete course overview & quickstart (this file)
├── COURSE_GUIDE.md             # In-depth architectural & pedagogical handbook
├── VERSION.md                  # Release version history and changelog
├── course-structure.json       # Interactive index and lesson progression manifest
├── feedback-config.json        # Progress tracking and feedback settings
│
├── company-context/            # Active scenario brand guidelines & scenario briefs
├── inherited-chaos/            # Raw unorganized sample files, notes, data, & feedback
├── templates/                  # Executive report and leadership update templates
├── analysis/                   # Destination folder for structured analysis outputs
├── reviews/                    # Stage for peer critiques and revisions
├── organized/                  # Destination for structured file reorganizations
├── attachments/                # Visual media, flyers, and reference assets
│
├── lesson-modules/             # 15 interactive lesson modules (Modules 1 & 2)
└── scenarios/                  # 9 self-contained industry challenge packs
```

---

## ⚙️ How the Interactive Engine Works

Each lesson file contains structured instructions that Claude interprets:

1. **Context Ingestion:** Claude checks `course-structure.json` and loads the active lesson markdown file.
2. **Concept Delivery:** Claude explains the objective and highlights the relevant files.
3. **Execution Challenge:** You are given an authentic task (e.g., *"Find the top 3 customer complaints in `inherited-chaos/` and draft a leadership memo using `templates/leadership-update-template.md`"*).
4. **The `STOP / USER` Gate:** Claude halts and waits for your response.
5. **Evaluation & Feedback:** Claude reviews your work against pedagogical benchmarks, offers tips for improvement, and proceeds to the next lesson.

---

## 💡 Tips for Cowork Success

- **Direct File Pointers:** Mention exact relative paths (e.g., `company-context/BRAND-VOICE.md`) when prompting Claude.
- **Specify the Format:** Ask Claude for specific outputs — bulleted lists, tables, markdown files, or structured JSON.
- **Cross-Reference Frequently:** Test Claude’s synthesis by asking:  
  *"Cross-reference `inherited-chaos/customer-feedback` with `company-context/LOYALTY-PROGRAM.md` and identify discrepancies."*
- **Resetting a Scenario:** You can reset or swap scenarios anytime by copying files from `scenarios/<scenario-name>` into `company-context/` and `inherited-chaos/`.

---

## 🤝 Contributing & Community

Contributions are welcome! If you have suggestions for:
- New industry scenarios
- Additional real-world templates
- Translations or typo fixes
- Integration guides for new Claude connectors

Feel free to open an issue or submit a pull request to [https://github.com/ROHITHELAYARAJA/Claude-](https://github.com/ROHITHELAYARAJA/Claude-).

---

## 📜 Credits & License

- **Repository Maintainer & Publisher:** [ROHITHELAYARAJA](https://github.com/ROHITHELAYARAJA)
- **Original Course Architecture:** Inspired by Clarence Archibald ([claudecoworkcourse.com](https://claudecoworkcourse.com))
- **License:** Released under the permissive [MIT License](LICENSE) — free for personal, commercial, and educational use.

---

<p align="center">
  <b>Happy Coworking! 🚀 Empower your daily productivity with Claude.</b>
</p>
