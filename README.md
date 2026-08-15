# Hi there! I'm Nithin 👋

Senior Software Engineer focused on building robust developer tools, machine learning pipelines, and backend systems. I am passionate about building scalable C#/.NET backend services, writing clean, typed Python code, and contributing to open-source ecosystems.

---

### 🚀 Upstream Open-Source Contributions

| Organization & Repository | Merged PRs | Engineering Impact & Core Fixes |
| :--- | :---: | :--- |
| <img src="https://github.com/feast-dev.png" width="22" height="22" valign="middle" alt="Feast Logo" /> **[feast-dev/feast](https://github.com/feast-dev/feast)**<br><sub>Linux Foundation AI • Production ML Feature Store</sub><br><br>[![](https://img.shields.io/github/stars/feast-dev/feast?style=flat-square&logo=github&label=Stars)](https://github.com/feast-dev/feast)&nbsp;[![](https://img.shields.io/github/forks/feast-dev/feast?style=flat-square&logo=git&label=Forks)](https://github.com/feast-dev/feast) | <img src="https://img.shields.io/badge/3_Merged-8957e5?style=flat-square&logo=git&logoColor=white"/><br><br>[![](https://img.shields.io/badge/%236711-white?style=flat-square&logo=github&logoColor=black)](https://github.com/feast-dev/feast/pull/6711)<br>[![](https://img.shields.io/badge/%236713-white?style=flat-square&logo=github&logoColor=black)](https://github.com/feast-dev/feast/pull/6713)<br>[![](https://img.shields.io/badge/%236712-white?style=flat-square&logo=github&logoColor=black)](https://github.com/feast-dev/feast/pull/6712) | • **Latency & Scalability:** Implemented async DynamoDB connection pre-warming (`describe_limits`) to eliminate ~20ms cold-start latency.<br>• **CI/CD & Protocol:** Downgraded & locked Model Context Protocol (MCP) pin (`1.29.0`) to resolve core protocol incompatibilities and unblock test pipelines.<br>• **Type Safety:** Corrected PyTorch `TorchTensor` TypeAlias runtime parsing in strict static analysis. |
| <img src="https://github.com/facebookresearch.png" width="22" height="22" valign="middle" alt="Meta Logo" /> **[facebookresearch/hydra](https://github.com/facebookresearch/hydra)**<br><sub>Meta AI Research (FAIR) • Distributed Config Framework</sub><br><br>[![](https://img.shields.io/github/stars/facebookresearch/hydra?style=flat-square&logo=github&label=Stars)](https://github.com/facebookresearch/hydra)&nbsp;[![](https://img.shields.io/github/forks/facebookresearch/hydra?style=flat-square&logo=git&label=Forks)](https://github.com/facebookresearch/hydra) | <img src="https://img.shields.io/badge/2_Merged-8957e5?style=flat-square&logo=git&logoColor=white"/><br><br>[![](https://img.shields.io/badge/%233363-white?style=flat-square&logo=github&logoColor=black)](https://github.com/facebookresearch/hydra/pull/3363)<br>[![](https://img.shields.io/badge/%233350-white?style=flat-square&logo=github&logoColor=black)](https://github.com/facebookresearch/hydra/pull/3350) | • **Distributed Systems:** Fixed Ray cluster initialization bug that overrode shared object store memory on pre-existing clusters.<br>• **Config Engine:** Normalized group default paths containing slashes and resolved deferred interpolations early in the Defaults List. |

---

### 🛠️ Core Expertise & Technologies

* **Languages:** C#, Python (strict typing, async & performance), SQL, C++, Shell Scripting
* **AI & Data Systems:** Feast (Feature Stores), PyTorch, Ray, AWS DynamoDB, Redis, NumPy, pandas
* **Frameworks & Architecture:** .NET Core, Hydra, OmegaConf, FastAPI, gRPC, Model Context Protocol (MCP)
* **Developer Tooling & CI/CD:** Git, Docker, GitHub Actions, Ruff, mypy, Pyre, pytest, Antlr4

---

### 🔭 Current Focus & Projects
* Contributing to **Feast** (real-time feature stores, low-latency DynamoDB/Redis online stores, and Model Context Protocol).
* Enhancing core configurations and distributed launchers in the **Meta / Hydra** ecosystem.
* Building resilient, high-throughput backend services and reproducible ML pipelines.
* Open to collaborating on open-source ML infrastructure and distributed backend tools.

---

*“Clean code always looks like it was written by someone who cares.”*
