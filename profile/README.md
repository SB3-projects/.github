# SB3-projects

This organisation holds the team's project repositories: the actual delivery work, whether for a client or for ourselves. Each repo is scoped to one project and carries its own context, code, and documentation.

Reusable, client-agnostic assets live in a separate organisation, [SB3-vault](https://github.com/SB3-vault): [strategy-vault](https://github.com/SB3-vault/strategy-vault) for frameworks, playbooks, and templates, and [tech-vault](https://github.com/SB3-vault/tech-vault) for tools, scripts, and skills. If something built in a project here turns out to be reusable, strip the project-specific parts and move it to the vault.

## Naming convention

Every repository name starts with a prefix that says who the project is for:

| Prefix | Use for | Example |
|---|---|---|
| `internal-` | Internal projects: tools, accelerators, and R&D we build for ourselves | `internal-GenAIFinOps` |
| `client-` | Client projects: delivery work for a specific client engagement | `client-AcmeDataPlatform` |

After the prefix, use a short descriptive name in PascalCase, without spaces or extra hyphens.

## Ground rules

- One project per repository. Do not mix client work and internal work in the same repo.
- Client repos must be private and contain nothing from another client.
- No credentials, tokens, or secrets in any repo. Use `.env` files that are gitignored.
- Every repo has a README that explains what the project is, how to set it up, and where the documentation lives.
