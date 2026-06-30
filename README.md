# AI Automation Library

A central library of reusable AI automations built across the Conga organization.

## Purpose

This page is a central catalog of automations that any team can discover, understand, and reuse.  
It starts with automations built for CODS, OSM, and Ops Leadership reporting — and is designed to grow as new automations are contributed.

## Live Page

Open `index.html` in any browser — no server required.

## Contents

| File | Description |
|------|-------------|
| `index.html` | Fully self-contained AI Automation Library app |

## Features

- Search by name, description, owner, or keyword  
- Filter by Function, Tool, Complexity, and Team/Pillar  
- Card grid with status badges (Ready to Use / Needs Setup / Experimental)  
- Slide-out detail panel per automation with: problem statement, what it does, how it works (Trigger → Logic → Action), reuse steps, required inputs, sample output, impact, dependencies, version  

## Automations Catalogued

| # | Name | Function | Status |
|---|------|----------|--------|
| 1 | Sprint Health Monitoring Agent | Sprint Management | Ready to Use |
| 2 | Auto SLA Breach Alert | Support / Ops | Needs Setup |
| 3 | Weekly Status Report Generator | Reporting | Ready to Use |
| 4 | Sprint Spillover Truth Report | Sprint Management | Ready to Use |
| 5 | CODS Ops Maturity Auto-Refresh | Reporting | Ready to Use |
| 6 | CODS Sprint Pulse Dashboard Pipeline | Sprint Management | Ready to Use |
| 7 | OSM Monthly Executive Dashboard Automation | Reporting | Ready to Use |
| 8 | Hosting Impact Cost Estimator Agent | DevOps | Ready to Use |
| 9 | Org Releases Tracker Dashboard | Reporting | Ready to Use |
| 10 | Master Dashboard Composer | Reporting | Needs Setup |
| 11 | Resource Optimization Refresh | Reporting | Ready to Use |
| 12 | Jira-to-Email Newsletter Builder | Support | Experimental |

## Contributing

To add a new automation, add a new entry to the `automations` array in `index.html` with the following fields:

```js
{
  id: "unique-kebab-id",
  name: "Automation Name",
  description: "One-line description",
  function: "Function Tag",
  tools: ["Tool1", "Tool2"],
  complexity: "Basic | Medium | Advanced",
  team: "Team or Pillar",
  impact: "Time/effort saved",
  owner: "Your Name",
  status: "Ready to Use | Needs Setup | Experimental",
  source: "Repo path or link",
  problem: "Problem it solves",
  does: ["Bullet 1", "Bullet 2"],
  whenToUse: "When to use it",
  flow: "Trigger → Logic → Action",
  reuseSteps: ["Step 1", "Step 2"],
  inputs: ["Input 1", "Input 2"],
  sampleOutput: "Example result text",
  dependencies: "Known dependencies or limitations",
  version: "v1.0",
  lastUpdated: "YYYY-MM-DD"
}
```

## Owner

Kranthi Nagulapally — knagulapally@conga.com
