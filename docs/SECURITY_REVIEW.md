# CS 305 Security Review

## Portfolio focus

This repository presents security work as evidence: checksum integrity, secure-transport concepts, dependency configuration, and mitigation reasoning. Course scaffolding is clearly separated from the security decisions demonstrated in the code.

## Findings addressed before publication

| Finding | Risk | Treatment |
| --- | --- | --- |
| Hard-coded database credentials in the original REST exercise | Credential disclosure and unauthorized database access | Excluded from the public rebuild; the original remains private evidence only |
| Personal-name sample text in the checksum exercise | Unnecessary personal information | Replaced with neutral portfolio sample data |
| Unimplemented checksum FIXME | Incomplete security demonstration | Implemented deterministic SHA-256 output with UTF-8 encoding |
| Keystores, compiled artifacts, and dependency caches | Secret or noise leakage | Excluded through repository selection and ignore rules |

## Limitations

The Spring Boot examples are educational demonstrations rather than production services. A production implementation would add authenticated access controls, structured error handling, dependency scanning, TLS configuration supplied through deployment secrets, and integration tests against a controlled test database.
