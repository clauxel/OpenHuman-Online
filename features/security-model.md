# Security Model

This documentation is public. It should explain safe evaluation without leaking implementation details.

## Public-Safe Claims

- OpenHuman Online is a hosted SaaS for hosted personal AI memory workspace.
- The documentation is independent from private production infrastructure.
- Readers should verify live behavior before making procurement or rollout decisions.
- Sensitive data should stay out of public examples and public GitHub issues.

## Practical Guardrails

- Do not connect broad inbox or chat history before a source policy exists.
- Keep sensitive customer notes out of public examples.
- Review generated memory before relying on it in meetings.
- Use the smallest useful connector set for the first pilot.

## Data Boundaries

Do not include:

- API keys, tokens, payment secrets, webhook secrets, or account identifiers.
- Private repositories, private customer names, private analytics, or local machine paths.
- Internal Cloudflare, database, registrar, or payment-provider configuration.
- Screenshots that reveal private sessions, accounts, or browser profiles.

## Safe Link

Use the public SaaS link with UTM:

- https://openhuman.online/?utm_source=github&utm_medium=documentation&utm_campaign=openhuman_online_docs&utm_content=security_safe_link
