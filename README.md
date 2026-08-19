# Awesome Agent Sandboxes

A curated list of **code-execution sandboxing solutions for AI/LLM agents**.

## Cloud

- [E2B](https://github.com/e2b-dev/E2B) - Open-source cloud runtime with Linux OS and SDK support.
- [AgentSphere](https://www.agentsphere.run/) - MicroVM sandboxes with MCP integration for secure LLM code execution.
- [CreateOS](https://createos.sh) - MicroVMs with pause-to-snapshot, fork-based branching, and private overlay networking for multi-agent systems. [SDK](https://github.com/NodeOps-app/createos-sandbox-sdk).
- [Runloop](https://www.runloop.ai/) - Fast devboxes with snapshots and repo connections.
- [Modal Sandboxes](https://modal.com/docs/guide/sandboxes) - Programmatic sandboxes at massive scale with sub-second startup, snapshotting, and fine-grained networking controls.
- [Deno Sandboxes](https://docs.deno.com/sandboxes/) - Millisecond boot times.
- [Sprites](https://sprites.dev/) - Persistent Firecracker VMs with exec sessions and checkpoint/restore capabilities.
- [Cognitora](https://www.cognitora.dev/) - Firecracker microVMs with hardware-level isolation.
- [exe.dev](https://exe.dev/) - 2-second Ubuntu VMs for coding agents.
- [YepCode Run](https://yepcode.io/run) - Serverless JavaScript/Python execution with enterprise-grade sandboxing.
- [shellbox.dev](https://shellbox.dev/) - SSH-accessible Linux boxes.
- [Novita Sandbox](https://novita.ai/docs/guides/sandbox-agent-runtime-introduction) - Agent deployment framework with SDK decorators and one-click configuration.
- [BlueRock Agent Sandbox](https://www.bluerock.io/products/agent-sandbox) - Commercial sandbox with full MCP visibility and action-level tracing.
- [Tenki Sandbox](https://tenki.cloud/products/sandbox) - Hardware-isolated Linux VMs with warm-start sessions, snapshot/fork, and multi-language SDKs.

## Self-hosted / Open Source

- [AIO Sandbox](https://github.com/agent-infra/sandbox) - All-in-one container with browser, terminal, VS Code, Jupyter, and MCP.
- [Sandboxer](https://github.com/ammmir/sandboxer) - Forkable server for LLMs and agents.
- [Kubernetes Agent Sandbox](https://github.com/kubernetes-sigs/agent-sandbox) - Kubernetes APIs with pluggable isolation backends (gVisor/Kata) for secure agent workloads at scale.
- [Arrakis](https://github.com/abshkbh/arrakis) - MicroVM isolation with snapshots and backtracking.
- [Bouvet](https://github.com/vrn21/bouvet) - Rust-based sandbox.
- [Microsandbox](https://github.com/zerocore-ai/microsandbox) - Self-hosted with VM-level isolation and under 200ms boot times.
- [SandboxAI](https://github.com/substratusai/sandboxai) - Multi-cloud infrastructure for AI-generated code.
- [Daytona](https://www.daytona.io/docs/en/sandboxes/) - Open-source infrastructure with SDK/CLI.
- [Fence](https://github.com/Use-Tusk/fence) - Lightweight CLI sandbox with network and filesystem restrictions using OS-native tools.
- [Landrun](https://github.com/Zouuup/landrun) - Landlock-based sandboxing without root.
- [nono](https://huggingface.co/blog/lukehinds/nono-agent-sandbox) - Capability-based shell using kernel-level security primitives.
- [yolo-cage](https://github.com/borenstein/yolo-cage) - Anti-exfiltration sandbox.
- [Yolobox](https://github.com/finbarr/yolobox) - Docker containers protecting home directory.
- [Flintlock](https://github.com/liquidmetal-dev/flintlock) - MicroVM lifecycle management backed by containerd for building higher-level solutions.
- [Volant](https://github.com/volantvm/volant) - MicroVM orchestration with ~200ms cold start.
- [Capsule](https://github.com/bots-garden/capsule) - WASM runners.
- [Enclave](https://github.com/agentfront/enclave) - JavaScript sandbox preventing code injection and prototype pollution.
- [Sandbox Agent](https://github.com/rivet-dev/sandbox-agent) - Universal API for Claude Code, Codex, OpenCode, and Amp.
- [pctx](https://github.com/portofcontext/pctx) - Execution layer with type-checked Deno sandboxes.
- [pctx-sandbox](https://github.com/portofcontext/pctx-py-sandbox) - Python decorator for untrusted code.
- [AgentFence](https://github.com/agentfence/agentfence) - Security testing platform for prompt injection and secret leakage vulnerabilities.
- [OpenServ](https://github.com/openserv-labs/sdk) - TypeScript framework for autonomous agents.
- [AgentBox](https://github.com/madarco/agentbox) - Run coding agents (Claude Code, Codex, OpenCode) in parallel sandboxed VMs — local Docker (default), self-hosted, or cloud (Hetzner, Daytona, Vercel, E2B, DigitalOcean). Sub-1s checkpoints, per-box browser/VS Code/shells, git credentials kept on the host.

## Others

- [Agents.one Playground](https://agents.one/playground) - Upload Python agents and share public playground links for zero-install testing.
- [AI Agent Sandbox](https://agentsandbox.net/) - Run agents in-browser with Pyodide.
- [Browser Use Sandboxes](https://docs.browser-use.com/customize/sandbox/quickstart) - Production browser automation.
- [ComputeSDK](https://www.computesdk.com/) - Universal API across multiple cloud providers with automatic provider detection.
- [VibeKit](https://docs.vibekit.sh/) - SDK supporting E2B, Daytona, Modal, and other providers.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
