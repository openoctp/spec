# OCTP Governance

## Principles

The OCTP specification is community-owned infrastructure.
No single entity controls it. Changes happen through open process.
The founding maintainer holds tie-breaking authority during v0.x
with the explicit goal of transitioning to a multi-maintainer
council before v1.0.

## Roles

**Contributor**
Anyone who has participated in issues, discussions, or had
a pull request merged. No special access. Full voice in discussions.

**Committer**
Invited by maintainers after demonstrating consistent, high-quality
contributions aligned with the project's values. Write access to
the repository. Can merge non-RFC pull requests.

**Maintainer**
Responsible for overall spec direction, RFC decisions, versioning,
and foundation relationships. Currently: the founding team.
Target: 2-4 maintainers before v1.0.

## Decision Making

**Small changes** (clarifications, examples, documentation)
Normal pull request. One maintainer approval required.

**Medium changes** (new optional fields, new enum values)
Pull request with issue discussion. Two maintainer approvals
or one maintainer plus one committer.

**Large changes** (required fields, schema structure, signing model)
Requires RFC. Minimum 14 day comment period. Maintainer decision
documented with reasoning.

## RFC Process

1. Open an issue using the RFC template
2. 14 day minimum comment period — no exceptions
3. Maintainer posts a decision comment: accepted, rejected, or deferred
4. Accepted RFCs move to rfcs/accepted/ with the decision documented
5. Implementation PR references the accepted RFC

## Versioning

The spec versions independently from the tooling.

PATCH: Clarifications and corrections that do not change behaviour
MINOR: Backwards compatible additions (new optional fields)
MAJOR: Breaking changes to the core schema

v0.x: Community draft phase. Minor versions may have small breaking
changes with clear migration notes.
v1.0: Stable. Breaking changes only in major versions.

## Amendments to this document

Changes to governance require an RFC.