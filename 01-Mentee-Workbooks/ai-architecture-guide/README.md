# AI Architecture — from the Ground Up (Guide)

> A teaching guide on **AI architecture**: how to organize multi-agent
> LLM systems, where to draw the boundaries between agents, how to
> share context, and what audit trails to keep. Originally drafted at
> 19V Capital's R&D and donated to this public library by the author.

## What's in the workbook

- **The shape of an AI architecture** — agents as namespaces, shared
  context as the load-bearing wall, audit trail as the floor.
- **Boundary cases** — when one agent is enough, when N agents is
  too many, the case for 3–11.
- **Operational patterns** — the four orchestration topologies
  (router, planner/executor, parallel-vote, supervisor).

## Format

| File | How to read |
|---|---|
| [`AI-Architecture-from-the-Ground-Up-Guide.html`](./AI-Architecture-from-the-Ground-Up-Guide.html) | Open in any browser |
| [`AI-Architecture-from-the-Ground-Up-Guide.pdf`](./AI-Architecture-from-the-Ground-Up-Guide.pdf) | Download for printing or offline reading |

## Related repos

- [`toolcall-agent`](https://github.com/christianmacion26/toolcall-agent)
- [`reflect-revise`](https://github.com/christianmacion26/reflect-revise)
- [`eval-mcp-server`](https://github.com/christianmacion26/eval-mcp-server)

---

© Christian T. Macion. Originally drafted at 19V Capital. Released under
the MIT License.
