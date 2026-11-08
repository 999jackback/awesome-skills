::: {align="center"}
# Awesome AI Agent Skills

**A curated directory of reusable skills, workflows, and resources for
AI agents.**

Discover practical capabilities for coding, research, writing, design,
automation, data, and more.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions
Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**Browse · Learn · Build · Share**
:::

------------------------------------------------------------------------

## What are AI agent skills?

AI agent skills are reusable packages of task-specific instructions,
supporting files, and (where needed) scripts that help an AI agent
perform a workflow consistently.

A skill commonly contains a `SKILL.md` file with metadata and
instructions. It may also include reference documents, templates,
examples, or executable scripts. Compatible agents can load the relevant
instructions when a task calls for them.

> **Compatibility note:** Skill formats and discovery mechanisms vary
> between products. A skill that follows the open Agent Skills
> conventions may work across multiple compatible agents, but
> compatibility is not automatic. Check each agent's current
> documentation and the skill's requirements before installing it.

## Contents

-   [Getting started](#getting-started)
-   [Supported agents and tools](#supported-agents-and-tools)
-   [Skill collections](#skill-collections)
-   [Skills by category](#skills-by-category)
-   [Skill discovery and
    installation](#skill-discovery-and-installation)
-   [Creating a skill](#creating-a-skill)
-   [Choosing the right approach](#choosing-the-right-approach)
-   [Security and responsible use](#security-and-responsible-use)
-   [Contributing](#contributing)
-   [Useful documentation](#useful-documentation)

## Getting started

### 1. Find a skill

Start with a trusted source or one of the collections listed below. Read
the skill's description, supported agents, dependencies, license, and
installation instructions.

### 2. Check compatibility

Confirm that your AI tool supports the skill's format and installation
method. Do not assume that a Claude-specific plugin, a Copilot
instruction file, an MCP server, and a portable `SKILL.md` package are
interchangeable.

### 3. Review before installing

Inspect the complete skill directory, including scripts and referenced
files. Understand what permissions, files, network access, and
credentials it may use.

### 4. Install and test

Follow the source project's official instructions. Test in a disposable
project or a restricted environment before using a skill on important
work.

## Supported agents and tools

The following products and ecosystems are relevant to AI agent
workflows. Their extension formats and capabilities differ; follow the
official documentation for each.

  ------------------------------------------------------------------------------------------------------
  Agent / ecosystem       Useful starting point                                  Notes
  ----------------------- ------------------------------------------------------ -----------------------
  **OpenAI Codex**        [Codex                                                 Codex supports
                          documentation](https://developers.openai.com/codex/) · skills-based workflows.
                          [OpenAI skills](https://github.com/openai/skills)      Check current
                                                                                 installation and
                                                                                 compatibility guidance.

  **ChatGPT**             [ChatGPT](https://chatgpt.com/) · [OpenAI              Availability and skill
                          skills](https://github.com/openai/skills)              workflows depend on the
                                                                                 ChatGPT product surface
                                                                                 and supported
                                                                                 integrations.

  **Claude**              [Claude](https://claude.ai/) · [Anthropic              Claude has its own
                          skills](https://github.com/anthropics/skills)          Skills and Claude Code
                                                                                 extension workflows.

  **Gemini**              [Gemini](https://gemini.google.com/) · [Gemini         Check the relevant
                          CLI](https://github.com/google-gemini/gemini-cli)      Gemini product's
                                                                                 current extension and
                                                                                 instruction
                                                                                 conventions.

  **GitHub Copilot**      [Copilot                                               Copilot supports
                          documentation](https://docs.github.com/en/copilot) ·   repository
                          [Awesome                                               instructions, prompt
                          Copilot](https://github.com/github/awesome-copilot)    files, agents, and
                                                                                 other extension
                                                                                 mechanisms.

  **Cursor**              [Cursor documentation](https://docs.cursor.com/)       Cursor has project
                                                                                 rules and agent
                                                                                 workflows; verify
                                                                                 whether a particular
                                                                                 skill format is
                                                                                 supported.

  **Windsurf**            [Windsurf documentation](https://docs.windsurf.com/)   Uses its own rules and
                                                                                 workflow conventions.

  **Other compatible      [Agent Skills specification](https://agentskills.io/)  Consult the
  agents**                                                                       specification and each
                                                                                 agent's implementation
                                                                                 notes.
  ------------------------------------------------------------------------------------------------------

## Skill collections

These repositories and directories are useful starting points for
discovering skills. They are independent projects; inclusion here is not
an endorsement or a security audit.

  ----------------------------------------------------------------------------------------------------
  Collection                                                       Focus
  ---------------------------------------------------------------- -----------------------------------
  [OpenAI Skills](https://github.com/openai/skills)                Skills and examples from OpenAI.

  [Anthropic Skills](https://github.com/anthropics/skills)         Official examples including
                                                                   document, design, development, and
                                                                   skill-creation workflows.

  [GitHub Awesome                                                  Community resources for GitHub
  Copilot](https://github.com/github/awesome-copilot)              Copilot, including custom
                                                                   instructions, prompts, and agents.

  [Composio Awesome Claude                                         A large community collection
  Skills](https://github.com/ComposioHQ/awesome-claude-skills)     originally focused on Claude
                                                                   skills.

  [obra/superpowers](https://github.com/obra/superpowers)          Software development workflows such
                                                                   as brainstorming, planning, TDD,
                                                                   and code review.

  [Vercel Agent                                                    Frontend and React-oriented agent
  Skills](https://github.com/vercel-labs/agent-skills)             skills.

  [Expo Skills](https://github.com/expo/skills)                    Skills for Expo and React Native
                                                                   development.

  [K-Dense Scientific                                              Scientific and research-oriented
  Skills](https://github.com/K-Dense-AI/scientific-agent-skills)   agent workflows.

  [Trail of Bits Skills](https://github.com/trailofbits/skills)    Security-focused skills and
                                                                   engineering workflows.

  [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) Tooling for turning documentation
                                                                   sources into skill resources.

  [Skills directory](https://skills.sh/)                           Searchable directory and
                                                                   installation ecosystem for agent
                                                                   skills.
  ----------------------------------------------------------------------------------------------------

## Skills by category

The categories below are an organizing framework for this directory. Add
entries only when the linked project and its capabilities have been
checked.

### Software development

-   [OpenAI Skills](https://github.com/openai/skills) --- official skill
    examples and workflows.
-   [Anthropic Skills](https://github.com/anthropics/skills) ---
    development and software-related examples.
-   [obra/superpowers](https://github.com/obra/superpowers) ---
    structured development practices, planning, testing, and
    collaboration.
-   [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills)
    --- React and frontend engineering guidance.
-   [Expo Skills](https://github.com/expo/skills) --- Expo and React
    Native workflows.

### Web design and user experience

-   [Frontend
    Design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)
    --- guidance for distinctive, considered frontend design.
-   [Web Artifacts
    Builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder)
    --- workflows for building interactive web artifacts.
-   [shadcn/ui](https://ui.shadcn.com/docs/skills) --- skills and
    guidance for working with shadcn/ui components.
-   [Frontend Slides](https://github.com/zarazhangrui/frontend-slides)
    --- presentation creation with web technologies.

### Documents and productivity

-   [DOCX](https://github.com/anthropics/skills/tree/main/skills/docx)
    --- Word document creation and editing workflows.
-   [PDF](https://github.com/anthropics/skills/tree/main/skills/pdf) ---
    PDF reading, creation, and manipulation workflows.
-   [PPTX](https://github.com/anthropics/skills/tree/main/skills/pptx)
    --- PowerPoint presentation workflows.
-   [XLSX](https://github.com/anthropics/skills/tree/main/skills/xlsx)
    --- spreadsheet creation, editing, and analysis.
-   [Internal
    Communications](https://github.com/anthropics/skills/tree/main/skills/internal-comms)
    --- internal communications and business writing.

### Research and data

-   [K-Dense Scientific
    Skills](https://github.com/K-Dense-AI/scientific-agent-skills) ---
    scientific and research workflows.
-   [D3.js
    Skill](https://github.com/chrisvoncsefalvay/claude-d3js-skill) ---
    data visualization with D3.js.
-   [Claude Scientific
    Skills](https://github.com/K-Dense-AI/claude-scientific-skills) ---
    specialized scientific and technical workflows.

### Security and quality

-   [Trail of Bits Skills](https://github.com/trailofbits/skills) ---
    security engineering, code analysis, and review resources.
-   [Web App
    Testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing)
    --- browser-based web application testing workflows.
-   [Playwright Skill](https://github.com/lackeyjb/playwright-skill) ---
    browser automation and testing with Playwright.

### Creative work and media

-   [Algorithmic
    Art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art)
    --- generative art workflows.
-   [Canvas
    Design](https://github.com/anthropics/skills/tree/main/skills/canvas-design)
    --- visual design workflows.
-   [Slack GIF
    Creator](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator)
    --- animated GIF creation for Slack.

### Building and managing skills

-   [Skill
    Creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator)
    --- guided skill creation.
-   [MCP
    Builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder)
    --- guidance for building Model Context Protocol servers.
-   [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) ---
    documentation-to-skill tooling.

> **Listing policy:** A link in this README is a discovery pointer, not
> a guarantee that the project is maintained, safe, free, compatible
> with every agent, or officially supported by this repository. Check
> the upstream project before use.

## Skill discovery and installation

### Using the Skills CLI

The community Skills CLI can discover and install skills from supported
repositories. Check its documentation and the target agent's
compatibility before using it.

``` bash
# Browse CLI usage and options
npx skills --help

# Add a skill from a repository (replace with a verified repository)
npx skills add owner/repository

# List installed skills
npx skills list
```

For current usage, agent selection, global installation, and update
commands, consult the [Skills CLI documentation](https://skills.sh/).

### Manual installation

There is no single universal installation path. A common manual workflow
is:

1.  Clone or download the trusted skill repository.
2.  Read its `SKILL.md`, scripts, and referenced resources.
3.  Identify the target agent's documented skills or instruction
    directory.
4.  Copy or link the skill into that location using the agent's
    supported structure.
5.  Restart or reload the agent if required, then test the skill.

Do not copy a skill into a guessed directory. Use the official
documentation for the specific agent and version.

## Creating a skill

A simple skill directory can look like this:

``` text
my-skill/
├── SKILL.md
├── scripts/
│   └── helper.py
└── references/
    └── guide.md
```

A minimal `SKILL.md` may use YAML frontmatter:

``` markdown
---
name: my-skill
description: A concise description of the task this skill helps an agent perform.
---

# My Skill

## Purpose
Explain the problem this skill solves.

## Instructions
Give clear, ordered, actionable steps.

## Quality checks
Describe how the agent should verify its work.

## Safety
Explain relevant permissions, data handling, and actions that require approval.
```

### Skill authoring guidelines

-   Give the skill one clear purpose and a descriptive name.
-   Write instructions that are specific, testable, and easy to follow.
-   State assumptions, prerequisites, supported platforms, and
    limitations.
-   Keep essential instructions in `SKILL.md`; place detailed references
    in separate files when appropriate.
-   Use relative paths for bundled resources.
-   Make scripts predictable, documented, and safe to run.
-   Require confirmation before destructive, external, financial, or
    irreversible actions.
-   Include realistic examples and verification steps.
-   Attribute reused material and document the original license.
-   Test from a clean checkout and update the documentation when
    behavior changes.

## Choosing the right approach

  -----------------------------------------------------------------------
  Approach                            Best suited to
  ----------------------------------- -----------------------------------
  **Skills**                          Reusable, task-specific procedures
                                      and domain knowledge.

  **Prompts**                         One-off instructions or a single
                                      task's context.

  **Project instructions**            Persistent rules for a particular
                                      codebase or workspace.

  **Agents / subagents**              Delegated roles with separate
                                      objectives or tool access.

  **MCP**                             Connecting an agent to external
                                      tools, services, and data.

  **Scripts and APIs**                Deterministic operations and
                                      integrations that need explicit
                                      code.
  -----------------------------------------------------------------------

These approaches can complement one another. A skill can describe when
and how to use an MCP server or script, while project instructions
define constraints that apply throughout a repository.

## Security and responsible use

Skills are executable-adjacent instructions and may include scripts or
direct an agent to use powerful tools. Treat them as untrusted code and
configuration until reviewed.

Before installing or running a skill:

-   **Verify the source.** Prefer the original maintainer's repository
    and check its history and release activity.
-   **Read every file.** Inspect `SKILL.md`, scripts, dependencies, and
    downloaded resources.
-   **Check permissions.** Understand access to files, shell commands,
    network, credentials, and connected accounts.
-   **Protect secrets.** Never expose API keys, passwords, tokens,
    private keys, or personal data to an untrusted skill.
-   **Use least privilege.** Run with only the access required for the
    task.
-   **Test safely.** Prefer a sandbox, disposable project, or restricted
    environment.
-   **Review outputs.** Verify commands, code changes, downloads, and
    external actions before approving them.
-   **Keep dependencies current.** Check for vulnerabilities and
    unexpected changes.

A skill's presence in this list does not mean it has been
security-audited. Report suspected malicious or unsafe content through
the upstream project's security process.

## Contributing

Contributions are welcome. The goal is to keep this list useful,
navigable, accurate, and responsibly curated.

Before opening a pull request:

1.  Confirm the repository or resource is public and the link works.
2.  Add it to the most relevant category.
3.  Write a concise, factual description based on the upstream
    documentation.
4.  Identify the supported agent(s), where known.
5.  Include installation instructions only when verified from the
    source.
6.  Check the project's license and preserve attribution.
7.  Avoid duplicate entries and promotional claims.
8.  Disclose known limitations or security considerations.

### Suggested entry format

``` markdown
- **[Project or Skill Name](https://github.com/owner/repository)** — A short, factual description of its purpose. *(Agent: name; License: license, if verified.)*
```

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for the repository's
contribution process.

## Useful documentation

-   [Agent Skills specification](https://agentskills.io/)
-   [OpenAI Codex documentation](https://developers.openai.com/codex/)
-   [OpenAI Skills repository](https://github.com/openai/skills)
-   [Anthropic Skills repository](https://github.com/anthropics/skills)
-   [GitHub Copilot documentation](https://docs.github.com/en/copilot)
-   [GitHub Awesome Copilot](https://github.com/github/awesome-copilot)
-   [Gemini CLI](https://github.com/google-gemini/gemini-cli)
-   [Cursor documentation](https://docs.cursor.com/)
-   [Skills directory and CLI](https://skills.sh/)

------------------------------------------------------------------------

::: {align="center"}
**Maintained by [@999jackback](https://github.com/999jackback)**

If this list helps you, consider giving the repository a ⭐ and
contributing improvements.
:::
