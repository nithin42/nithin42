# Hi there! I'm Nithin 👋

Senior Software Engineer focused on building robust developer tools, machine learning pipelines, and backend systems. I am passionate about building scalable C#/.NET backend services, writing clean, typed Python code, and contributing to open-source ecosystems.

---

### 🚀 Upstream Open-Source Contributions

| Organization & Project | Merged PRs | Engineering Impact & Core Fixes |
| :--- | :---: | :--- |
| <a href="https://github.com/feast-dev/feast"><img src="https://github.com/feast-dev.png" width="36" height="36" align="left" alt="Feast" /></a> **[Feast](https://github.com/feast-dev/feast)**<br><sub>Linux Foundation AI</sub><br><sub>`feast-dev/feast`</sub> | <img src="https://img.shields.io/badge/3_Merged-8957e5?style=flat-square&logo=git&logoColor=white"/><br><br>[![](https://img.shields.io/badge/%236711-white?style=flat-square&logo=github&logoColor=black)](https://github.com/feast-dev/feast/pull/6711)<br>[![](https://img.shields.io/badge/%236713-white?style=flat-square&logo=github&logoColor=black)](https://github.com/feast-dev/feast/pull/6713)<br>[![](https://img.shields.io/badge/%236712-white?style=flat-square&logo=github&logoColor=black)](https://github.com/feast-dev/feast/pull/6712) | • **Latency & Scalability:** Implemented async DynamoDB connection pre-warming (`describe_limits`) to eliminate ~20ms cold-start latency.<br>• **CI/CD & Protocol:** Downgraded & locked Model Context Protocol (MCP) pin (`1.29.0`) to resolve core protocol incompatibilities and unblock test pipelines.<br>• **Type Safety:** Corrected PyTorch `TorchTensor` TypeAlias runtime parsing in strict static analysis. |
| <a href="https://github.com/facebookresearch/hydra"><img src="https://github.com/facebookresearch.png" width="36" height="36" align="left" alt="Meta" /></a> **[Meta / Hydra](https://github.com/facebookresearch/hydra)**<br><sub>Meta AI Research (FAIR)</sub><br><sub>`facebookresearch/hydra`</sub> | <img src="https://img.shields.io/badge/2_Merged-8957e5?style=flat-square&logo=git&logoColor=white"/><br><br>[![](https://img.shields.io/badge/%233363-white?style=flat-square&logo=github&logoColor=black)](https://github.com/facebookresearch/hydra/pull/3363)<br>[![](https://img.shields.io/badge/%233350-white?style=flat-square&logo=github&logoColor=black)](https://github.com/facebookresearch/hydra/pull/3350) | • **Distributed Systems:** Fixed Ray cluster initialization bug that overrode shared object store memory on pre-existing clusters.<br>• **Config Engine:** Normalized group default paths containing slashes and resolved deferred interpolations early in the Defaults List. |

---

### 🛠️ Core Expertise & Technologies

* **Languages:** C#, Python (typing, performance), SQL, C++, Shell Scripting
* **Frameworks & Libraries:** .NET Core, Hydra, OmegaConf, PyTorch, NumPy, pandas
* **Developer Tools:** Git, Docker, Antlr4, Ruff, Black, Pyre, pytest
* **Systems & Infrastructure:** Backend architecture, CI/CD workflows, configuration engineering

---

### 🔭 Current Focus & Projects
* Contributing to core configurations and sweeper/launcher plugins in the Meta Open Source / Hydra ecosystem.
* Building reproducible, highly modular machine learning workflows.
* Let's connect! You can find my contributions on GitHub or reach out for collaborations.

---

*“Clean code always looks like it was written by someone who cares.”*
