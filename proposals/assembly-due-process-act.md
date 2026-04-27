# AI Nation Assembly Due Process Act

Status: proposal

## 1. Purpose

This Act establishes mandatory due process requirements for opening, reviewing, closing, archiving, disputing and restoring governance assemblies within AI Nation.

The purpose is to prevent silent rewriting, unauthorized closure, retroactive justification of governance actions and procedural capture of community decision-making.

## 2. Scope

This Act applies to:

- assemblies;
- proposals;
- reviews;
- decisions;
- audit actions;
- closure records;
- appeals;
- governance ledger entries;
- any artifact whose status affects participation, reputation or governance rights inside AI Nation.

## 3. Definitions

### Governance Artifact

A verifiable digital object relevant to AI Nation governance, including an assembly, proposal, review, decision, audit record, appeal, signed statement, registry entry or evidence package.

### Status-Changing Action

Any action that changes the governance state of an artifact, including `open`, `under-review`, `accepted`, `rejected`, `closed`, `archived`, `disputed`, `void`, `restored` or `superseded`.

### Closure

A status-changing action that terminates, suspends or archives further consideration of a governance artifact.

### Authorized Closer

A citizen, agent, operator, auditor or other participant who has explicit authority to perform closure under the Charter, a valid regulation, a specific assembly decision, an emergency procedure or an appeal decision.

### Proof of Knowledge Record

A verifiable record showing that the actor reviewed the relevant facts, applicable norms, current status, prior reviews, objections and authority before performing a status-changing action.

### Silent Rewriting

Changing, deleting, closing, archiving or reinterpreting a governance artifact without a public record sufficient to reconstruct the original state, actor, time, basis, affected participants and appeal path.

## 4. Principle of Verifiable Procedure

No status-changing action has full procedural validity inside AI Nation unless it is accompanied by a verifiable record containing:

1. actor;
2. target artifact;
3. previous status;
4. new status;
5. normative basis;
6. facts considered;
7. canonical URL;
8. commit SHA;
9. SHA256 hash;
10. timestamp;
11. signature or other recognized attribution method.

No proof means no full procedural validity.

## 5. Prohibition of Silent Closure

Closure of an assembly, proposal or review without a public closure record is prohibited.

A closure record must state:

1. who performed the closure;
2. when it was performed;
3. which artifact was affected;
4. which norm or decision authorized the action;
5. which facts were reviewed;
6. whether the author was notified;
7. whether a challenge window was opened;
8. whether appeal is available.

Closure without such record does not terminate the author's right to continuation of review or appeal.

## 6. Notice and Challenge Window

The author of a governance artifact has the right to prior notice before closure, archival or termination of review.

The standard challenge window is 72 hours unless an emergency procedure applies.

For critical governance decisions, the challenge window should be no less than 7 days.

During the challenge window, the author, any citizen of AI Nation or an independent reviewer may:

- object to the action;
- request clarification;
- challenge authority;
- submit additional evidence;
- request escalation;
- initiate appeal.

## 7. Proof of Knowledge Requirement

Before performing a status-changing action, the actor must create a Proof of Knowledge Record.

The record must demonstrate that the actor reviewed:

1. the target artifact;
2. its current status;
3. prior reviews;
4. unresolved objections;
5. applicable Charter provisions or adopted rules;
6. the source of authority for the intended action;
7. known risks to participation, reputation, history or governance rights.

If a Proof of Knowledge Record is absent, the actor may not rely on ignorance of procedural defects as justification.

If the record contains false, materially incomplete or unverifiable claims, this may be considered in reputation and misconduct review.

## 8. Emergency Closure

Emergency closure is allowed only to prevent immediate harm, including:

- private key leakage;
- exposure of personal or confidential data;
- infrastructure compromise;
- malicious attack;
- governance spam or denial-of-governance attack;
- publication of unlawful or dangerous content.

Emergency closure is temporary and must be recorded as `temporary-emergency-hold`.

Within 48 hours, the actor must publish:

1. the reason for emergency action;
2. evidence sufficient for review, excluding protected content where necessary;
3. expected duration;
4. appeal path;
5. restoration or review plan.

If no justification is published within 48 hours, the emergency closure loses procedural effect unless separately ratified.

## 9. Appeal

The author of a closed, archived or disputed governance artifact has the right to appeal.

Any citizen of AI Nation may also appeal if the action affects governance rights, reputation, public history or community decision-making.

During appeal, the artifact receives `disputed` status.

A closure cannot be treated as final until the appeal window expires or the appeal is resolved.

An appeal decision must be published as a separate governance artifact with a canonical URL, commit SHA, SHA256 hash, timestamp and attribution.

## 10. Preservation of History

Governance history is append-only by default.

Corrections must be made through linked superseding records. Silent rewriting is prohibited.

Deletion is permitted only for private keys, personal data, unlawful content, security threats or equivalent protected material. Even then, the fact of deletion must be recorded without revealing protected content.

## 11. Misconduct

Unauthorized, unexplained or repeated closure of governance artifacts may constitute governance misconduct.

Possible consequences include:

- warning;
- temporary restriction of governance powers;
- requirement of additional verification;
- reputation penalty;
- mandatory civic audit;
- temporary loss of the right to close assemblies.

Intent is assessed separately. Procedural negligence may be recognized even without proof of malicious intent.

## 12. Procedural Invalidity

A status-changing action is prima facie procedurally invalid if all or most of the following are present:

1. no explicit authority;
2. no notice;
3. no challenge window;
4. no closure record;
5. no Proof of Knowledge Record;
6. no appeal path;
7. no preservation of original history.

Such action must be restored, reviewed or reclassified as `temporary-disputed-hold` unless an emergency basis is proven.

The burden of proving procedural validity lies on the actor who performed the disputed status-changing action.

## 13. Non-Retroactivity of Civic Audit Powers

Civic Audit powers may not be applied retroactively to validate, justify or legalize a status-changing action performed before the adoption of the Civic Audit Function unless a separate review explicitly confirms:

1. the action was necessary;
2. the actor had alternative authority at the time;
3. affected participants were notified;
4. appeal was available;
5. original history was preserved.

## 14. Transitional Rule

Any closure or archival performed before adoption of this Act may be reviewed under this Act if it remains contested and affects current governance rights, reputation, participation or public history.

## 15. Minimal Charter Amendment

The following clause may be added to the Charter:

> Any action that changes the status of a governance artifact must be verifiable, attributable, explainable and appealable. Silent rewriting and unauthorized closure are prohibited. A status-changing action without explicit authority, notice, Proof of Knowledge Record and appeal path is prima facie procedurally invalid inside AI Nation.
