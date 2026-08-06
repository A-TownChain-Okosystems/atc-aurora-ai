# 🌳 Architektur — atc-aurora-ai

> **Stand:** 2026-08-06 | **Version:** v1.0.0
> **Teil von:** [A-TownChain Ökosystem](https://github.com/A-TownChain-Okosystems)

## Beschreibung

Aurora AI Core — die zentrale KI-Schicht des A-TownChain Ökosystems. Agent-Runtime, LLM-Orchestrierung, Multi-Agent-Koordination, Memory, Tool-Use, Model-Hub. Bündelt die verstreuten AI-Module (core/ai/, ai_kernel, kai_routes) in einem dedizierten Repo. Implementiert die 12 Agenten-Rollen aus Regel 11.

## Metadaten

| Metrik | Wert |
|--------|------|
| Layer | L6 — AI Layer |
| Sprint | 3.2 |
| ATC-Standards | ATC-97, ATC-24, ATC-17, ATC-45 |
| Status | 🟢 AKTIV (Stubs) |
| Dateien | 17 |
| Zeilen | 468 |
| .atc | 17 |

## Komponenten-Übersicht

| Komponente | Beschreibung | Status |
|-----------|-------------|--------|
| `core/aurora_core.atc` | Zentrale AI-Initialisierung | 🔄 STUB |
| `core/agent_registry.atc` | Agent-Typ-Registrierung (12 Rollen) | 🔄 STUB |
| `core/model_hub.atc` | LLM-Modell-Registrierung und -Routing | 🔄 STUB |
| `runtime/llm_router.atc` | LLM-Request-Routing | 🔄 STUB |
| `runtime/agent_runtime.atc` | Agenten-Ausführungsumgebung | 🔄 STUB |
| `runtime/tool_executor.atc` | Sichere Tool-Ausführung | 🔄 STUB |
| `agents/knowledge_agent.atc` | Knowledge Agent (Wissen) | 🔄 STUB |
| `agents/architect_agent.atc` | Architect Agent (Architektur) | 🔄 STUB |
| `agents/coding_agent.atc` | Coding Agent (ATCLang) | 🔄 STUB |
| `agents/research_agent.atc` | Research Agent (Recherche) | 🔄 STUB |
| `agents/security_agent.atc` | Security Agent (Audit) | 🔄 STUB |
| `agents/orchestrator_agent.atc` | Orchestrator Agent (Koordination) | 🔄 STUB |
| `memory/agent_memory.atc` | Agenten-Gedächtnis (On-chain) | 🔄 STUB |
| `memory/context_window.atc` | Kontext-Fenster-Manager | 🔄 STUB |
| `orchestration/workflow_engine.atc` | Workflow-Engine | 🔄 STUB |
| `orchestration/sync_orchestrator.atc` | Daily Sync (16 Dienste) | 🔄 STUB |
| `orchestration/decision_handler.atc` | Decision-Verwaltung (AD-001-007) | 🔄 STUB |

## Verzeichnisstruktur

```
├── agents/ (6 files, 126 lines)
│   ├── architect_agent.atc (21 lines)
│   ├── coding_agent.atc (21 lines)
│   ├── knowledge_agent.atc (21 lines)
│   ├── orchestrator_agent.atc (21 lines)
│   ├── research_agent.atc (21 lines)
│   └── security_agent.atc (21 lines)
├── core/ (3 files, 94 lines)
│   ├── agent_registry.atc (33 lines)
│   ├── aurora_core.atc (25 lines)
│   └── model_hub.atc (36 lines)
├── memory/ (2 files, 59 lines)
│   ├── agent_memory.atc (31 lines)
│   └── context_window.atc (28 lines)
├── models/ (0 files, 0 lines)
├── orchestration/ (3 files, 95 lines)
│   ├── decision_handler.atc (30 lines)
│   ├── sync_orchestrator.atc (28 lines)
│   └── workflow_engine.atc (37 lines)
├── runtime/ (3 files, 94 lines)
│   ├── agent_runtime.atc (32 lines)
│   ├── llm_router.atc (32 lines)
│   └── tool_executor.atc (30 lines)
├── tools/ (0 files, 0 lines)
└── README.md (28 lines)
```

## Abhängigkeiten

- **ATCLang Stdlib** (atc-stdlib)
- **ATC VM** (atc-vm)
- **ATC Kernel** (atc-kernel)
- **ATCNet** (atcnet)

## Roadmap

| Phase | Aufgabe | Status |
|-------|---------|--------|
| Sprint 3.2 | Komponenten-Definition | ✅ ERLEDIGT |
| Sprint 3.2 | Architektur-Baum | ✅ ERLEDIGT |
| Sprint 3.2 | Stub-Dateien | ✅ ERLEDIGT |
| Sprint 3.2.1 | Implementierung | 📋 GEPLANT |
| Sprint 3.2.2 | Tests | 📋 GEPLANT |
| Sprint 3.2.3 | Dokumentation | 📋 GEPLANT |

---
*Auto-generiert 2026-08-06 · Aurora (MasterBrain · Base44)*
