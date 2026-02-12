# Contributing to Simulare architecture

## Decision records

Architectural decision records (ADRs) document significant architectural choices. To propose a new decision:

1. Copy `templates/adr.md` to `decisions/NNNN-title.md`
2. Fill in the template sections
3. Submit a merge request for review

### When to write an ADR

- Choosing between competing technologies or approaches
- Establishing conventions that affect multiple projects
- Making trade-offs with long-term implications
- Changing a previous architectural decision

## Requests for comments

Requests for comments (RFCs) propose substantial changes that benefit from broader discussion. To propose an RFC:

1. Copy `templates/rfc.md` to `rfcs/NNNN-title.md`
2. Fill in the template sections
3. Submit a merge request for review

### When to write an RFC

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
