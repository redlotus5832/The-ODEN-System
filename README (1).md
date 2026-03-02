# ODEN — Observational Diagnostic Entry Network

A standalone research tool for investigating what the historical, institutional, or archival record can and cannot tell you about a question.

ODEN runs entirely in your browser. No account, no server, no internet required after the first load. Everything you enter stays on your computer until you choose to share it.

---

## What It Does

ODEN helps you build structured, sourceable investigations. You map the people, organizations, locations, documents, events, and evidence gaps connected to your research question — then write up your findings with every claim traceable to something on the map.

The goal isn't to prove a story. It's to find out whether the system that dismissed it ever had the records to back that claim.

## Who It's For

- **Historical researchers** investigating events where the official record may be incomplete
- **Genealogists** tracing family history through fragmented records across multiple archives
- **True crime and cold case investigators** examining whether investigations were thorough
- **Journalists** building structured investigations where every claim connects to documented evidence

If your work involves asking *"what does the record actually show, and where does it go silent?"* — this tool was built for that.

## How It Works

ODEN organizes your investigation across several connected workspaces:

| Tab | What It Does |
|-----|-------------|
| **Quick Start** | A guided walkthrough for first-time users |
| **Map** | Visual node graph showing your investigation — people, institutions, gaps, and how they connect |
| **Blueprint** | A structured research roadmap that walks you through your case phase by phase |
| **Nodes & Edges** | Add and connect the building blocks of your investigation (people, orgs, documents, gaps, events) |
| **Context** | Write up your findings in organized sections, linked to your evidence map |
| **Documents** | Track specific documents — received, pending, requested, or denied |
| **Sources** | Log the archives, libraries, and repositories you're working with |
| **Methodology Check** | Test your own work — is your framework falsifiable? Are the gaps real? |
| **Import Files** | Drop in existing research notes (.txt, .md, .csv, .docx) and extract entities into nodes |
| **Save Your Work** | Download your entire investigation as a .oden backup file |

## Getting Started

1. **Open the HTML file** in any modern browser (Chrome, Firefox, Safari, Edge)
2. **Click the "Quick Start" tab** for a guided walkthrough of every feature
3. **Name your case** in the header bar
4. **Start with the Blueprint** — it walks you through thinking about your case structurally
5. **Add nodes** for the key people, organizations, and evidence in your investigation
6. **Connect them** with documented relationships
7. **Write your findings** in the Context tab
8. **Save regularly** — your work auto-saves to the browser, but download a .oden backup file to be safe

## Key Principles

**Nothing goes on the map without a source.** If you can't point to a document, record, or verified piece of evidence, it doesn't get a node. The map shows what's documented — not what's suspected.

**Gaps are findings, not proof.** A missing record is documented as a missing record. It might mean suppression, bad filing, or a system that was never capable of producing that record. The gap is the finding — the interpretation is separate.

**The methodology is falsifiable.** If your framework can't produce a result that contradicts your expectations, it's not research — it's a confirmation machine. Point it at something it should fail on. If it fails cleanly, the tool works.

**Everything stays on your computer.** No data is sent anywhere. No account needed. Your investigation is private until you choose to share it.

## Node Types

ODEN uses color-coded node types to categorize the elements of your investigation:

- **Person / Actor** — Named individuals who play a role in your investigation
- **Organization** — Companies, agencies, government bodies, institutions
- **Gap / Unknown** — A specific record that should exist but doesn't — your primary findings
- **Event** — Specific dateable occurrences that anchor your timeline
- **Location** — Places that matter to the investigation
- **Document / Record** — Specific documents that are themselves evidence
- **Media** — Publications or outlets that shaped the public record
- **Witness / Source** — People who saw or reported something
- **Financial / Transaction** — Money trails that explain relationships
- **Legislation / Law** — Acts or rulings that shaped what was possible
- **Scientific Finding** — Studies or academic conclusions relevant to the case
- **Family / Lineage** — Genealogical connections
- **Network / Group** — Informal groups without official structure
- **Concept / Theory** — Ideas or narratives that need connecting to evidence
- **Object / Artifact** — Physical objects being tracked
- **Rumor / Claim** — Unverified assertions without a paper anchor
- **Pattern / Behavior** — Recurring behaviors that are themselves a finding

## Technical Details

- **Single HTML file** — no build step, no dependencies, no installation
- **Runs offline** — works without internet after initial load
- **Browser storage** — auto-saves to localStorage as you type
- **Backup format** — .oden files (JSON) for portable, restorable backups
- **File import** — parses .txt, .md, .csv, and .docx files for entity extraction
- **Responsive** — works on desktop and mobile

## License

Original methodology by unverifiableonline.com — 2026.
