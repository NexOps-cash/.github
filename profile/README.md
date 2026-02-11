# 🌌 NexOps Protocol
### *The Intelligent Infrastructure Layer for Smart Contract Operations*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Stack: Bitcoin Cash](https://img.shields.io/badge/Blockchain-Bitcoin%20Cash-green)](https://bitcoincash.org/)
[![Layer: AI](https://img.shields.io/badge/Layer-AI--Powered-blueviolet)](https://gemini.google.com/)

NexOps Protocol is a high-performance, AI-driven development and operations layer designed to streamline the lifecycle of Bitcoin Cash (BCH) smart contracts. By bridging the gap between natural language intent and low-level CashScript execution, NexOps empowers developers and organizations to build secure, audited, and scalable DeFi protocols with unprecedented speed.

---

## 🚀 Key Features

- **🧠 AI-Assisted Contract Generation**: Transform complex business logic into validated CashScript code using state-of-the-art LLMs (Gemini, Groq).
- **🛡️ Automated Audit Engine**: Real-time security scanning and vulnerability detection tailored for the BCH VM (Bitauth).
- **⚡ Unified Deployment Pipeline**: Seamlessly bridge from development to mainnet with integrated WalletConnect support and automated fee estimation.
- **📊 Operational Intelligence**: Deep visibility into contract states, UTXO management, and protocol health via an intuitive workbench.
- **🛠️ Developer-Centric IDE**: Monaco-powered editor with full syntax highlighting, real-time compilation, and an integrated debugging console.

---

## 🏗️ Architecture

NexOps is built on a modular "Nexus" architecture that prioritizes security and developer experience:

- **Nexus Frontend**: A polished React + Vite application utilizing Tailwind CSS for a premium, high-density dashboard experience.
- **Inference Layer**: Pluggable AI backend supporting advanced reasoning for contract generation and audit report synthesis.
- **Blockchain Interface**: Direct integration with `libauth` and `electrum-cash` for robust network interactions and hardware wallet compatibility.

---

## 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Framework** | React 18, Vite, TypeScript |
| **Styling** | Tailwind CSS (Nexus Design System) |
| **Smart Contracts** | CashScript, Bitcoin Cash VM |
| **AI Layer** | Google Gemini (SDK), Groq SDK |
| **Communication** | WalletConnect, Electrum Network |
| **IDE Core** | Monaco Editor, XTerm.js |

---

# NexOps MCP: The Intelligence Layer for Secure BCH Covenants

NexOps MCP (Model Context Protocol) is the authoritative intelligence core of the NexOps ecosystem. It transitions AI reasoning out of the peripheral IDE and into a centralized, specialized, and safety-hardened server dedicated to the generation of secure Bitcoin Cash (BCH) smart contracts.

## 🎯 Mission

To provide a deterministic, safety-first code generation pipeline that eliminates common vulnerabilities in Cashtokens and BCH covenants by enforcing a "Negative Type System" through semantic anti-pattern detection.

## 🏗️ Core Architecture

NexOps MCP is built on a tiered architecture that separates structural intent from logic implementation, wrapped in a strict security baseline.

### 1. The Architect (Phase 1)
Responsible for structural skeleton generation. It defines the "shape" of a contract (parameters, functions, storage) without implementing logic, ensuring the high-level design is sound before a single line of script is written.

### 2. The Engineer (Phase 2)
The logic implementation core. It transforms skeletons into fully functional CashScript code by drawing from an authoritative **Knowledge Base** of production-tested patterns and security rules.

### 3. The Safety Layer (Anti-Pattern Enforcer)
A rigorous "Negative Type System" that semantically analyzes generated code for known exploitable patterns.
- **Authoritative**: If a violation is detected, the code is REJECTED.
- **Semantic**: Uses AST analysis (not string matching) to understand logic flow.
- **Explainable**: Provides detailed reports on why code is unsafe and which BCH invariants were violated.

### 4. The Knowledge Layer
A curated library of Bitcoin Cash domain expertise:
- **Security Rules**: 18+ critical rules for covenant safety.
- **Secure Patterns**: Production-ready snippets for validation, auth, and state management.
- **Templates**: Reference implementations for standard contract types (Escrows, Vaults, DAOs).

## 🛠️ Technology Stack

- **Core**: Python 3.11+
- **API Framework**: FastAPI
- **Real-time Communication**: WebSockets (JSON-RPC style)
- **Validation**: Pydantic v2
- **Testing**: Pytest (Unit & Integration)
- **Security Logic**: Custom CashScript AST Parser & Semantic Evaluator

## 🤝 NexOps Integration

NexOps MCP is designed to be the "brain" behind the NexOps IDE. While the IDE handles UI/UX and user interaction, the MCP server handles:
1.  **Context-Aware Reasoning**: Injecting BCH-specific constraints into LLM prompts.
2.  **Security Audits**: Real-time checking of user-written or AI-generated code.
3.  **Knowledge Retrieval**: Providing the IDE with authoritative patterns on-demand.

---

## 🏁 Getting Started

### Prerequisites

- **Node.js**: v18.x or higher
- **Package Manager**: npm or yarn
- **Wallet**: A BCH-compatible wallet (supporting WalletConnect) for deployment features.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nexops-protocol/nexops-core.git
   cd nexops-core
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Environment Variables:
   Create a `.env.local` file based on the provided configuration:
   ```env
   VITE_GEMINI_API_KEY=your_key_here
   VITE_GROQ_API_KEY=your_key_here
   ```

4. Launch the Development Server:
   ```bash
   npm run dev
   ```
---

*Part of the NexOps ecosystem - building the future of secure decentralized finance on Bitcoin Cash.*

---

## 🗺️ Roadmap

- [ ] **Q3 2025**: Multi-contract composition support (linking multiple scripts).
- [ ] **Q4 2025**: Integrated automated testing suite with BCH-sandbox.
- [ ] **Q1 2026**: "One-Click Protocol" templates for common DeFi primitives (DEX, Lending, Stablecoins).
- [ ] **Q2 2026**: NexOps API for external integration into CI/CD pipelines.

---

## 🤝 Contributing

We welcome contributions from the community! Please read our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Built with ❤️ by the NexOps Foundation Team
</p>
