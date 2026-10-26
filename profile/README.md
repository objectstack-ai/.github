<h1 align="center">ObjectStack</h1>

<p align="center"><b>The ontology is the software.</b> &nbsp;·&nbsp; 本体即软件</p>

<p align="center">One executable business ontology. AI writes it, the runtime runs it, agents operate it, you own it.</p>

Your app's definition — objects, relations, actions, permissions, flows, agent and
tool definitions — is a **business ontology**: typed, validated, versioned in your
repository, and small enough for an agent to hold whole. The runtime derives the
database, REST API, Console and MCP tools from that one definition, and enforces
permissions and audit on every call.

## Two ways to build & ask

|  | **Build & ask with Claude Code** | **Build & ask online** |
|---|---|---|
| Where | In your repo, with your coding agent (Claude Code, Cursor, Copilot …) | In the browser — no toolchain, nothing to deploy |
| What | [**ObjectStack**](https://github.com/objectstack-ai/objectstack) — the open protocol and runtime: `@objectstack/spec`, microkernel, CLI, SDK, Console | [**ObjectOS**](https://www.objectos.ai) — the commercial runtime environment built on ObjectStack: AI Build & Ask, approvals, SSO, deployment, operations |
| Terms | Apache-2.0, self-host anywhere | ObjectOS Cloud (we operate it) or ObjectOS Enterprise (your infrastructure) |
| Start | `npm create objectstack@latest` | [objectos.ai](https://www.objectos.ai) |

Either way the ontology is yours: an app built on ObjectOS exports to the open
runtime, and an app built on ObjectStack installs into ObjectOS.

## Repositories

| | Repo | What it is |
|---|---|---|
| 🏗️ | [objectstack](https://github.com/objectstack-ai/objectstack) | The open-source framework — protocol, microkernel, CLI, SDK, production runtime, and the Console / Studio UI (`ui/`). Apache-2.0, no open-core asterisks. |
| ☁️ | [objectos](https://github.com/objectstack-ai/objectos) | Public home of the commercial platform — documentation ([docs.objectos.ai](https://docs.objectos.ai)), issue tracker, trademark policy. |
| 📇 | [hotcrm](https://github.com/objectstack-ai/hotcrm) | The reference app: a full enterprise CRM as typed metadata, with its size measured in CI. [Try it on StackBlitz](https://stackblitz.com/github/objectstack-ai/hotcrm), no install. |

## Try it in 60 seconds

```bash
npm create objectstack@latest my-app && cd my-app
npx os dev --ui   # → http://localhost:3000/_console/
```

Open the project in Claude Code (or any coding agent) and describe what the
business needs — the scaffold ships with the AI skills bundle and an
`AGENTS.md`, so the agent starts with the protocol's rules already loaded.
Prefer clicking to coding? Start online at [objectos.ai](https://www.objectos.ai).

---

<p align="center">
🌐 <a href="https://objectstack.ai">objectstack.ai</a> ·
📚 <a href="https://objectstack.ai/docs">Framework Docs</a> ·
🏢 <a href="https://docs.objectos.ai">ObjectOS Docs</a> ·
▶️ <a href="https://youtu.be/CX_FlOoOtr0">ObjectStack in 90 seconds</a> ·
✍️ <a href="https://www.objectos.ai/en/blog/">Blog</a>
</p>
