# REQUIREMENTS

## Primary objective

Develop and operate a technically verified, maintainable networking architecture around PasarGuard/Xray that can be evaluated under real Iran-to-foreign network conditions.

## Design philosophy

1. Existing tunnel projects are references, not the solution boundary.
2. Discover the complete solution space before selecting an architecture.
3. Create new combinations or custom protocols when a measured capability gap requires them.
4. Do not call something novel without prior-art research.
5. Prefer the simplest architecture that satisfies measured requirements.
6. Verify every important claim.
7. Use repeatable measurements rather than intuition.

## Functional requirements

- PasarGuard compatibility where practical.
- Xray compatibility where relevant.
- TCP support.
- UDP support when required by workload.
- IPv4 support.
- IPv6 behavior explicitly tested.
- Recoverable failures.
- Observable logs and diagnostics.
- Reproducible setup.
- Clear client/server configuration mapping.
- Support for direct, reverse, multi-hop and CDN-mediated architectures where technically feasible.
- Ability to evaluate custom tunnel designs.

## Non-functional requirements

- Low unnecessary complexity.
- Predictable resource usage.
- Measured latency and throughput.
- Explicit MTU/MSS handling where needed.
- Backup and rollback paths.
- No secrets committed to public repositories.

## Research requirements

The AI must research:
- current PasarGuard and Xray behavior
- current tunnel ecosystem
- current CDN capabilities
- current Iranian network observations
- relevant prior art
- protocol specifications and implementation details
