# Which SAT solver finishes more public cases in 60 seconds?

Compare two pinned solvers on 12 predetermined 2026 competition instances under the same single-core limit.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/sat-competition-comparison/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-sat-competition-comparison/pulls)

## Why this matters

SAT Competition 2026 publishes instance-level results, solvers and benchmarks. A small, fixed sample makes it possible for another contributor to reproduce a comparison.

## What to contribute

Predeclare 12 public instance hashes, two solvers that output checkable witnesses or certificates, and a one-core 60-second wall-time limit. Publish one driver command to run both.

## How reviewers check it

For every solver and instance, report the model or certificate check, elapsed time, timeout or error, and environment. Count only independently verified answers as solved.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/sat-competition-comparison
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/sat-competition-comparison/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-sat-competition-comparison/security/advisories/new) for security reports.

## Sources

- [SAT Competition 2026 releases and results](<https://satcompetition.github.io/2026/>)
- [SAT Competition output and certificate rules](<https://satcompetition.github.io/2026/output.html>)
