# wxctl docs

## Get started

| Page | Content |
|---|---|
| `introduction.mdx` | What wxctl is, the problem it solves, and the end-to-end lifecycle clips |
| `installation.mdx` | Install or build the binary, configure a profile, upgrade, uninstall |
| `quickstart.mdx` | Hub: pick the declarative or generative path to build the example |
| `quickstart/declarative.mdx` | Build the example by hand: config, tools, knowledge base, then plan, apply, test |
| `quickstart/generative.mdx` | Build the example with IBM Bob over MCP from one plain-language sentence |

## Concepts

| Page | Content |
|---|---|
| `concepts/declarative-model.mdx` | Resources, `${kind.ref_name}` references, `${env:VAR}` interpolation, combining sources with `-f` |
| `concepts/pipeline.mdx` | The fixed stages every command runs (validate, closure, reconcile, plan, execute) and how `plan` and `apply` differ |
| `concepts/profiles-and-credentials.mdx` | Profiles, how the active profile is chosen, and every supported auth type |
| `concepts/how-wxctl-compares.mdx` | How wxctl relates to Terraform, Pulumi, and Ansible, and when to reach for each |

## Guides

| Page | Content |
|---|---|
| `guides/compose.mdx` | Generate a config from a plain-language scenario with the compose MCP tools |
| `guides/examples.mdx` | Worked example: a tool, an agent, and a test, built by hand end to end |
| `guides/gallery.mdx` | Curated index of runnable examples, grouped by industry and complexity tier |
| `guides/mcp-clients.mdx` | Wire the local MCP server into IBM Bob, Cursor, and Claude Desktop, or point a client at the hosted Worker |
| `guides/automation.mdx` | Unattended runs: idempotent applies, the exit-code contract, secrets, GitHub Actions |
| `guides/troubleshooting.mdx` | Logging, concurrency, timeout, and terminal-color environment variables |

## Reference

Generated from the built `wxctl` binary; each page carries a banner saying so. Do not hand-edit.

| Page | Content |
|---|---|
| `reference/commands.mdx` | Every command, its flags, and examples |
| `reference/resources.mdx` | Every supported resource kind, with deployment and endpoint |
| `reference/kinds/*.mdx` | Per-service kind pages: fields, dependencies, and endpoints |

## Project

| Page | Content |
|---|---|
| `faq.mdx` | Common questions: wxctl vs infrastructure-as-code, auth, late-bound identifiers, resetting a profile |
| `releases.mdx` | Where releases are published and what to expect from versioning |
