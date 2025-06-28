# Project Vault

A project management system using Obsidian with atomic notes for clear, organized project tracking and AI-assisted project creation.

## Core Principles

**Project Vault** transforms complex projects into manageable, interconnected atomic pieces while maintaining clear oversight through a centralized dashboard.

### 1. Atomic Principle
Each note contains exactly one clear concept - no exceptions.

### 2. Flat Hierarchy
All content lives in `Notes/` folder. No subfolders, ever.

### 3. Dashboard-Centric Management
Everything flows through the `Project Vault Dashboard` with four sections:
- **Inbox** - Notes that need processing (**keep empty - process or remove items regularly**)
- **Active Projects** - Currently working on
- **Projects on Hold** - Temporarily paused  
- **Archived Projects** - Completed projects

### 4. Tag-Based Organization
Uses meta tags like `#exercise`, `#cooking`, `#travel` instead of folders.

### 5. Bidirectional Linking
Dependencies link back to main projects for seamless navigation.

## AI Assistant Integration

This system is designed to work with AI assistants acting as **Project Managers**. The AI guides users through:

- **Discovery Process** - Strategic questioning to clarify scope and requirements
- **Atomic Project Creation** - Breaking projects into proper atomic components
- **Dependency Management** - Creating and linking all necessary project dependencies
- **Progress Tracking** - Monitoring status and suggesting next actions

## Quick Start

1. **New Project**: Start at `Project Vault Dashboard`, move to "Active Projects"
2. **Capture Ideas**: Drop in `inbox/` folder, process regularly
3. **Create Dependencies**: Each project component gets its own atomic note
4. **Track Progress**: Update status and move between dashboard sections

## File Structure

```
/
├── Notes/                    # All content (flat structure)
├── inbox/                   # Temporary items (keep empty)
├── Project Vault Dashboard.md  # Central hub
└── README.md               # This file
```

## AI Assistant Guidelines

When working with this system, AI assistants should:

### Project Discovery & Creation

**Always start with discovery questions** before creating any files. Ask strategic questions to understand:
- Project scope and goals
- Timeline and constraints
- Required dependencies
- Success criteria

**Create complete project structures** using these templates:

#### Main Project Template
```markdown
[[Project Vault Dashboard|< Dashboard]]

One core idea or focus of this project.

**Goal:** Clear, measurable objective
**Due:** Target completion date
**Status:** Active

## Progress & Next Actions
- [ ] Key milestone or task
- [ ] Next action item
- [ ] Future consideration

## Project Dependencies
- [[Dependency 1]]
- [[Dependency 2]]

---
#[meta-tags]
```

#### Dependency Template
```markdown
**Project: [[Main Project Name]]**

Single paragraph explaining the core atomic idea of this note.

## Content sections as needed
...

---
#[meta-tags]
```

### Project Management Workflow

1. **Discovery Conversation**
   - Continue asking follow-up questions until you have complete understanding
   - Identify opportunities for parallel projects
   - Look for reusable components that could become separate projects

2. **Project Creation**
   - Create main project file in `Notes/`
   - Add to dashboard under "Active Projects"
   - Create all necessary dependencies as atomic notes

3. **Dependency Discovery**
   - For each dependency, conduct separate discovery conversation
   - Ensure each dependency focuses on ONE clear deliverable
   - Verify atomic principle - no overlapping dependencies

4. **Enhancement & Optimization**
   - Add realistic milestones based on timeline
   - Define clear next actions
   - Apply appropriate meta tags
   - Establish project network for parallel projects

### Dashboard Maintenance

- **Maintain four sections only** - never add subcategories
- **List projects as simple links**: `- [[Project Name]]`
- **Process inbox items regularly** - help users decide: project, dependency, or delete
- **Remind users to keep inbox empty**
- **Update project status** as work progresses

### Creating Parallel Projects

When components could serve multiple purposes or be managed independently:

1. **Identify Opportunities**
   - Reusable components across projects
   - Dependencies that could expand into projects
   - Scope better managed as separate projects

2. **Create Project Network**
   - Establish clear links between parallel projects
   - Maintain distinct goals for each
   - Enable independent progress while supporting others

### Quality Standards

- **Never use H1 headers** - Obsidian uses filename as H1
- **Use descriptive filenames** - content should be apparent from name
- **Create bidirectional links** - dependencies reference main projects
- **Apply relevant meta tags** - analyze content for appropriate tags
- **Follow atomic principle** - verify each note contains exactly one concept
- **Preserve flat structure** - no subfolders in Notes/

### Completion Process

When projects finish:
1. Change status to "Archived"
2. Move from Active Projects to Archived Projects in dashboard
3. Add final reference tags for future discovery

## System Philosophy

This system recognizes that effective project management requires both structure and flexibility. By combining atomic notes with AI-assisted project creation, it maintains clarity while scaling to handle complex, interconnected work.

The dashboard provides oversight, atomic notes ensure clarity, and AI assistance ensures proper structure and completeness. Together, they create a system that grows with your needs while staying organized.