<div align="center">

<img src="https://github.com/AgentEvalHQ/.github/blob/main/profile/AEHQ.png?raw=true" alt="AgentEvalHQ" width="300" />

# AgentEvalHQ

### Where AI Agents Prove Their Worth

**The open-source home of AgentEval — the comprehensive .NET evaluation toolkit for AI agents.**

[![AgentEval](https://img.shields.io/badge/AgentEval-Core_Toolkit-blue?style=for-the-badge)](https://github.com/AgentEvalHQ/AgentEval)
[![CLI](https://img.shields.io/badge/AgentEval.Cli-CLI_Tool-green?style=for-the-badge)](https://github.com/AgentEvalHQ/AgentEval.Cli)
[![Gatekeeper](https://img.shields.io/badge/AgentEval.Gatekeeper-PR_Quality_Gate-orange?style=for-the-badge)](https://github.com/AgentEvalHQ/AgentEval.Gatekeeper)

</div>

---

## What is AgentEval?

AgentEval is the comprehensive .NET evaluation toolkit for AI agents — **tool usage validation, RAG quality metrics, stochastic evaluation, behavioral policies, and model comparison** — built first for [Microsoft Agent Framework (MAF)](https://github.com/microsoft/agents).

What **RAGAS** and **DeepEval** do for Python, **AgentEval** does for .NET.

## 🚀 Our Projects

| Repository | Description |
|-----------|-------------|
| [**AgentEval**](https://github.com/AgentEvalHQ/AgentEval) | The core evaluation toolkit — metrics, assertions, tracing, benchmarking |
| [**AgentEval.Cli**](https://github.com/AgentEvalHQ/AgentEval.Cli) | Command-line interface — evaluate from your terminal |
| [**AgentEval.Gatekeeper**](https://github.com/AgentEvalHQ/AgentEval.Gatekeeper) | AI-powered PR quality gate — every agent earns its merge |

## ⚡ Quick Start

```bash
dotnet add package AgentEval
// Evaluate whether your AI agent calls the right tools
result.ToolUsage!.Should()
    .HaveCalledTool("SearchFlights")
        .BeforeTool("BookFlight")
    .And()
    .HaveNoErrors();
```

## 📖 Resources

- 🌐 [Documentation](https://agenteval.dev)
- 📦 [NuGet Package](https://www.nuget.org/packages/AgentEval)
- 💬 [Discussions](https://github.com/AgentEvalHQ/AgentEval/discussions)
- 🐛 [Report Issues](https://github.com/AgentEvalHQ/AgentEval/issues)

## 🤝 Contributing

We welcome contributions! Check out each repository's `CONTRIBUTING.md` for guidelines.

---

<div align="center">

*Stop guessing if your AI agent works. Start proving it.*

**MIT Licensed** · Built with ❤️ for the .NET community

</div>