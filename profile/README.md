<p align="center">
  <img src="https://raw.githubusercontent.com/akhundMurad/pacta/main/assets/logo-ascii.png" alt="Pacta" width="400">
</p>

<p align="center">
  <strong>Architecture Insights, Governance & Versioned Design</strong>
</p>

<p align="center">
  <a href="https://pypi.org/project/pacta/">PyPI</a> •
  <a href="https://pacta-dev.github.io/pacta-cli/">Docs</a> •
  <a href="https://github.com/pacta-dev/pacta-cli/issues">Issues</a>
</p>

---

Pacta turns software architecture into versioned, queryable data — so teams can see, compare, and reason about architectural change over time, not just block violations.

<p align="center">
  <img src="https://raw.githubusercontent.com/akhundMurad/pacta/main/assets/demo.gif" alt="Pacta Demo" width="700">
</p>

## Why?

Codebases rot. Architecture degrades through small changes no one tracks. Pacta turns architecture into something measurable, reviewable, and enforceable — catching drift early, not months later.

## What it does

- **Architecture snapshots** — version your architecture like code
- **History & trends** — track how dependencies, coupling, and violations evolve over time
- **Diffs** — compare architectural states like Git commits
- **Metrics & insights** — nodes, edges, layers, instability, drift
- **Rules & governance** — express architectural intent and enforce it incrementally
- **Baseline mode** — govern change without being blocked by legacy debt

## Think of Pacta like Git for architecture

| Git | Pacta |
|-----|-------|
| `git add` | `pacta snapshot save` — capture an architectural snapshot |
| `git commit --verify` | `pacta check` — evaluate rules against a snapshot |
| `git commit` | `pacta scan` — snapshot + check in one step |
| `git log` | `pacta history` — timeline and trends of architectural states |
| `git diff` | `pacta diff` — compare two snapshots |
| branch protection | `rules.pacta.yml` — governance that prevents drift |

See the [Getting Started](https://pacta-dev.github.io/pacta-cli/getting-started/) guide for a full walkthrough.

## Docs

- [CLI Reference](https://pacta-dev.github.io/pacta-cli/cli/)
- [Architecture Model](https://pacta-dev.github.io/pacta-cli/architecture/)
- [Rules DSL](https://pacta-dev.github.io/pacta-cli/rules/)
