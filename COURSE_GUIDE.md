# Interactive Course Guide & Learning Handbook

Welcome to the **Free Claude Cowork Course**! This guide details how the course works under the hood and how to get the most value out of Claude Desktop in Cowork mode.

---

## Table of Contents
1. [How Cowork Mode Works](#how-cowork-mode-works)
2. [Course Architecture](#course-architecture)
3. [The STOP / USER Interaction Loop](#the-stop--user-interaction-loop)
4. [Choosing & Switching Scenarios](#choosing--switching-scenarios)
5. [Modules Overview](#modules-overview)
6. [Power Tips for Real-World Work](#power-tips-for-real-world-work)
7. [Troubleshooting & FAQs](#troubleshooting--faqs)

---

## 1. How Cowork Mode Works

Claude Desktop features a dedicated **Cowork Mode** built for deep file system collaboration. Unlike standard web chat:
- Claude directly reads and references files in your selected workspace folder.
- Claude analyzes multiple formats (`.md`, `.csv`, `.docx`, `.xlsx`, `.pptx`, `.json`, images, and raw text).
- Claude can organize directories, draft communications, and run parallel agent tasks.

When you point Claude Cowork to this repository and ask:
> *"I downloaded a Claude Cowork course. Can you start it?"*

Claude reads `course-structure.json` and begins guiding you through the interactive curriculum.

---

## 2. Course Architecture

The repository is structured to mirror an authentic workplace environment:

```
├── course-structure.json       # Manifest indexing all modules, lessons, and order
├── feedback-config.json        # Course feedback and progress tracking config
├── lesson-modules/             # 15 interactive lesson modules (Module 1 & Module 2)
│   ├── 1.1-introduction/
│   ├── 1.2-understanding-claude/
│   ├── 1.3-file-exploration/
│   ├── ...
│   └── 2.6-wrapup/
├── scenarios/                  # 9 complete, self-contained industry scenarios
│   ├── event-planning/
│   ├── bookstore-turnaround/
│   ├── product-launch/
│   ├── restaurant-rebrand/
│   ├── nonprofit-grant/
│   ├── loyalty-program/
│   ├── real-estate/
│   ├── freelancer-consultant/
│   └── hr-people-ops/
├── company-context/            # Brand voice, company background & active situation
├── inherited-chaos/            # Realistic messy files, notes, data, & feedback
├── templates/                  # Document templates for executive updates & reports
├── analysis/                   # Workspace where Claude outputs analytical synthesis
├── reviews/                    # Stage where peer reviews & feedback are collected
└── organized/                  # Destination where structured files are cleaned up
```

---

## 3. The STOP / USER Interaction Loop

Every lesson markdown file in `lesson-modules/` utilizes an intentional pedagogical loop:

1. **Claude Teaches Concept:** Claude explains the principle with concrete workplace examples.
2. **Claude Issues Task:** A realistic challenge using files in `company-context/` or `inherited-chaos/`.
3. **The `STOP / USER` Token:** Claude halts execution and waits for your input or feedback.
4. **Interactive Review:** Claude analyzes what you did, gives constructive feedback, and transitions to the next lesson.

This ensures you are actually driving the workflow rather than passively reading text.

---

## 4. Choosing & Switching Scenarios

The course includes **9 distinct industry scenarios**. Each scenario equips the workspace with its own backstory, messy notes, customer feedback, financial summaries, and team dynamics:

| Scenario | Setting | Key Focus |
|---|---|---|
| **Event Planning** | Brightmoor Community Hub | Festival logistics, vendor chaos, volunteer coordination |
| **Bookstore Turnaround** | Inkwell Books | Inventory audit, local author outreach, small business revival |
| **Product Launch** | MotorCity Apps | Launch turnaround, sprint retrospectives, app store feedback |
| **Restaurant Rebrand** | State Fair Cafe | Menu modernization, legacy customer retention, brand revival |
| **Nonprofit Grant** | Detroit Youth Arts | Grant writing, donor proposals, program impact metrics |
| **Loyalty Program** | State Fair Cafe Loyalty | Customer churn analysis, reward restructuring, promotional copy |
| **Real Estate** | Lakefront Realty Group | High-value client handovers, listing sheets, CRM hygiene |
| **Freelance Consulting** | Corktown Creative | Scope management, billing reconciliations, client briefings |
| **HR / People Ops** | Woodward Ventures | Remote onboarding, policy handbook, compliance tracking |

To switch scenarios, copy the files from your chosen folder in `scenarios/<scenario-name>/` into `company-context/` and `inherited-chaos/`, or simply instruct Claude in Cowork mode:
> *"Switch my current scenario to Bookstore Turnaround."*

---

## 5. Modules Overview

### Module 1: Working with Claude (2-3 Hours)
Focuses on core collaboration skills inside any workspace:
- **1.1 Introduction:** Orienting to Cowork mode and selecting your path.
- **1.2 Understanding Claude:** Prompting mental models and context management.
- **1.3 File Exploration:** Quickly getting up to speed on messy directories.
- **1.4 Working with Files:** Deep data extraction, theme synthesis, and tabular cleanup.
- **1.5 Cowork Features:** Power shortcuts, multi-file inspection, and best practices.
- **1.6 Agents:** Running parallel workstreams and managing autonomous assistants.
- **1.7 Document Creation:** Producing polished Word docs, spreadsheets, and slide decks.
- **1.8 Web Research:** Fact-checking, competitor analysis, and web content extraction.
- **1.9 Wrap-up:** Milestone check, scenario recap, and preview of Module 2.

### Module 2: Extending Claude (1-2 Hours)
Focuses on connecting Claude to your external software ecosystem:
- **2.1 Connectors:** Integrating Slack, Notion, Google Drive, Gmail, and GitHub.
- **2.2 Plugins:** Activating specialized tools for legal, sales, finance, or engineering.
- **2.3 Skills & Slash Commands:** Building custom reusable prompt workflows.
- **2.4 Customizing Plugins:** Fine-tuning voice, constraints, and operational guidelines.
- **2.5 Your First Real Workflow:** Designing a reusable workflow for your Monday morning.
- **2.6 Course Capstone:** Final celebration, certification of completion, and community.

---

## 6. Power Tips for Real-World Work

- **Be Specific with File Formats:** When asking Claude to generate outputs, specify your preferred layout (e.g. Markdown tables, bulleted executive summaries, CSV format).
- **Use Multi-File Prompts:** Claude excels at cross-referencing. For instance: *"Compare the feedback in `inherited-chaos/customer-feedback` with the goals in `company-context/BRAND-VOICE.md`."*
- **Iterative Refinement:** Start wide, then drill down. Ask Claude to first summarize findings, then draft the complete deliverable.

---

## 7. Troubleshooting & FAQs

**Q: Claude doesn't start lesson 1.1 automatically.**  
A: Ensure the workspace directory is set to this repository root, then type:  
`"I downloaded the Claude Cowork course. Can you start with Lesson 1.1?"`

**Q: Can I use this with the free tier of Claude?**  
A: Cowork mode is a desktop feature. Please check your Anthropic plan and ensure the Claude Desktop app is up to date.

**Q: Can I suggest new scenarios or lessons?**  
A: Yes! Pull requests and issues are warmly welcomed. See `README.md` for contribution details.
