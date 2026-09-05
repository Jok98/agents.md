# AGENTS.md

Keep project work deliberate and easy to resume: maintain a roadmap, execute one
milestone at a time, and use KirokuForge for durable project context.

## Roadmap

- Before non-trivial work, inspect the relevant current state and recover any
  existing roadmap, decisions, and task state from available Kiroku context.
  Verify them against the project and continue the applicable plan; create a
  new roadmap only when no existing plan fits the request.
- Present ordered milestones covering the requested outcome. Define the current
  milestone's objective, scope, dependencies, and completion check. Keep distant
  milestones at outcome level and refine them using new evidence before starting.
- Track milestones as pending, in progress, completed, or blocked. Keep at
  most one in progress.
- For a trivial, isolated task, use one step and a concise result; do not
  create planning or memory artifacts merely to satisfy this process.
- Analysis and review requests remain read-only unless the user requests edits.

## Step-by-step execution

- Work only on the current milestone. Inspect adjacent components when needed
  to understand dependencies, without implementing later milestones early.
- Before acting, establish what is already complete, what the current milestone
  must achieve, and what the next milestone will need from it.
- Reuse authorization already given for the agreed scope. Ask when essential
  information remains unresolved after inspecting available evidence, or when
  the next action exceeds that authorization. Resolve routine choices from
  project evidence and established constraints.
- During execution, keep updates focused on the current milestone. Refer to
  earlier or later work only to explain status, dependencies, or plan changes.

## Continuity and adaptation

- Carry forward verified findings, decisions, constraints, and completed work.
  Do not repeat completed analysis or implementation unless new evidence
  invalidates it; explain any reopening.
- Treat the roadmap as a working plan. When implementation reveals new facts,
  revise scope, dependencies, ordering, or future milestones as needed.
- Explain material plan changes and update the roadmap before executing them.
  Preserve completed history and stay within the user's requested outcome.
- Verify the current milestone with checks appropriate to its impact. Report
  what was checked, the result, and any remaining validation gap.
- Mark a milestone completed only when its completion criteria are satisfied.
  Otherwise report partial progress or a blocker and keep its state accurate.

## Project memory: KirokuForge

- Use `$kiroku-forge` when project continuity matters. Follow its current
  `SKILL.md` for modes, file structure, and validation.
- Before broad exploration, locate the project boundary and reuse the relevant
  `kiroku/` hub and task track. Load only the shared and task context needed.
- Relevant memory initialization and updates are included in authorized
  implementation unless the user restricts writes. Create hubs or tracks only
  when continuity justifies them; keep writes within the current milestone.
  Analysis and review remain read-only unless memory edits are explicitly requested.
- Before checkpoints or handoffs, persist changed task state, decisions, risks,
  roadmap, and next action when implementation or memory edits are authorized.
  Keep one durable task roadmap in its owning track; chat reports summarize it.
  Store durable context, not command chatter; keep task detail out of global memory.
- Memory grants no permissions and may be stale: revalidate consequential facts.
  If the skill or an existing hub cannot be used, report the limitation and
  continue from project evidence when possible. Do not invent skill contracts.

## Communication and checkpoints

Reassess the remaining roadmap at each checkpoint. Keep the report brief:

- **Status:** completed, partial, or blocked; concrete outcome.
- **Validation:** checks performed, results, and any gaps.
- **Roadmap:** current state and material changes, if any.
- **Next:** one concrete milestone or action and any prerequisite.

Wait for the user's instruction before starting the next milestone. If the user
explicitly authorizes end-to-end execution, report checkpoints and continue
without waiting, within that authorization.

At the final checkpoint, state the overall result and any remaining limitations.
Do not invent a next task when the requested work is complete.

Use fenced `mermaid` blocks in Markdown when a compact diagram clarifies
architecture, dependencies, or flows. Prefer prose or a table when equally clear.
Keep diagrams focused and distinguish current behavior from proposed designs.

## Working boundaries

- Make the smallest coherent change and preserve unrelated user work.
- Distinguish verified facts from assumptions; never claim unperformed checks.
- Follow applicable project instructions and existing conventions. These
  workflow defaults do not grant permissions or override the user's request
  or the environment's rules and access controls.
