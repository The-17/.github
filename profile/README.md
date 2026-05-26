# The Seventeen

We build practical systems that make living and building easier.
We prioritize utility over attention. If a tool doesn't remove friction or reduce decision fatigue, we don't build it.

## Engineering Philosophy

Software should be boring.

Most widely-used tools today solve symptoms while adding complexity. We focus on causes. We design systems that are readable, maintainable, and built to outlive the teams that created them.

- **Clarity over cleverness.** We prefer code that is easy to read over code that is fast to write.
- **Dependencies are liability.** We add them only when necessary.
- **Scarcity is a feature.** Constraints breed better solutions than abundance.

## Active Public Systems

These are the tools we use to run our own organization

- **[AgentSecrets](https://github.com/The-17/agentsecrets)**: Zero-knowledge secrets infrastructure for AI systems. Agents operate credentials without ever seeing the values.

- **[keychain-auth](https://github.com/The-17/keychain-auth)**: OS keychain security hardening. Closes the gap the OS leaves open — any process running as you can read your keychain. keychain-auth enforces verified process identity before any credential is accessed.

- **[SEC](https://github.com/The-17/sec)**: Signed Execution Contracts for AI agents. Before an agent reads untrusted content, it commits to a signed contract declaring what it is allowed to do. If the agent is hijacked by a prompt injection, the contract doesn't change — and the credentials stay locked.

- **[pr-reviewer](https://github.com/The-17/pr-reviewer)**: Autonomous Python PR reviewer. Production-grade agentic system and the live showcase for the AgentSecrets security stack — progressing from unsecured baseline through credential protection (AgentSecrets), cryptographic intent enforcement (SEC), and behavioral abuse containment (CAD).

## Where to Find Us

The work happens on [GitHub](https://github.com/The-17).
We document how these systems are designed and built at [engineering.theseventeen.co](https://engineering.theseventeen.co), written for engineers who want to understand the reasoning, not just the result.
Everything else is at [theseventeen.co](https://theseventeen.co).
