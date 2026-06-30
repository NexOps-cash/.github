# 🌌 NexOps Protocol

### Building trustworthy AI-assisted smart contract infrastructure for Bitcoin Cash.

<p align="center">

[![BCH-1 Hackcelerator](https://img.shields.io/badge/BCH--1%20Hackcelerator-🏆%20Overall%20Winner-success?style=for-the-badge)]()
[![Bitcoin Cash](https://img.shields.io/badge/Blockchain-Bitcoin%20Cash-green?style=for-the-badge)](https://bitcoincash.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

</p>

---

## The Problem

Large language models are becoming increasingly capable of writing software.

Smart contracts are no exception.

Today, AI can generate contracts that compile, look convincing, and even pass basic checks. Yet they may still contain subtle vulnerabilities capable of permanently locking funds, inflating tokens, or introducing unintended spending paths.

On an irreversible blockchain, those mistakes are permanent.

The challenge is no longer:

> **"Can AI generate smart contracts?"**

The challenge is:

> **"When should developers actually trust AI-generated smart contracts?"**

NexOps was built around that question.

---

# Why NexOps Exists

When we first started experimenting with AI-assisted CashScript generation, we believed the biggest limitation was training data.

CashScript is a relatively small language compared to Solidity, so language models often generated contracts that wouldn't even compile.

As prompting, retrieval, compiler feedback, and repair loops improved, something unexpected happened.

The contracts started compiling.

But compiling wasn't enough.

Many contracts still misunderstood spending paths, token ownership, or covenant behavior. They appeared correct while quietly introducing subtle security risks.

That completely changed our direction.

Instead of trying to build an AI that never makes mistakes, NexOps assumes AI **will** make mistakes—and surrounds it with infrastructure designed to detect, explain, and repair them before deployment.

Generation is only one step.

Trust is the real product.

---

# What is NexOps?

NexOps is an AI-assisted developer infrastructure platform for Bitcoin Cash smart contracts.

Instead of relying on a single language model response, NexOps combines multiple layers of validation before a contract reaches deployment.

These layers include:

- AI-assisted contract generation
- Deterministic structural analysis
- Security rule enforcement
- Semantic reasoning
- Automated repair
- Continuous benchmarking
- Deployment guardrails

Together, they help developers move faster **without lowering security standards.**

---

# Repository Structure

This organization contains several independent components that work together.

| Project | Purpose |
|---------|----------|
| **NexIDE** | AI-assisted development environment for generating, auditing and deploying CashScript contracts |
| **NexOps MCP** | Core intelligence engine responsible for guarded generation, auditing and repair |
| **NexKB** | Structured knowledge base containing contract patterns, documentation and benchmark data |

Repositories

- 🔹 NexIDE  
  https://github.com/NexOps-cash/nexops

- 🔹 NexOps MCP  
  https://github.com/NexOps-cash/nexops-mcp

- 🔹 NexKB  
  https://github.com/NexOps-cash/nexkb

---

# Design Philosophy

NexOps is built around one principle.

> **AI should propose. Infrastructure should decide.**

Language models are excellent at generating possibilities.

Infrastructure is responsible for determining whether those possibilities are safe enough to deploy.

Instead of replacing deterministic engineering with AI, NexOps combines both.

Each layer compensates for the weaknesses of the others.

The result is a development workflow that is both faster and substantially more trustworthy than prompting alone.

---

# Core Capabilities

## 🤖 AI-assisted Contract Generation

Generate CashScript contracts directly from natural language requirements.

Rather than exposing raw LLM output to developers, generation is guided through structured prompts, protocol knowledge, compiler feedback, and iterative refinement.

---

## 🛡 Security Analysis

Every generated contract passes through deterministic security analysis before semantic evaluation begins.

This detects structural issues that language models frequently overlook.

Examples include:

- Missing output binding
- Authority validation
- Token category consistency
- Value preservation
- Timelock enforcement
- Constructor validation
- Dangerous language patterns

---

## 🧠 Semantic Review

Structural correctness does not guarantee logical correctness.

NexOps therefore performs an additional semantic evaluation that compares contract behavior against the developer's original intent.

Questions include:

- Does the contract enforce the intended spending rules?
- Could funds become permanently locked?
- Can an attacker bypass expected conditions?
- Does token behavior match the requested design?

---

## 🔄 Automated Repair

Rather than stopping after detecting issues, NexOps attempts to repair them.

Generation → Analysis → Repair forms a continuous feedback loop until deployment requirements are satisfied.

Developers remain in control throughout the process.

---

## 📊 Benchmarking

Every improvement to NexOps is measured.

Changes are continuously evaluated across representative BCH contract patterns to ensure progress is genuine rather than anecdotal.

The goal is not simply better generations.

The goal is measurable improvements in correctness, security and developer trust.
