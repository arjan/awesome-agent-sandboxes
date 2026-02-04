# Awesome Agent Sandboxes

A curated list of **code-execution sandboxing solutions for AI/LLM agents** (cloud sandboxes, self-hosted runtimes, microVM orchestration, and local CLI sandboxers).

## Managed cloud solutions

- [E2B](https://github.com/e2b-dev/E2B) - Open-source secure cloud runtime for AI agents with Linux OS, filesystem, and command execution.
- [AgentSphere](https://www.agentsphere.run/) - AI-native cloud infrastructure with microVM sandboxes for secure LLM code execution and MCP integration.
- [Runloop](https://www.runloop.ai/) - Fast development environments ("Devboxes") for AI agents with snapshots, repo connections, and 2x faster execution.
- [Modal Sandboxes](https://modal.com/docs/guide/sandboxes) - Programmatic sandboxes for untrusted code at massive scale with sub-second startup and fine-grained controls.
- [Deno Sandboxes](https://docs.deno.com/sandboxes/) - Instant Linux microVMs with millisecond boot times for safely running untrusted code.
- [Daytona](https://www.daytona.io/docs/en/sandboxes/) - Open-source infrastructure for AI-generated code execution in isolated sandbox environments.
- [Sprites](https://sprites.dev/) - Persistent Firecracker VM environments with hardware isolation, exec sessions, and checkpoint/restore.
- [Cognitora](https://www.cognitora.dev/) - AI agent compute platform with sub-second Firecracker microVM startup and hardware-level isolation.
- [exe.dev](https://exe.dev/) - Subscription-based Ubuntu VMs starting in 2 seconds, designed for running coding agents with minimal supervision.
- [YepCode Run](https://yepcode.io/run) - Browser-based serverless runtime for executing JavaScript and Python code in secure sandboxes.
- [shellbox.dev](https://shellbox.dev/) - Instant Linux boxes accessible via SSH with persistent state and usage-based pricing.

## Self-hosted / open-source sandbox environments (agent-ready)

- [AIO Sandbox](https://github.com/agent-infra/sandbox) - All-in-one Docker container combining browser, terminal, VS Code, Jupyter, and MCP in a shared filesystem.
- [Sandboxer](https://github.com/ammmir/sandboxer) - Forkable code execution server designed for LLMs, agents, and developers.
- [Kubernetes Agent Sandbox](https://github.com/kubernetes-sigs/agent-sandbox) - Kubernetes APIs with pluggable isolation backends (gVisor/Kata) for secure agent workloads at scale.
- [Arrakis](https://github.com/abshkbh/arrakis) - Self-hosted agent sandbox with microVM isolation, snapshots, backtracking, and MCP support.
- [Bouvet](https://github.com/vrn21/bouvet) - Agent sandbox implementation in Rust with Docker and Terraform support.

## Local CLI sandboxing (developer machine safety rails)

- [Fence](https://github.com/Use-Tusk/fence) - Lightweight sandbox for CLI commands with network and filesystem restrictions using OS-native tools.
- [Landrun](https://github.com/Zouuup/landrun) - Landlock-based sandboxing for Linux processes without root privileges or containers.
- [nono](https://huggingface.co/blog/lukehinds/nono-agent-sandbox) - Capability-based security shell using Landlock/Seatbelt for safe AI agent execution.
- [yolo-cage](https://github.com/borenstein/yolo-cage) - Run AI coding agents with strict anti-exfiltration constraints to prevent secret theft.

## Agent-in-a-box wrappers (opinionated sandboxes for coding agents)

- [Yolobox](https://github.com/finbarr/yolobox) - Run AI coding agents in isolated Docker containers while protecting your home directory.
- [VibeKit](https://docs.vibekit.sh/) - SDK for embedding AI coding agents with support for multiple sandbox providers (E2B, Daytona, Modal, etc.).

## MicroVM orchestration & runtimes (building blocks)

- [Flintlock](https://github.com/liquidmetal-dev/flintlock) - MicroVM lifecycle management backed by containerd for building higher-level sandbox solutions.
- [Volant](https://github.com/volantvm/volant) - Modular orchestration engine for microVMs with ~200ms cold start and Docker-like simplicity.
- [Capsule](https://github.com/bots-garden/capsule) - WASM runners (CLI/HTTP) for executing WebAssembly modules with WASI support.

## Protocols, routing layers, and "meta" sandboxes

- [ComputeSDK](https://www.computesdk.com/) - Universal API for creating and running sandboxes across multiple cloud providers with auto-detection.
- [Sandbox Agent](https://github.com/rivet-dev/sandbox-agent) - Universal API for automatic coding agents supporting Claude Code, Codex, OpenCode, and Amp.
- [pctx](https://github.com/portofcontext/pctx) - Execution layer for agentic tool calls with type-checked code running in secure Deno sandboxes.
- [pctx-sandbox](https://github.com/portofcontext/pctx-py-sandbox) - Python decorator for executing untrusted code in isolated sandboxes with defense-in-depth security.

## Browser & web-agent sandboxing (focused)

- [Agents.one Playground](https://agents.one/playground) - Upload Python agents and share public playground links for zero-install testing.
- [AI Agent Sandbox](https://agentsandbox.net/) - Run Python and JavaScript agents directly in the browser using Pyodide.

## Security testing & research (adjacent but relevant)

- [AgentFence](https://github.com/agentfence/agentfence) - Open-source platform for automatically testing AI agent security vulnerabilities like prompt injection and secret leakage.
- [ceLLMate](https://arxiv.org/abs/2512.12594) - Browser-level sandboxing framework protecting AI agents from prompt injection attacks (research paper).
- [Jazzberry](https://jazzberry.ai/) - GitHub app that runs code in microVM sandboxes to automatically detect bugs in pull requests.

## More notable projects found during research

- [Microsandbox](https://github.com/zerocore-ai/microsandbox) - Self-hosted sandboxes with VM-level isolation, under 200ms boot times, and built-in MCP server.
- [Enclave](https://github.com/agentfront/enclave) - Secure JavaScript sandbox for AI agents protecting against code injection and prototype pollution.
- [SandboxAI](https://github.com/substratusai/sandboxai) - Run AI-generated code in isolated sandboxes with multi-cloud infrastructure support.
- [Novita Sandbox](https://novita.ai/docs/guides/sandbox-agent-runtime-introduction) - Lightweight framework for deploying AI agents with SDK decorators and one-click deployment.
- [Browser Use Sandboxes](https://docs.browser-use.com/customize/sandbox/quickstart) - Cloud-based sandbox for production browser automation with agent and LLM management.
- [BlueRock Agent Sandbox](https://www.bluerock.io/products/agent-sandbox) - Commercial sandbox with full MCP visibility, action-level tracing, and container isolation.

## Contributing

- Prefer adding a **canonical link** (official docs or GitHub repo) and a **one-line description**.
- If it's open source, include **license** when known.
- If you add a tool, please also add a short tag like **microVM**, **container**, **WASM**, **Landlock**, **browser**, or **managed** to help keep sections tidy.
