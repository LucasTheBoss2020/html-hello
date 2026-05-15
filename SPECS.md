## Product Description

AgentHub is a SaaS platform where companies rent AI agents—preconfigured assistants that can browse the web, read documents, summarize content, or manage tasks. The admin user is an internal team member who manages users, agents, skills, contracts, and system activity. This HTML prototype is used to validate layout and behavior before backend integration.
    
## Tech Stack and Constraints

- HTML
- Tailwind CSS via CDN
- Vanilla JavaScript
- No frameworks
- No backend
- No custom CSS files
- No inline styles

## Section Specifications

1. Skills
- Catalog of 4 skills with name, description, and agent count.
- Short explanation of what a “skill” is appears at the top.
- Each skill has a dropdown with “View detail” and “Delete”.

2. Dashboard
- Four metric cards in a responsive 2×2 grid with icon, label, and hardcoded value.
- Each card uses a unique accent color and subtle shadow.
- A full‑width dashed placeholder represents the weekly activity chart.

3. Error Log
- Six hardcoded errors with timestamp, agent name, colored error badge, description.
- dropdown with “View detail” and “Mark as resolved”.
- Error badges use Tailwind colors to indicate severity.

4. User Management
- Table with 5 hardcoded users: name, email, plan, status badge.
- Each row has a dropdown with “View detail” and “Delete”.
- “View detail” opens a modal; modal closes via button or backdrop.

5. Agent Management
- List of 4 agents showing name, owner, and status badge.
- Each agent has a collapsible skill list (collapsed by default).
- dropdown includes “Configure” (opens modal with <textarea>) and “Delete”.

6. Agent Contracts
- Table with 4 contracts: client, agent, skills, dates, amount paid.
- dropdown with “View detail” opens a modal showing itemized skill pricing.
- Table uses semantic HTML and Tailwind spacing utilities.

## Component Inventory

- Sidebar navigation
- Metric card
- Status badge
- Action dropdown
- Modal
- Collapsible skill list
- Dark mode toggle

## Acceptance Criteria

- SPECS.md committed before any HTML.
- All six sections accessible from sidebar.
- Tailwind classes used everywhere; no inline styles or custom CSS.
- All dropdowns open, close, and close on outside click.
- “View detail” opens modals in at least four sections.
- Modals close via button and backdrop.
- Skill lists expand/collapse with a visible transition.
- Dark/light mode toggle updates entire panel and persists between sections.
- Hardcoded data stays consistent across sections.
- Semantic HTML tags used correctly.
- Layout works on desktop and tablet.
