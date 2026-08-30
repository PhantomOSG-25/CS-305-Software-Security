# CS 305 — Software Security Portfolio

Security-focused Java portfolio demonstrating checksum integrity, secure-transport concepts, dependency analysis, vulnerability assessment, and mitigation reporting.

## What this demonstrates

- Deterministic SHA-256 checksum generation using standard Java APIs
- Review of secure transport and certificate concepts
- Threat-focused defect analysis and remediation decisions
- Careful separation of educational scaffolding from portfolio claims
- Secret-safe repository hygiene and explicit limitations

See [the security review](docs/SECURITY_REVIEW.md) for findings and publication decisions.

## Staging decisions

- Written submissions are retained privately for evidence and metadata review.
- Selected Java and Maven project files are included for Projects One and Two and the checksum-verification exercise.
- Keystores (`.p12`), JARs, compiled classes, dumps, IDE metadata, Maven wrapper downloaders, build output, and raw ZIPs are excluded.
- Configuration files with password- or keystore-shaped values are withheld pending manual secret review.

Much of the Spring project structure may be course-provided. Public claims must focus on verified security analysis and student modifications rather than the presence of scaffolding.
