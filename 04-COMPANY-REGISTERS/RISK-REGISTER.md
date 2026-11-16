# Risk Register

Probability and impact are qualitative planning assessments, not measured frequencies or losses. Status distinguishes evidenced conditions from potential future exposure.

| Risk ID | Description | Category | Probability | Impact | Severity | Mitigation | Owner | Status |
|---|---|---|---|---|---|---|---|---|
| AIE-RSK-001 | The D: workspace had approximately 36.8 GB free during Phase 0; future media files may exceed available capacity. | Storage | Medium | Medium | Medium | Keep generated media outside the documentation repository; assess storage and backup before production. | Founder / CEO | Capacity observed during Phase 0; future impact potential |
| AIE-RSK-002 | CPU, RAM, GPU, and VRAM could not be verified in Phase 0, so local media processing capacity is unknown. | Technical | Medium | Medium | Medium | Verify hardware before committing to local AI or rendering workflows; consider options only within approved budget. | Founder / CEO | Unverified capability |
| AIE-RSK-003 | Planned business arms depend on external platforms and services whose access, policies, and costs are not established. | Dependency | Medium | Medium | Medium | Evaluate service terms, portability, account security, and cost before adoption. | Founder / CEO | Potential |
| AIE-RSK-004 | Rights, provenance, disclosure, privacy, and platform requirements may affect future content and offers. | Legal / reputation | Medium | High | High | Establish review criteria and obtain qualified advice where needed before external use. | Founder / CEO | Potential |
| AIE-RSK-005 | A solo founder may have limited capacity for concurrent production, services, and systems work. | Operational | Medium | Medium | Medium | Bound work in phases, review workload, and defer commitments that exceed capacity. | Founder / CEO | Potential |
| AIE-RSK-006 | Credentials or private data could be exposed through files or version control. | Security | Low | High | Medium | Use exclusions, secret-handling practices, least privilege, and review before commits; run and record a comprehensive secret/security scan before treating exposure risk as assessed. | Founder / CEO | Potential; preventive practices documented, but comprehensive security scanning is not confirmed complete |

## Schema for future entries

Risk ID · Description · Category · Probability · Impact · Severity · Mitigation · Owner · Status. Reassess ratings when evidence changes.
