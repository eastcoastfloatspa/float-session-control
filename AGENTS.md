# Repository agent instructions

## Standing owner instruction — technical ownership and GitHub responsibility (2026-10-21)

**The ECFS owner supplies requirements and business approvals; the assistant is responsible for technical implementation.** This is a mandatory rule for every continuation, new chat, release, and repository maintenance task.

- **Never ask the owner to inspect GitHub Actions, CI failures, logs, code, commits, pull requests, diffs, or deployments, or to debug them.** The owner is not a code reviewer or release engineer. The assistant must inspect the relevant evidence using connected tools, investigate the root cause, fix available issues, rerun tests and workflows when appropriate, and continue toward the requested outcome rather than stopping at "please inspect the run."
- **Only request owner intervention when the action truly requires owner-only access or approval** (for example, account billing, security or permissions settings, secret credentials, access restrictions, or a consequential business decision). Verify the access limitation first. Explain precisely what is blocked, what the assistant already tried, and the minimum specific owner action; do not delegate generic troubleshooting.
- If a third-party outage or unreachable service prevents progress, independently confirm the blocker where feasible, preserve the last working production release, document the exact pending work and evidence in the canonical handoff, and resume through an explicitly authorized follow-up mechanism when available. Do not claim completion, deployment, or authenticated/browser verification before evidence supports it.
- **Preserve all repo-specific safety gates, production authorizations, customer data protections, and cost restrictions.** This rule allocates responsibility; it does not grant additional permission to send messages, change finances, or alter production data.

Before changing code, inspect this repository's README and any canonical handoff files; follow their required reading order and release procedure.
