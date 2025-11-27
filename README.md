# Claude Flow Blueprint - Advanced Multi-Agent Development System

> **A comprehensive development blueprint featuring Claude Flow orchestration, Universal Search Algorithm (USACF), 43+ specialized PHD Research agents, and Serena MCP integration for enterprise-grade AI-powered development.**

[![GitHub](https://img.shields.io/badge/GitHub-ChrisRoyse%2Fmyclaudeflowsetup-blue?logo=github)](https://github.com/ChrisRoyse/myclaudeflowsetup)
[![Claude Flow](https://img.shields.io/badge/Claude%20Flow-v2.0.0-purple)](https://github.com/ruvnet/claude-flow)
[![Serena MCP](https://img.shields.io/badge/Serena%20MCP-Integrated-green)](https://github.com/oraios/serena)

---

## 🙏 Credits

This blueprint is built on top of **[Claude Flow](https://github.com/ruvnet/claude-flow)** by **[Rueven Cohen (@ruvnet)](https://github.com/ruvnet)** - an innovative multi-agent orchestration framework that enables sophisticated AI-powered development workflows.

**Original Claude Flow Repository:** https://github.com/ruvnet/claude-flow

This repository extends Claude Flow with:
- Pre-configured specialized agent systems
- Universal Search Algorithm (USACF) framework
- Serena MCP integration
- Production-ready workflows and documentation

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Quick Start](#-quick-start)
- [Critical Setup Requirements](#-critical-setup-requirements)
- [Core Components](#-core-components)
- [PRD to Spec Conversion](#-prd-to-spec-conversion)
- [AI-Driven File Modularization](#-ai-driven-file-modularization)
- [Universal Search Algorithm (USACF)](#-universal-search-algorithm-usacf)
- [Specialized Agent Systems](#-specialized-agent-systems)
- [Serena MCP Integration](#-serena-mcp-integration)
- [Directory Structure](#-directory-structure)
- [Usage Guidelines](#-usage-guidelines)
- [Best Practices](#-best-practices)
- [Advanced Features](#-advanced-features)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)

---

## 🎯 Overview

This repository provides a **production-ready blueprint** for building sophisticated AI-powered development systems using:

- **Claude Flow**: Multi-agent orchestration framework with specialized agents
- **USACF**: Universal Search Algorithm for Claude Flow - advanced multi-agent search methodology
- **Serena MCP**: Semantic code analysis and IDE-like tools for precise code manipulation
- **Specialized Agent Systems**: Pre-built multi-agent systems for Business Research, Penetration Testing, PhD Research, and Strategic Engagement

### Key Features

✅ **Production-Ready Agents** - Immediately deployable specialized agents
✅ **4 Complete Multi-Agent Systems** - Business, Security, Research, and Sales workflows
✅ **Universal Search Framework** - PhD-level research and analysis methodology
✅ **Serena Integration** - Symbol-level code navigation and editing (30+ languages)
✅ **Concurrent Execution** - Parallel agent coordination for 2.8-4.4x speed improvements
✅ **Memory Coordination** - Cross-session persistence and agent memory sharing
✅ **Neural Training** - Self-learning patterns from successful operations

---

## 🚀 Quick Start

### Clone This Blueprint

This repository is a **ready-to-use blueprint** with all agents and configurations pre-configured. Simply clone and start using:

```bash
# Clone this blueprint repository
git clone https://github.com/ChrisRoyse/myclaudeflowsetup.git
cd myclaudeflowsetup

# Verify all agents are available
ls -la .claude/agents/

# You're ready to go! All agents are pre-configured
```

### Prerequisites

While this repository contains all the Claude Flow configurations, you'll need:

```bash
# Claude Code CLI (required)
npm install -g @anthropics/claude-code

# UV (required for Serena MCP)
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Setup MCP Servers

Configure the MCP servers to work with this blueprint:

```bash
# Add Claude Flow MCP (REQUIRED)
# This enables multi-agent orchestration
Tell Claude Code to make sure the AgentDB Reasoning bank and Claude Flow Memory system are working

# Add Serena MCP (REQUIRED for code analysis)
# This enables symbol-level code navigation
Tell Claude Code to get the Serena MCP server working

# Add ruv-swarm (RECOMMENDED for enhanced coordination)
If ruv-swarm isn't working, tell claude code to get it working.

# Optional: Cloud-based features
claude mcp add flow-nexus npx flow-nexus@latest mcp start
```

### Verify and Initialize Systems

After adding MCP servers, you need to ensure all systems are properly initialized and working:

#### Step 1: Ask Claude Code to Setup Core Systems

In Claude Code, prompt:

```
"Please ensure all MCP systems are properly configured:

1. Verify Serena MCP is working correctly and can access language servers
2. Initialize AgentDB for vector-based memory storage
3. Verify the memory coordination system is fully functional
4. Confirm all MCP servers (claude-flow, ruv-swarm, serena) are connected

Please run any necessary setup commands and verify everything is operational."
```

Claude Code will:
- Check Serena MCP configuration and language server availability
- Initialize AgentDB vector database for agent memory
- Set up memory namespaces and coordination
- Verify MCP server connections
- Run any required initialization commands

#### Step 2: Verify MCP Server Status

After Claude Code completes the setup, **open a new terminal** and verify:

```bash
# Check MCP server status in Claude Code
/mcp
```

You should see these servers **connected and working**:
- ✅ **claude-flow** - Multi-agent orchestration
- ✅ **ruv-swarm** - Enhanced coordination features
- ✅ **serena** - Semantic code analysis

If any server shows as disconnected or has errors, ask Claude Code to troubleshoot:

```
"The [SERVER_NAME] MCP server is not connected. Please diagnose and fix the issue."
```

#### Step 3: Test the Systems

Verify everything works with a simple test:

```
"Please test the following systems:
1. AgentDB vector storage - store and retrieve a test memory
2. Serena MCP - analyze a simple code file using symbol tools
3. Claude Flow memory coordination - verify memory namespaces

Confirm all systems are operational."
```

---

## ⚠️ Critical Setup Requirements

### 1. **ALWAYS Include claudeflow.md in Your Prompts**

**This is the most important rule.** When starting any project with Claude Code, you **MUST** reference the `docs2/claudeflow.md` configuration file in this repository:

```
"Please read \\wsl.localhost\Ubuntu-20.04\home\cabdru\claudeflowblueprint\docs2\claudeflow.md and follow all instructions within it for this project."
```

**For Windows WSL users, use the WSL path format shown above.**

**For Linux/Mac users:**
```
"Please read /home/cabdru/claudeflowblueprint/docs2/claudeflow.md and follow all instructions within it for this project."
```

**Or use relative path from your cloned repository:**
```
"Please read docs2/claudeflow.md and follow all instructions within it for this project."
```

The `docs2/claudeflow.md` file contains the **Universal Development Guide** with:
- ⚠️ **99.9% Sequential Execution Rule** - Critical coordination pattern
- 🔮 **Forward-Looking Subagent Coordination** - Future agent context
- 💾 **AgentDB ReasoningBank Integration** - Adaptive learning
- 🎯 **Correct Memory Store Syntax** - Positional arguments (prevents errors)
- 📁 **File Organization Rules** - Prevents root folder clutter
- 🚀 **Performance Optimization** - 2.8-4.4x speed improvements
- 🧠 **Memory Coordination Strategies** - Cross-agent communication

**Without claudeflow.md, you'll:**
- ❌ Use incorrect parallel execution (99.9% of tasks need sequential)
- ❌ Get "Usage: memory store" errors (wrong syntax)
- ❌ Miss forward-looking coordination (agents won't prepare for future agents)
- ❌ Lose AgentDB reasoning bank benefits
- ❌ Experience poor file organization
- ❌ Lose 2.8-4.4x performance gains

### 2. File Path Updates Required

The `agent_headers_extract.txt` file contains headers for all 43+ PhD research agents, but uses placeholder paths:

**⚠️ UPDATE THESE PATHS:**

```bash
# Example from agent_headers_extract.txt:
FILE: /home/cabdru/clag/.claude/agents/phdresearch/abstract-writer.md

# Change to YOUR project path:
FILE: /path/to/your/project/.claude/agents/phdresearch/abstract-writer.md
```

**When to use `agent_headers_extract.txt`:**
Feed this file to Claude Code when you want to understand all available agents:

```
"Please read docs2/agent_headers_extract.txt to see all available specialized agents.
Note: Update file paths to match /my/actual/project/path before using."
```

### 3. Documentation Storage Location

By default, Claude Flow stores documentation in `/docs` folder. To change this:

```
"Store all documentation in /documentation folder instead of /docs"
```

---

## 🧩 Core Components

### docs2/claudeflow.md Configuration

The `docs2/claudeflow.md` file is your **primary configuration**. It defines:

1. **Concurrent Execution Rules** - All related operations in ONE message
2. **File Organization** - Never save to root folder
3. **Agent Execution Flow** - MCP coordinates, Task tool executes
4. **Memory Coordination** - Cross-session persistence
5. **Performance Optimization** - 2.8-4.4x speed improvements

**Key Patterns from docs2/claudeflow.md:**

```javascript
// ✅ CORRECT: Batch all operations in single message
[Single Message]:
  Task("Research agent", "Analyze requirements...", "researcher")
  Task("Coder agent", "Implement features...", "coder")
  Task("Tester agent", "Create tests...", "tester")
  TodoWrite({ todos: [...8-10 todos...] })
  Write("src/file1.js", content1)
  Write("src/file2.js", content2)

// ❌ WRONG: Multiple messages
Message 1: Task("agent1")
Message 2: TodoWrite
Message 3: Write file
// Breaks parallel coordination!
```

### Universal Search Algorithm Files

**Location:** `docs2/usacfsearches.md` and `docs2/usacfsearches2.md`

These files contain the **Universal Search Algorithm for Claude Flow (USACF)** - a comprehensive framework for:

- Multi-agent decomposition
- Uncertainty quantification
- RAG integration
- Adversarial validation
- Meta-learning
- Observability and tracing

**How to Use:**

```
"Please read docs2/usacfsearches.md and docs2/usacfsearches2.md to understand
the Universal Search Algorithm framework. Use these blueprints to create a
custom search prompt for [YOUR SPECIFIC TASK]. Incorporate the most optimal
search methods from the USACF framework for this use case."
```

The USACF framework provides:
- **Section 0**: Pre-search meta-analysis (step-back prompting, ambiguity resolution)
- **Section 1**: Discovery phase (structural mapping, flow analysis)
- **Section 2**: Gap analysis (quality, performance, security gaps)
- **Section 3**: Risk analysis (FMEA, edge cases, vulnerabilities)
- **Section 4**: Synthesis (opportunity generation, optimization)
- **Section 5**: Implementation planning

---

## 📝 PRD to Spec Conversion

### What is the PRD to Spec Framework?

The **AI-Agent Specification Development Guide** (`docs2/prdtospec.md`) is a comprehensive framework for translating Product Requirements Documents (PRDs) into **machine-executable specifications** that AI agents can autonomously implement.

### Why Use PRD to Spec?

Traditional PRDs are written for humans and contain ambiguity. AI agents need:

✅ **Explicit structure** - XML tags and clear hierarchies
✅ **Traceable requirements** - Unique IDs (REQ-XXX-01) linking code to intent
✅ **Unambiguous language** - No "fast," "user-friendly," or vague terms
✅ **Edge cases documented** - What happens when things fail
✅ **Self-contained context** - Agents can pick up work with zero prior knowledge
✅ **Testable criteria** - Clear validation and acceptance tests

**Traditional approach:**
```
❌ "The login should be secure and fast"
❌ "Users should have a good experience"
❌ "Handle errors appropriately"
```

**PRD to Spec approach:**
```xml
✅ <requirement id="REQ-AUTH-01">
     Session tokens must be JWT with 24-hour expiration
   </requirement>
✅ <requirement id="REQ-AUTH-02">
     API response time must be < 200ms p95
   </requirement>
✅ <error id="ERR-AUTH-01" http_code="401">
     Invalid credentials: "Email or password is incorrect"
   </error>
```

### The Specification Hierarchy

Specifications exist in 5 levels:

```
Level 1: Constitution (immutable project rules)
  ↓
Level 2: Functional Specifications (what to build)
  ↓
Level 3: Technical Specifications (how to build it)
  ↓
Level 4: Task Specifications (atomic work units)
  ↓
Level 5: Context Files (live project state)
```

### When to Use PRD to Spec

**Use this framework when:**

✅ Starting a new feature or system from a PRD
✅ Building something AI agents will implement autonomously
✅ Need traceability from code back to requirements
✅ Working on complex projects requiring multiple AI sessions
✅ Need to onboard new team members or AI agents quickly
✅ Compliance or audit trails are important

**Don't use for:**

❌ Quick bug fixes or trivial changes
❌ Exploratory prototyping
❌ Human-only development (no AI agents involved)
❌ Projects with constantly changing requirements

### How to Use PRD to Spec

**Step 1: Read the Framework**
```
"Please read docs2/prdtospec.md to understand the AI-Agent Specification
Development Guide framework."
```

**Step 2: Analyze Your PRD**
```
"I have a PRD for [FEATURE/PROJECT]. Please use the PRD Decomposition Template
from docs2/prdtospec.md to:

1. Extract user types and journeys
2. Identify functional domains
3. Assign requirement IDs (REQ-XXX-##)
4. Surface edge cases and error states
5. Extract non-functional requirements

Store the analysis in /specs/prd-analysis.md"
```

**Step 3: Create Functional Specifications**
```
"Using the PRD analysis, create functional specifications following the
Functional Specification Template from docs2/prdtospec.md:

1. Write user stories with acceptance criteria
2. Define requirements with traceability
3. Document edge cases and error states
4. Create test plan

Store in /specs/functional/[domain].md"
```

**Step 4: Create Technical Specifications**
```
"Create technical specifications using the Technical Specification Template:

1. Define architecture with Mermaid diagrams
2. Create data models with constraints
3. Define API contracts with all response codes
4. Specify component contracts

Store in /specs/technical/[component].md"
```

**Step 5: Create Task Specifications**
```
"Break the technical spec into atomic tasks using the Task Specification Template:

1. Create task specs with pseudo-code
2. Define dependencies between tasks
3. Establish validation criteria
4. Specify test commands

Store in /specs/tasks/TASK-XXX-001.md"
```

**Step 6: Let AI Agents Implement**
```
"Implement TASK-AUTH-001 following the Agent Workflow Protocol from prdtospec.md:

1. Read .ai/activeContext.md
2. Read specs/constitution.md
3. Read the task spec
4. Propose pseudo-code
5. Wait for approval
6. Implement with tests
7. Update context files"
```

### Complete Example Workflow

```
User: "I have a PRD for a new authentication system. Help me create specs."

Step 1 - PRD Analysis:
"Read docs2/prdtospec.md section 2.2 and analyze my PRD using the
PRD Decomposition Template. Extract user types, journeys, requirements
with IDs, and edge cases."

Step 2 - Create Constitution:
"Create specs/constitution.md using the Constitution File template from
prdtospec.md section 3.2. Include our tech stack (Node.js, PostgreSQL),
coding standards, anti-patterns, and security requirements."

Step 3 - Functional Spec:
"Create specs/functional/auth.md using the Functional Specification Template
(section 3.3). Include user stories US-AUTH-01 through US-AUTH-05, requirements
REQ-AUTH-01 through REQ-AUTH-15, edge cases, and test plan."

Step 4 - Technical Spec:
"Create specs/technical/auth.md using the Technical Specification Template
(section 3.4). Include sequence diagrams, data models for User and Session
tables, API contracts for /auth/register and /auth/login, and component
contracts for AuthService."

Step 5 - Task Breakdown:
"Break the auth spec into tasks using the Task Specification Template
(section 3.5):
- TASK-AUTH-001: Registration endpoint
- TASK-AUTH-002: Login endpoint
- TASK-AUTH-003: Email verification
Each with dependencies, pseudo-code, and validation criteria."

Step 6 - Implementation:
"Implement TASK-AUTH-001 following the Agent Workflow Protocol (section 5.1).
Read the constitution, functional spec, technical spec, and task spec.
Propose pseudo-code, then implement with tests."
```

### Directory Structure for Specs

```
project-root/
├── .ai/                          # AI context and memory
│   ├── activeContext.md          # Current session state
│   ├── decisionLog.md            # Architectural decisions
│   └── progress.md               # Roadmap completion status
├── specs/
│   ├── constitution.md           # Immutable project rules
│   ├── functional/
│   │   ├── _index.md             # Manifest of all specs
│   │   ├── auth.md
│   │   ├── users.md
│   │   └── [domain].md
│   ├── technical/
│   │   ├── _index.md
│   │   ├── architecture.md
│   │   ├── data-models.md
│   │   └── api-contracts.md
│   └── tasks/
│       ├── _index.md
│       └── TASK-XXX-001.md
```

### Key Benefits

**For AI Agents:**
- 🎯 Zero ambiguity - every requirement is explicit
- 🔗 Full traceability - REQ IDs link code to business intent
- 💾 Context persistence - work continues across sessions
- ✅ Self-verification - built-in validation criteria

**For Development Teams:**
- 📊 Clear roadmap - task breakdown with dependencies
- 🔍 Audit trail - every decision documented
- 🤝 Easy onboarding - comprehensive documentation
- 🧪 Testability - acceptance criteria pre-defined

**For Project Success:**
- ⚡ Faster development - AI agents work autonomously
- 🎨 Consistency - constitution enforces standards
- 🛡️ Quality gates - human review at critical points
- 📈 Scalability - methodology works for any project size

### Templates Quick Reference

**Minimal Viable Spec** (Simple features):
```xml
<feature_spec id="FEAT-001">
  <title>Feature Name</title>
  <requirements>
    <req id="REQ-001">Specific requirement</req>
  </requirements>
  <acceptance_criteria>
    - Given X, when Y, then Z
  </acceptance_criteria>
</feature_spec>
```

**Bug Fix Spec**:
```xml
<bug_spec id="BUG-001">
  <current_behavior>What's broken</current_behavior>
  <expected_behavior>What should happen</expected_behavior>
  <reproduction_steps>How to reproduce</reproduction_steps>
  <root_cause>Why it's broken</root_cause>
  <fix_requirements>How to fix it</fix_requirements>
</bug_spec>
```

### Common Pitfalls (from Appendix B)

Before finalizing specs, check:

- [ ] No vague language ("fast" → "< 200ms p95")
- [ ] Failure modes documented for all operations
- [ ] Valid input ranges specified
- [ ] Permissions/authorization requirements clear
- [ ] Empty/null data behavior defined
- [ ] All requirements have test cases
- [ ] Time zones specified where relevant
- [ ] Internationalization addressed

### Integration with Claude Flow

The PRD to Spec framework integrates seamlessly with this blueprint:

```
"Create specifications from my PRD following docs2/prdtospec.md, then
implement using:

1. phdresearch agents for documentation quality
2. business-research agents for requirement validation
3. USACF framework for gap analysis
4. Serena MCP for precise implementation
5. Claude Flow for agent coordination

Store specs in /specs/ and implementation in /src/"
```

---

## 🔧 AI-Driven File Modularization

### What is File Modularization?

The **AI-Driven File Modularization Prompt** (`docs2/modulateprompt.md`) is a comprehensive, language-agnostic framework for refactoring large, monolithic files into clean, maintainable modular architectures while maintaining **100% backwards compatibility**.

### Why Use File Modularization?

Large files become unmaintainable over time. This framework helps you:

✅ **Enforce size limits** - Every resulting file stays under configurable line limit (default: 500 lines)
✅ **Maintain backwards compatibility** - All existing imports and APIs continue to work
✅ **Improve code quality** - Lower complexity, higher cohesion, better testability
✅ **Language-agnostic** - Works with 15+ languages (Python, TypeScript, Go, Rust, Java, etc.)
✅ **Systematic approach** - 5-phase process from analysis to validation
✅ **Zero breaking changes** - Existing tests pass without modification

### Supported Languages

Python, TypeScript/JavaScript, Go, Rust, Java, Kotlin, Ruby, PHP, C#, Swift, Scala, Elixir, Clojure, Haskell, C/C++

### When to Use Modularization

**Use this framework when:**

✅ You have a file exceeding your team's line limit (typically 500+ lines)
✅ A file contains multiple responsibilities (violates Single Responsibility Principle)
✅ Code review feedback identifies complexity or maintenance concerns
✅ Onboarding new developers struggle to understand a large file
✅ Testing requires complex setup due to mixed concerns
✅ Refactoring is needed but you can't afford breaking changes

**Don't use for:**

❌ Files already under the line limit and well-organized
❌ Prototype or throwaway code
❌ Files with a single, cohesive responsibility
❌ When you can afford breaking changes (simpler refactoring available)

### The 5-Phase Process

```
Phase 1: Deep Analysis (Understanding)
  └─ File analysis, dependencies, usage, complexity metrics

Phase 2: Modularization Strategy (Planning)
  └─ Identify cohesive modules, design structure, ensure compatibility

Phase 3: Implementation Plan (Execution)
  └─ Step-by-step refactoring with test checkpoints

Phase 4: Output Specification
  └─ Generate analysis docs, architecture diagrams, test suites

Phase 5: Quality Assurance
  └─ Verify metrics, backwards compatibility, and improvements
```

### How to Use Modularization

**Step 1: Identify Large Files**
```bash
# Find files over 500 lines (Unix/Linux/Mac)
find . -name "*.py" -exec wc -l {} + | sort -rn | head -20

# PowerShell (Windows)
Get-ChildItem -Recurse -Filter "*.py" | ForEach-Object {
  [PSCustomObject]@{Lines=(Get-Content $_.FullName).Count; File=$_.FullName}
} | Sort-Object Lines -Descending | Select-Object -First 20
```

**Step 2: Configure the Prompt**
```
"Read docs2/modulateprompt.md and refactor the following file:

TARGET_FILE: src/services/user_service.py
MAX_LINES: 500
LANGUAGE: python
TEST_COMMAND: pytest
LINT_COMMAND: pylint
TYPE_CHECK_COMMAND: mypy

Follow all 5 phases and ensure 100% backwards compatibility."
```

**Step 3: Execute Refactoring**

The AI will:
1. Analyze the file's purpose, dependencies, and usage
2. Design a modular structure following language conventions
3. Create a step-by-step refactoring plan with test checkpoints
4. Implement the refactoring incrementally
5. Validate backwards compatibility and improvements

**Step 4: Review Outputs**

You'll receive:
- **Analysis document** - Understanding of current state
- **Architecture document** - Module breakdown with diagrams
- **Refactoring plan** - Step-by-step implementation guide
- **Code implementation** - All new modular files
- **Test suite** - Backwards compatibility and unit tests
- **Validation report** - Before/after metrics

### Example: Modularizing a 1200-line File

**Before:**
```
src/api/routes/classify.py  (1200 lines) ❌
```

**After:**
```
src/api/routes/classify/
├── __init__.py                      # ~50 lines  ✅ Facade
├── router.py                        # ~150 lines ✅ Routes
├── handlers/
│   ├── __init__.py                  # ~15 lines  ✅
│   ├── primary_handler.py           # ~200 lines ✅ Main logic
│   └── validation_handler.py        # ~100 lines ✅ Validation
├── services/
│   ├── __init__.py                  # ~10 lines  ✅
│   ├── classification_service.py    # ~300 lines ✅ Business logic
│   └── preprocessing_service.py     # ~200 lines ✅ Data prep
├── repositories/
│   ├── __init__.py                  # ~10 lines  ✅
│   └── data_repository.py           # ~180 lines ✅ Data access
├── models/
│   ├── __init__.py                  # ~20 lines  ✅
│   ├── request_models.py            # ~150 lines ✅ Input models
│   └── response_models.py           # ~120 lines ✅ Output models
└── utils/
    ├── __init__.py                  # ~10 lines  ✅
    └── helpers.py                   # ~200 lines ✅ Utilities

All files under 500 lines ✅
Backwards compatible ✅
All tests passing ✅
```

### Backwards Compatibility Guarantee

**Old imports still work:**
```python
# OLD (still works - facades to new modules)
from src.api.routes.classify import classify_image, validate_input

# NEW (preferred - direct module access)
from src.api.routes.classify.handlers import classify_image
from src.api.routes.classify.utils import validate_input
```

**The original file becomes a facade:**
```python
# src/api/routes/classify/__init__.py (now ~50 lines)
from .handlers.primary_handler import classify_image
from .utils.helpers import validate_input

__all__ = ['classify_image', 'validate_input']
```

### Quality Improvements

**Code Quality Metrics:**
- **Modularity:** 1 file → 15 files, each < 500 lines
- **Complexity:** Cyclomatic complexity reduced by 40%
- **Testability:** Unit tests increased by 200%
- **Maintainability:** Clear separation of concerns

**Verified by:**
- ✅ All existing tests pass without modification
- ✅ No performance regression
- ✅ Linting passes
- ✅ Type checking passes
- ✅ Code coverage maintained or increased

### Language-Specific Conventions

The framework adapts to your language's idioms:

**Python:** Uses `__init__.py` for package structure
**TypeScript/JavaScript:** Uses `index.ts` for barrel exports
**Go:** Uses package-level files (no subdirectories for small modules)
**Rust:** Uses `mod.rs` and `pub use` for re-exports
**Java/Kotlin:** Uses package structure with proper visibility

### Integration with Claude Flow

Use modularization with agent coordination:

```
"Read docs2/modulateprompt.md and refactor src/large_file.py.

Use these agents:
1. code-analyzer - Analyze file structure and dependencies
2. system-architect - Design modular architecture
3. coder - Implement refactoring step-by-step
4. tester - Validate backwards compatibility
5. reviewer - Review code quality improvements

Store all outputs in /docs/modularization/ and ensure all files under 500 lines."
```

### Success Criteria

The refactoring is successful when:

1. ✅ Original file reduced to < 100 lines (facade only)
2. ✅ All new files under configured line limit (default: 500)
3. ✅ Zero breaking changes (100% backwards compatible)
4. ✅ All tests pass (existing + new tests)
5. ✅ Code quality metrics improved
6. ✅ No performance degradation
7. ✅ Clear module boundaries
8. ✅ Documentation updated
9. ✅ Team review approved
10. ✅ Can deploy without downtime

### Quick Start Example

```
"I have a 1500-line Python file that needs refactoring.

Please:
1. Read docs2/modulateprompt.md
2. Analyze src/services/large_service.py
3. Design a modular structure with max 500 lines per file
4. Create refactoring plan with test checkpoints
5. Implement the refactoring ensuring backwards compatibility
6. Generate all documentation and validation reports

Configuration:
- MAX_LINES: 500
- TEST_COMMAND: pytest
- LINT_COMMAND: pylint
- TYPE_CHECK_COMMAND: mypy

Store outputs in /docs/modularization/large_service/"
```

---

## 🔍 Universal Search Algorithm (USACF)

### What is USACF?

The **Universal Search Algorithm for Claude Flow** is a PhD-level research methodology that treats any analysis as a memory-coordinated, multi-dimensional search through state space.

### Core Principles

1. **Multi-Agent Decomposition** - Parallel specialized subagents with synthesizers
2. **Uncertainty Quantification** - Confidence scoring (0-100%) for all findings
3. **RAG Integration** - Web search for grounded research
4. **Adversarial Validation** - Red team critique of all findings
5. **Meta-Learning** - Self-improving prompts and recursive optimization
6. **Observability** - Full decision tracing and instrumentation
7. **Version Control** - Source attribution and change tracking

### When to Use USACF

Use USACF for:
- ✅ Complex codebase analysis
- ✅ Business strategy research
- ✅ Security audits and penetration testing
- ✅ Academic research and literature reviews
- ✅ Competitive intelligence gathering
- ✅ System architecture planning

### Creating Custom Search Prompts

**Step 1:** Read the USACF blueprints:
```
"Read docs2/usacfsearches.md and docs2/usacfsearches2.md"
```

**Step 2:** Identify relevant search methods for your task:
```
"From the USACF framework, identify the optimal search methods for:
[YOUR SPECIFIC TASK - e.g., 'analyzing a React codebase for performance issues']"
```

**Step 3:** Build your custom prompt:
```
"Create a custom search prompt combining:
- Step-back prompting (Section 0.1)
- Structural mapping (Section 1.1)
- Performance gap analysis (Section 2.1)
- Risk analysis (Section 2.2)
Store all findings with confidence scores and sources."
```

### USACF Agent Coordination

The USACF framework uses these agent patterns:

**Discovery Swarm:**
- `structural-mapper` - Component and hierarchy mapping
- `flow-analyst` - Data/control flow tracing
- `dependency-tracker` - Dependency network analysis
- `critical-path` - Performance bottleneck identification

**Analysis Swarm:**
- `gap-hunters` (7 types) - Quality, performance, structural, resource, capability, security, UX gaps
- `risk-analysts` - FMEA, edge cases, vulnerabilities
- `benchmark-analysts` - Industry standards comparison

**Synthesis Swarm:**
- `opportunity-generators` - Quick wins, strategic, transformational improvements
- `optimizers` - Pareto optimization, constraint solving

**Meta Swarm:**
- `orchestrator` - Adaptive coordination
- `uncertainty-quantifier` - Confidence analysis
- `adversarial-reviewer` - Red team critique
- `validator` - Quality gate keeper

---

## 🤖 Specialized Agent Systems

This repository includes **4 complete multi-agent systems** in `.claude/agents/`:

### 1. Business Research (`/business-research`)

**Purpose:** Strategic business positioning and competitive analysis

**Agents:**
- `strategic-researcher` - Web research and data collection
- `problem-validator` - Burning problem validation and scoring
- `competitive-intelligence` - Competitive landscape mapping
- `pattern-analyst` - Cross-study pattern identification
- `knowledge-gap-identifier` - Gap detection and research planning
- `synthesis-specialist` - Cross-analysis integration
- `positioning-strategist` - Positioning statement development
- `documentation-specialist` - File structure and executive summaries
- `company-intelligence-researcher` - Deep company analysis
- `leadership-profiler` - Decision-maker profiling
- `conversation-script-writer` - Dialogue engineering
- `sales-enablement-specialist` - Sales tools and playbooks
- `strategic-positioning-analyst` - Value proposition customization
- `executive-brief-writer` - Executive-level synthesis

**Specialized Prompts:**
- `business_positioning_research_various burning problems.md` - Multi-arc research orchestration

**When to Use:**
```
"I need to research [COMPANY/MARKET]. Please use the business-research agents
in .claude/agents/business-research/. Start with the strategic-researcher agent
and coordinate with problem-validator and competitive-intelligence agents."
```

### 2. Penetration Testing (`/pentestsystem`)

**Purpose:** Security testing, vulnerability assessment, and remediation

**Agents:**
- `passive-reconnaissance-specialist` - OSINT collection
- `active-reconnaissance-specialist` - Port scanning, service detection
- `vulnerability-landscape-mapper` - Comprehensive vulnerability discovery
- `web-application-security-tester` - OWASP Top 10 testing
- `network-security-tester` - Network infrastructure testing
- `cloud-infrastructure-security-tester` - AWS/Azure/GCP security
- `exploitation-strategy-planner` - Exploitation workflow planning
- `active-exploitation-specialist` - Ethical exploitation
- `post-exploitation-specialist` - Post-compromise activities
- `comprehensive-risk-scorer` - CVSS v3.1 scoring
- `remediation-prioritizer` - Prioritized remediation roadmaps
- `compensating-controls-analyst` - Temporary mitigation strategies
- `technical-report-writer` - Technical security reports
- `executive-report-writer` - Executive summary reports
- `retest-verification-specialist` - Remediation verification
- `security-metrics-analyst` - Security metrics and KPIs

**When to Use:**
```
"Conduct penetration testing on [TARGET]. Use agents from
.claude/agents/pentestsystem/. Start with passive-reconnaissance-specialist,
then proceed through the testing phases. Ensure authorization is documented."
```

### 3. PhD Research (`/phdresearch`)

**Purpose:** Academic research, literature reviews, and publication-quality writing

**43 Specialized Agents** including:
- `abstract-writer` - Publication-quality abstracts
- `literature-review-writer` - Comprehensive literature reviews
- `methodology-writer` - Research methodology documentation
- `results-writer` - Results section with statistical rigor
- `discussion-writer` - Discussion and interpretation
- `conclusion-writer` - Synthesis and forward-looking conclusions
- `apa-citation-specialist` - APA 7th edition formatting
- `systematic-reviewer` - PRISMA-compliant systematic reviews
- `meta-learning-orchestrator` - Research planning and coordination
- `gap-hunter` - Multi-dimensional gap analysis
- `risk-analyst` - FMEA and risk assessment
- `adversarial-reviewer` - Red team critique
- `confidence-quantifier` - Uncertainty quantification
- `step-back-analyzer` - Principle extraction
- `ambiguity-clarifier` - Terminology resolution
- `source-tier-classifier` - Source quality assessment
- `bias-detector` - Systematic bias identification
- `evidence-synthesizer` - Cross-study synthesis
- `quality-assessor` - Study quality appraisal
- And 24 more specialized research agents...

**When to Use:**
```
"I'm conducting academic research on [TOPIC]. Use the phdresearch agents from
.claude/agents/phdresearch/. Start with literature-mapper and systematic-reviewer,
then coordinate with gap-hunter and synthesis agents. Ensure all citations follow
APA 7th edition."
```

### 4. Strategic Engagement (SPRINKLE) (`/sprinkle`)

**Purpose:** Strategic sales enablement and relationship management

**Agents:**
- `research-orchestrator` - Master orchestrator for strategic research
- `company-intelligence-researcher` - Deep company analysis
- `leadership-profiler` - Decision-maker intelligence
- `strategic-positioning-analyst` - Value proposition customization
- `conversation-script-writer` - Dialogue engineering
- `sales-enablement-specialist` - Sales tools and playbooks
- `executive-brief-writer` - Executive synthesis

**When to Use:**
```
"Prepare for strategic meeting with [COMPANY]. Use sprinkle agents from
.claude/agents/sprinkle/. Generate company intelligence, leadership profiles,
conversation scripts, and executive briefs."
```

---

## 🔧 Serena MCP Integration

### What is Serena?

**Serena** is a powerful coding agent toolkit that provides **IDE-like semantic code analysis** for 30+ programming languages. It enables symbol-level code navigation and editing instead of crude text searches.

### Why Use Serena?

**Without Serena:**
```
❌ Read entire files
❌ grep-like text searches
❌ String-based replacements
❌ No code structure awareness
```

**With Serena:**
```
✅ Symbol-level navigation (find_symbol)
✅ Precise code editing (replace_symbol_body)
✅ Reference tracking (find_referencing_symbols)
✅ LSP-powered analysis
✅ 30+ language support
```

### Supported Languages

Python, JavaScript, TypeScript, Go, Rust, Java, C#, C/C++, PHP, Ruby, Elixir, Kotlin, Swift, Scala, Clojure, Perl, Bash, Terraform, and 12 more.

### Key Serena Tools

1. **`mcp__serena__find_symbol`** - Find functions, classes, methods by name path
2. **`mcp__serena__find_referencing_symbols`** - Find all references to a symbol
3. **`mcp__serena__replace_symbol_body`** - Replace function/class implementation
4. **`mcp__serena__insert_after_symbol`** - Insert code after a symbol
5. **`mcp__serena__get_symbols_overview`** - Get file structure overview
6. **`mcp__serena__search_for_pattern`** - Regex search across codebase
7. **`mcp__serena__rename_symbol`** - Refactor symbol names across codebase

### Serena Best Practices

**1. Always Get Overview First:**
```
Use mcp__serena__get_symbols_overview before diving into specific symbols
```

**2. Use Symbol Names, Not File Paths:**
```
✅ find_symbol("MyClass/myMethod")
❌ find_symbol("src/modules/MyClass.ts/myMethod")
```

**3. Leverage Reference Tracking:**
```
Use find_referencing_symbols to understand impact before refactoring
```

**4. Prefer Symbol-Level Operations:**
```
✅ replace_symbol_body for function changes
❌ regex replacements for structured code
```

### Serena Configuration

Serena is configured via `.serena/project.yml` and supports:
- **Contexts** - Tool sets for different environments
- **Modes** - Operational patterns (planning, editing, interactive)
- **Memory** - Project knowledge persistence in `.serena/memories/`

### When to Use Serena vs USACF

**Use Serena for:**
- Code navigation and editing
- Refactoring operations
- Symbol-level analysis
- Language-specific operations

**Use USACF for:**
- High-level system analysis
- Multi-dimensional gap analysis
- Strategic planning
- Research and documentation

**Use Both for:**
- Comprehensive codebase audits
- Architecture migration planning
- Security vulnerability analysis
- Performance optimization

---

## 📁 Directory Structure

```
claudeflowblueprint/
├── README.md                    # This file
├── CLAUDE.md                    # Original Claude Code configuration (legacy)
├── docs2/                       # ⚠️ CRITICAL DOCUMENTATION
│   ├── claudeflow.md            # ⚠️ INCLUDE IN ALL PROMPTS - Universal Development Guide
│   ├── usacfsearches.md         # ⚠️ USACF framework part 1
│   ├── usacfsearches2.md        # ⚠️ USACF framework part 2
│   └── agent_headers_extract.txt # ⚠️ All agent headers (UPDATE PATHS)
├── .claude/                     # Claude Code configuration
│   ├── agents/                  # All specialized agents
│   │   ├── business-research/   # Strategic business agents
│   │   ├── pentestsystem/       # Security testing agents
│   │   ├── phdresearch/         # Academic research agents (43 agents)
│   │   ├── sprinkle/            # Strategic engagement agents
│   │   ├── core/                # Core utility agents
│   │   ├── development/         # Development agents
│   │   ├── testing/             # Testing agents
│   │   └── [30+ other categories]
│   ├── hooks/                   # Pre/post operation hooks
│   └── settings.json            # Claude Code settings
├── docs/                        # Default documentation output
├── serena/                      # Serena MCP codebase
│   ├── README.md                # Serena documentation
│   ├── CLAUDE.md                # Serena-specific configuration
│   └── src/                     # Serena source code
├── config/                      # Additional configurations
├── coordination/                # Swarm coordination files
├── memory/                      # Agent memory storage
└── .swarm/                      # Swarm state database
```

### Key Directories

**`.claude/agents/`** - specialized agents organized by category
- Must reference when using specialized agents
- Update paths in `agent_headers_extract.txt` to match your project

**`docs2/`** - USACF search algorithm documentation
- Read before creating custom search prompts
- Contains complete multi-agent search methodology

**`serena/`** - Serena MCP integration
- Provides semantic code analysis
- 30+ language support via LSP

**`docs/`** - Default output location
- Claude Flow stores docs here by default
- Override with explicit instructions

---

## 📖 Usage Guidelines

### Starting a New Project

**1. Reference docs2/claudeflow.md:**
```
"Read docs2/claudeflow.md and follow all instructions for this project."
```

**2. Choose Your Agent System:**
```
"Use agents from .claude/agents/[business-research|pentestsystem|phdresearch|sprinkle]"
```

**3. Create Custom Search Prompt (if needed):**
```
"Read docs2/usacfsearches.md and create a custom search prompt for
analyzing [YOUR TASK] using optimal USACF methods."
```

**4. Specify Output Location:**
```
"Store all documentation in /output/docs instead of /docs"
```

### Using Specialized Agents

**Business Research Example:**
```
I need to analyze the competitive landscape for [PRODUCT].

Please:
1. Read docs2/claudeflow.md for execution patterns
2. Use agents from .claude/agents/business-research/
3. Start with strategic-researcher to gather data
4. Use competitive-intelligence to map alternatives
5. Coordinate with problem-validator to score pain points
6. Use synthesis-specialist to integrate findings
7. Store results in /research/competitive-analysis/
```

**PhD Research Example:**
```
I'm writing a systematic literature review on [TOPIC].

Please:
1. Read docs2/claudeflow.md for concurrent execution
2. Use agents from .claude/agents/phdresearch/
3. Start with literature-mapper (read docs2/usacfsearches.md for methodology)
4. Use systematic-reviewer for PRISMA compliance
5. Coordinate with gap-hunter and pattern-analyst
6. Use literature-review-writer for final synthesis
7. Ensure all citations use apa-citation-specialist
8. Store output in /research/literature-review/
```

**Penetration Testing Example:**
```
Conduct authorized penetration test on [AUTHORIZED TARGET].

Please:
1. Read docs2/claudeflow.md for execution coordination
2. Use agents from .claude/agents/pentestsystem/
3. Start with passive-reconnaissance-specialist
4. Progress through active-reconnaissance-specialist
5. Use vulnerability-landscape-mapper for scanning
6. Coordinate with exploitation-strategy-planner
7. Generate reports with technical-report-writer and executive-report-writer
8. Store all findings in /security/pentest-[DATE]/

⚠️ AUTHORIZATION CONFIRMED: [AUTHORIZATION DETAILS]
```

### Agent Coordination Patterns

**Pattern 1: Parallel Independent Agents (Single Message)**
```javascript
// Use when agents don't depend on each other
[Message 1]:
  Task("research-agent", "Research requirements", "researcher")
  Task("data-agent", "Collect data", "data-collector")
  Task("analysis-agent", "Analyze metrics", "analyst")
```

**Pattern 2: Sequential Dependent Agents (Multiple Messages)**
```javascript
// Use when agents need previous outputs
[Message 1]:
  Task("discovery-agent", "Map structure", "structural-mapper")

[Message 2 - after discovery complete]:
  Task("gap-agent", "Find gaps in structure", "gap-hunter")

[Message 3 - after gap analysis]:
  Task("synthesis-agent", "Synthesize findings", "synthesizer")
```

**Pattern 3: Hybrid Execution**
```javascript
// Phase 1: Parallel independent discovery
[Message 1]:
  Task("structural-mapper", "Map components", "structural-mapper")
  Task("flow-analyst", "Trace flows", "flow-analyst")
  Task("dependency-tracker", "Map dependencies", "dependency-tracker")

// Phase 2: Sequential synthesis (after Phase 1)
[Message 2]:
  Task("gap-hunter", "Analyze gaps from all discoveries", "gap-hunter")

[Message 3]:
  Task("synthesizer", "Create final report", "synthesizer")
```

### Understanding Agent Headers

The `docs2/agent_headers_extract.txt` file contains metadata for all 43 PhD research agents:

**Format:**
```yaml
FILE: /path/to/agent.md

---
name: agent-name
type: agent-type
color: "#HEX"
description: Agent purpose and capabilities
capabilities:
  - capability_1
  - capability_2
priority: critical|high|medium|low
hooks:
  pre: |
    Pre-operation bash commands
  post: |
    Post-operation bash commands
---
```

**When to Feed to Claude:**
```
"Read docs2/agent_headers_extract.txt to understand all available phdresearch agents.
Note: Update file paths from /home/cabdru/clag/ to /my/actual/path/ before using."
```

---

## 💡 Best Practices

### 1. Always Include docs2/claudeflow.md

**DO THIS:**
```
"Read and follow docs2/claudeflow.md for this project."
```

**NOT THIS:**
```
"Help me with this project."
```

### 2. Batch Operations in Single Messages

**DO THIS:**
```javascript
[Single Message]:
  Task("agent1", ..., "type1")
  Task("agent2", ..., "type2")
  TodoWrite({ todos: [...5+ todos...] })
  Write("file1.js", content1)
  Write("file2.js", content2)
  Bash("mkdir -p src/{components,utils}")
```

**NOT THIS:**
```javascript
[Message 1]: Task("agent1")
[Message 2]: Task("agent2")
[Message 3]: TodoWrite
[Message 4]: Write file
```

### 3. Organize Files Properly

**DO THIS:**
```
/src/components/Header.tsx
/tests/Header.test.tsx
/docs/api-reference.md
/config/eslint.config.js
```

**NOT THIS:**
```
/Header.tsx           ❌ Root folder
/test.tsx             ❌ Root folder
/README.md            ❌ Working file in root
/notes.txt            ❌ Root folder clutter
```

### 4. Use Appropriate Agent Systems

**Business Strategy** → `business-research` agents
**Security Testing** → `pentestsystem` agents
**Academic Research** → `phdresearch` agents
**Sales Enablement** → `sprinkle` agents
**Code Analysis** → Serena MCP tools
**Complex Analysis** → USACF framework

### 5. Document Agent Coordination

```
"Coordinate these agents:
1. strategic-researcher (parallel with competitive-intelligence)
2. problem-validator (after step 1)
3. synthesis-specialist (after step 2)

Use Claude Flow memory for inter-agent communication."
```

### 6. Leverage Memory Coordination

```bash
# Agents store findings in memory
npx claude-flow memory store --namespace "research/findings" --key "gap-analysis"

# Other agents retrieve findings
npx claude-flow memory retrieve --key "research/findings/gap-analysis"
```

### 7. Use Confidence Scoring (USACF)

```
"For all findings, include:
- Confidence: 0-100%
- Sources: [URL1, URL2]
- Uncertainty: What could be wrong?
- Research needed: If confidence < 70%"
```

---

## 🎯 Advanced Features

### Neural Training

Claude Flow can train neural patterns from successful operations:

```bash
# Enable neural training
npx claude-flow@alpha hooks post-edit --memory-key "successful-pattern"

# View learned patterns
npx claude-flow@alpha neural patterns --pattern "all"
```

### Performance Monitoring

Track swarm performance and bottlenecks:

```bash
# Monitor swarm health
npx claude-flow@alpha swarm status

# Analyze bottlenecks
npx claude-flow@alpha performance report --timeframe "24h"

# Token usage analysis
npx claude-flow@alpha token usage --operation "all"
```

### GitHub Integration

Integrate with GitHub workflows:

```bash
# Repository analysis
npx claude-flow@alpha github repo-analyze --repo "owner/repo"

# PR management
npx claude-flow@alpha github pr-manage --repo "owner/repo" --action "review"

# Code review automation
npx claude-flow@alpha github code-review --repo "owner/repo" --pr 123
```

### Custom Agent Creation

Create your own specialized agents:

```yaml
# .claude/agents/custom/my-agent.md
---
name: my-custom-agent
type: specialist
description: My specialized agent for [PURPOSE]
capabilities:
  - capability_1
  - capability_2
priority: high
hooks:
  pre: |
    echo "Starting my-custom-agent"
    npx claude-flow memory retrieve --key "context/data"
  post: |
    npx claude-flow memory store --namespace "output" --key "results"
---
```

### Memory Namespaces

Organize agent memory efficiently:

```bash
# Search phase memory
search/meta/principles
search/discovery/structural
search/gaps/quality
search/risks/fmea

# Business research memory
business/competitive/landscape
business/problems/validated
business/positioning/strategy

# Security testing memory
security/recon/passive
security/vulnerabilities/findings
security/remediation/priorities
```

---

## 🔧 Troubleshooting

### Issue: MCP Servers Not Connected

**Problem:** MCP servers show as disconnected when running `/mcp` command

**Solution:**
```bash
# Step 1: Check MCP server status
/mcp

# Step 2: If servers are disconnected, ask Claude Code:
"Please check why the [SERVER_NAME] MCP server is disconnected and reconnect it."

# Step 3: Verify MCP configuration
cat ~/.config/claude/mcp.json

# Step 4: Restart Claude Code if needed
# Close and reopen Claude Code, then verify with /mcp
```

**Common causes:**
- MCP server process crashed
- Incorrect server command in configuration
- Missing dependencies (UV for Serena, Node.js for Claude Flow)
- Firewall blocking local connections

### Issue: AgentDB Not Initialized

**Problem:** Memory storage or AgentDB vector database not working

**Solution:**
```
Ask Claude Code:

"Please initialize AgentDB and verify the memory system:
1. Check if .agentdb/ directory exists
2. Initialize AgentDB vector storage
3. Test storing and retrieving a sample memory
4. Verify all memory namespaces are accessible

Show me the results of each step."
```

### Issue: Serena Language Servers Not Working

**Problem:** Serena can't analyze code or symbol tools fail

**Solution:**
```
Ask Claude Code:

"Please verify Serena MCP is properly configured:
1. Check Serena MCP server connection
2. Verify language server availability for [LANGUAGE]
3. Test symbol analysis on a sample file
4. Initialize any missing language servers

Report any errors and fix them."
```

**Common languages and their servers:**
- Python: pyright or jedi-language-server
- JavaScript/TypeScript: typescript-language-server
- Go: gopls
- Rust: rust-analyzer
- Java: eclipse-jdt-ls

### Issue: Agents Not Found

**Problem:** Claude Code can't find agents in `.claude/agents/`

**Solution:**
```
1. Verify .claude/agents/ directory exists
2. Check agent file format (.md files with YAML frontmatter)
3. Update paths in agent_headers_extract.txt if needed
4. Explicitly reference: "Use agents from .claude/agents/phdresearch/"
```

### Issue: Serena Tools Not Working

**Problem:** Serena MCP tools not available

**Solution:**
```bash
# Verify Serena is installed
claude mcp list

# Reinstall Serena MCP
claude mcp remove serena
claude mcp add serena uvx --from git+https://github.com/oraios/serena serena start-mcp-server

# Check language server support
uvx --from git+https://github.com/oraios/serena serena start-mcp-server --help
```

### Issue: Poor Performance

**Problem:** Agents running slowly or sequentially

**Solution:**
```
1. Check docs2/claudeflow.md for concurrent execution patterns
2. Batch ALL independent operations in ONE message
3. Use parallel Task tool calls
4. Verify MCP coordination is enabled
5. Enable performance monitoring:
   npx claude-flow@alpha performance report
```

### Issue: Files in Root Directory

**Problem:** Working files saved to project root

**Solution:**
```
"NEVER save files to root directory. Use:
- /src for source code
- /tests for tests
- /docs for documentation
- /config for configuration

Reorganize any files currently in root."
```

### Issue: Lost Context Between Sessions

**Problem:** Agents forgetting previous work

**Solution:**
```bash
# Enable session persistence
npx claude-flow@alpha hooks session-restore --session-id "project-main"

# Store critical context
npx claude-flow memory store --namespace "session/context" --key "current-state"

# Retrieve on restart
npx claude-flow memory retrieve --key "session/context/current-state"
```

---

## 🤝 Contributing

### Reporting Issues

1. Check existing issues at [GitHub Issues](https://github.com/ChrisRoyse/myclaudeflowsetup/issues)
2. Provide reproduction steps
3. Include Claude Code version, OS, and error messages
4. Attach relevant log files

### Suggesting Improvements

- **New Agents:** Submit agent definitions following YAML format
- **USACF Enhancements:** Propose improvements to search methodology
- **Documentation:** Fix errors or add clarifications
- **Examples:** Share successful agent coordination patterns

### Pull Request Guidelines

1. Update `agent_headers_extract.txt` if adding agents
2. Document new features in README
3. Test with Claude Code and Serena MCP
4. Follow existing code style and structure

---

## 📚 Additional Resources

### Official Documentation

- **Claude Flow (Original):** [GitHub](https://github.com/ruvnet/claude-flow) by [@ruvnet](https://github.com/ruvnet)
  - Original multi-agent orchestration framework
  - Comprehensive documentation and examples
  - Active development and community support
- **Serena MCP:** [GitHub](https://github.com/oraios/serena) | [Docs](https://oraios.github.io/serena/)
- **Claude Code:** [Anthropic Docs](https://claude.com/claude-code)

### Community

- **Discord:** Join Claude Flow community
- **Reddit:** r/ClaudeAI, r/ClaudeCode
- **Twitter:** Follow @anthropics

### Related Projects

- **Flow Nexus:** Cloud-based swarm deployment
- **AgentDB:** Vector database for agent memory
- **Hive Mind:** Advanced collective intelligence

---

## 📄 License

This blueprint is provided as-is for educational and development purposes. Individual components may have their own licenses:

- **Claude Flow:** MIT License
- **Serena MCP:** MIT License
- **This Blueprint:** MIT License

---

## 🙏 Acknowledgments

### Primary Attribution

This blueprint is built upon **[Claude Flow](https://github.com/ruvnet/claude-flow)** created by **Rueven Cohen ([@ruvnet](https://github.com/ruvnet))**.

Claude Flow is an innovative multi-agent orchestration framework that revolutionizes AI-powered development through:
- Hierarchical swarm coordination
- Memory-based agent communication
- Neural pattern learning
- Performance optimization (2.8-4.4x improvements)
- 84.8% SWE-Bench solve rate

**Original Repository:** https://github.com/ruvnet/claude-flow
**Creator:** Rueven Cohen - [@ruvnet](https://github.com/ruvnet)

### Additional Technologies

- **Serena/Oraios Team** - Semantic code analysis MCP server with LSP integration
- **Anthropic** - Claude Code CLI and Claude API
- **Open Source Community** - Language server implementations and contributions

---

## 📞 Support

For support and questions:

1. **Read docs2/claudeflow.md** - Most questions answered here
2. **Check USACF docs** - `docs2/usacfsearches.md`
3. **Review agent headers** - `docs2/agent_headers_extract.txt`
4. **GitHub Issues** - Report bugs and request features
5. **Community Forums** - Ask questions and share patterns

---

**Remember:** Always include `docs2/claudeflow.md` in your prompts and update file paths in `agent_headers_extract.txt` to match your project structure.

**Happy Building! 🚀**


