# 🌍 sky-is-green

*Taking systems apart, analysing them, and rebuilding them smaller.*

Independent LLM researcher focused on: long-horizon memory, ternary quantization,
LLM forensics & analysis, local-hosting on consumer hardware, and more.

<a href="https://sky-is-green.github.io/"><img src="https://raw.githubusercontent.com/sky-is-green/sky-is-green.github.io/main/assets/qr/avatar-512.png" width="180" alt="QR code pointing at the interactive portfolio" /></a>

### → **[the interactive portfolio](https://sky-is-green.github.io/)**

The scan above opens it: a phosphor-green one-pager where the work list is a
drum you scroll, the open projects slide sideways, and the arcade is playable.
Everything on it is built from the repos below.

[![GitHub followers](https://img.shields.io/github/followers/sky-is-green?style=flat&label=Followers&logo=github)](https://github.com/sky-is-green?tab=followers)
[![Public repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fsky-is-green&query=%24.public_repos&style=flat&label=Public%20repos&logo=github)](https://github.com/sky-is-green?tab=repositories)
[![Private repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsky-is-green%2Fsky-is-green%2Fmain%2Fprivate-repos.json&query=%24.count&style=flat&label=Private%20repos&logo=github)](https://github.com/sky-is-green?tab=repositories)

## 🚀 Featured projects

**[Scion](https://github.com/sky-is-green/scion)** — Ternary MoE quantization with trained corrections — the harness behind the released
[Scion-35B-A3B](https://huggingface.co/SkyIsNotGreen/Scion-35B-A3B) and
[Scion-FlashNext-176B-A6B](https://huggingface.co/SkyIsNotGreen/Scion-FlashNext-176B-A6B).

**[Splinter Memory](https://github.com/sky-is-green/splinter-memory)** — An external, managed-decay context-curation layer for long-horizon LLM conversations.

**[HiveBench](https://github.com/sky-is-green/hivebench)** — Evaluation suite and Studio sidecar for Splinter Memory.

**[Bonsai 2 ternary forensics](https://github.com/sky-is-green/bonsai2-ternary-forensics)** — Independent forensics on Bonsai 2 27B — recovering a ~2 bpw ternary model's format, basis, and quality gap.

**[PixelQR](https://github.com/sky-is-green/pixelqr)** — Pixel art that becomes a real, scannable QR code.
[Live on the site](https://sky-is-green.github.io/pixelqr/).

**[Strata](https://github.com/sky-is-green/Strata)** — Kernel fusions and speculative decoding in the Strata inference engine (fork work).

## 📂 Public repos

| repo | what it is | language |
| --- | --- | --- |
| [scion](https://github.com/sky-is-green/scion) | Ternary MoE quantization with trained corrections — harness + docs behind Scion-35B-A3B | Python |
| [splinter-memory](https://github.com/sky-is-green/splinter-memory) | An external, managed-decay context-curation layer for long-horizon LLM conversations | Python |
| [hivebench](https://github.com/sky-is-green/hivebench) | Evaluation suite for Splinter Memory (tests, testing, experiments) | Python |
| [bonsai2-ternary-forensics](https://github.com/sky-is-green/bonsai2-ternary-forensics) | Independent forensics of Bonsai 2 27B ternary quantization: format and basis recovery, the trained-weights residual, and the public PTQ calibration artifact | Python |
| [pixelqr](https://github.com/sky-is-green/pixelqr) | Pixel art that becomes a real, scannable QR code — a writable-canvas art-QR engine: zero random cells inside the drawing area, free payload-bit solving (GF(2)), six decode-verified render styles, no build step, no dependencies | JavaScript |
| [scrollpeak](https://github.com/sky-is-green/scrollpeak) | A scrollbar minimap for Firefox. Hover the scrollbar to see the whole page, magnify a section, click to jump | Python |
| [sky-is-green.github.io](https://github.com/sky-is-green/sky-is-green.github.io) | The portfolio — plan, avatar prototypes, and the site itself. Interactive piece built on PixelQR | JavaScript |
| [Strata](https://github.com/sky-is-green/Strata) | *(fork)* Qwen3.8-Flash-Next on any consumer hardware — Strata inference engine, OpenAI/Anthropic API on localhost | C++ |
| [prism-ml-llama.cpp](https://github.com/sky-is-green/prism-ml-llama.cpp) | *(fork)* LLM inference in C/C++ — MoE expert-residency and kernel-fusion experiments | C++ |
| [deepseek-harness](https://github.com/sky-is-green/deepseek-harness) | *(fork)* DeepSeek Harness: Everything is a Plugin — plugin and tooling work | TypeScript |
| [autogrid](https://github.com/sky-is-green/autogrid) | *(fork)* Turn any model into a full-size Ternary INTEGER model, free where the noise-floor math says it's free | Python |
| [huggingface.js](https://github.com/sky-is-green/huggingface.js) | *(fork)* Use Hugging Face with JavaScript | TypeScript |

## 🛠️ My tech stack & tools

**LLM & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black) ![Transformers](https://img.shields.io/badge/Transformers-2C2255?style=flat) ![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat) ![Triton](https://img.shields.io/badge/Triton-4B8BBE?style=flat) ![JAX](https://img.shields.io/badge/JAX-2C8EBB?style=flat) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

**Systems & performance**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white) ![ROCm](https://img.shields.io/badge/ROCm-ED1C24?style=flat&logo=amd&logoColor=white) ![OpenCL](https://img.shields.io/badge/OpenCL-2E8BC0?style=flat) ![Vulkan](https://img.shields.io/badge/Vulkan-A41E22?style=flat&logo=vulkan&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Web & tooling**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat&logo=pnpm&logoColor=white) ![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Data & testing**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat&logo=ruff&logoColor=black) ![Hypothesis](https://img.shields.io/badge/Hypothesis-BD1C2B?style=flat)

## 📬 Connect with me

[![Hugging Face](https://img.shields.io/badge/Hugging_Face-SkyIsNotGreen-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/SkyIsNotGreen)
[![Reddit](https://img.shields.io/badge/Reddit-u%2FBotSympathiser-FF4500?style=flat&logo=reddit&logoColor=white)](https://www.reddit.com/user/BotSympathiser)
[![Portfolio](https://img.shields.io/badge/Portfolio-sky--is--green.github.io-5df08a?style=flat&logo=github)](https://sky-is-green.github.io/)

---

*Note: Unless otherwise stated, the source code for my current projects is hosted in private repositories for intellectual property and security reasons.*
