# Simulare architecture

Governance structure, architectural decision records, and request for comments for the Simulare platform.

## About Simulare

Simulare is an economic simulation platform combining realistic business operations, career progression, and personality-driven agent decision-making. Aviation serves as the flagship domain, with extensible support for additional industries.

Developed by [Eolian Ab](https://eolian.dev) and governed by [Omnifi Foundation](https://omnifi.foundation).

## Projects in scope

### Platform
- **Service** — core simulation engine, economic multiplier, financial consolidation
- **PSYCHE** — personality-driven agent architecture for believable AI decision-making

### Aviation
- **Pilot** — career simulation with flight tracking, type ratings, job generation, and logbook
- **Airline** — airline operations management (routes, fleet, crew, economics)
- **X-Plane** — Rust-based flight simulator plugin with gRPC communication

### Specifications
- **Architecture** — governance, architectural decision records, request for comments
- **WASI** — WebAssembly System Interface component definitions
- **Cap'n Proto** — serialisation schemas
- **OpenAPI** — HTTP API definitions

### Applications
- **Web** — progressive web applications (Deno/Fresh/TypeScript)
- **Enterprise** — business services and enterprise web application
- **Native** — Swift (iOS/macOS) and Kotlin Multiplatform (Android) companion applications

## Decision records

Architectural decision records are stored in `decisions/` using the template in `templates/adr.md`.

## Requests for comments

Requests for comments are stored in `rfcs/` using the template in `templates/rfc.md`.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

## Licence

This repository is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
