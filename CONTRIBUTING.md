# Contributing to Simulare architecture

## Decisions

Decisions document significant architectural choices. They are also known as
architecture decision records (ADRs). To propose a new decision:

1. Copy `templates/decision.md` to `decisions/NNNN-title.md`
2. Fill in the template sections
3. Submit a merge request for review

### When to write a decision

- Choosing between competing technologies or approaches
- Establishing conventions that affect multiple projects
- Making trade-offs with long-term implications
- Changing a previous architectural decision

## Comments

Comments propose substantial changes that benefit from broader discussion. They
are also known as requests for comments (RFCs). To propose a comment:

1. Copy `templates/comment.md` to `comments/NNNN-title.md`
2. Fill in the template sections
3. Submit a merge request for review

### When to write a comment

- New subsystems or major features
- Changes to cross-cutting concerns (authentication, data formats, protocols)
- API design for shared interfaces
- Process or workflow changes

## Conventions

- Use sentence casing in all documents
- Spell out acronyms on first use
- Use human-centric language (people, developers, operators — not "users")
- Do not use "frontend" — use "web application", "web infrastructure", or "interactive components"
- Default branch is `trunk`
- Licensing: LGPL 3.0 and MPL 2.0 for code, CC BY-SA 4.0 for architecture documents

## Governance

This repository follows the
[Omnifi Foundation governance model](https://handbook.omnifi.foundation/engineering/architecture/governance/).
