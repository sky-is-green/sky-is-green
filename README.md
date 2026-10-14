### Hi there, I'm Ricky 👋

# 🌍 sky-is-green

[![GitHub followers](https://img.shields.io/github/followers/sky-is-green?style=flat&label=Followers&logo=github)](https://github.com/sky-is-green?tab=followers)
[![Public repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fsky-is-green&query=%24.public_repos&style=flat&label=Public%20repos&logo=github)](https://github.com/sky-is-green?tab=repositories)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-SkyIsNotGreen-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/SkyIsNotGreen)
[![Reddit](https://img.shields.io/badge/Reddit-u%2FBotSympathiser-FF4500?style=flat&logo=reddit&logoColor=white)](https://www.reddit.com/user/BotSympathiser)

I'm a solo developer, assisted by AI, focused on long-context LLM competency:
local-first memory techniques, portable ways of interacting with models, and
making AI plug-&-play — an AI sysadmin capable of wiring into the host board's
firmware-level controls. Around that research I build an ever-growing software
suite of wired functions, tests, and logs, as the test-bed for bare-metal performance
of AI on Linux.

## 🚀 Featured Projects

**[Scion](https://github.com/sky-is-green/scion)** - Ternary quantization with trained corrections: ternarise the expert banks of a pretrained MoE in place, then recover the routing damage with small residual-stream corrections and router deltas trained by output-KD with the deployed quantizer in the loop. Ships **[Scion-35B-A3B](https://huggingface.co/SkyIsNotGreen/Scion-35B-A3B)** (11.34 GB / 2.61 bpw) and **[Scion-FlashNext-176B-A6B](https://huggingface.co/SkyIsNotGreen/Scion-FlashNext-176B-A6B)** (60.17 GB / 2.72 bpw), with task accuracy inside the ±2% noise band and the best PPL of the 2-bit class on preliminary testing.

[![Top language](https://img.shields.io/github/languages/top/sky-is-green/scion?style=flat&logo=python&logoColor=white)](https://github.com/sky-is-green/scion)
[![Last commit](https://img.shields.io/github/last-commit/sky-is-green/scion/main?style=flat&label=Last%20commit&logo=git)](https://github.com/sky-is-green/scion/commits/main)

**[HiveBench](https://github.com/sky-is-green/hivebench)** - Customisable harness with deep tool capabilities, capable of long-context curation using splinter-Memory with settings for fine-tune, plus the falsifiable evaluation suite Splinter-Memory was built upon and the test harness behind the Scion quantization releases (predictions P1–P11 with
measured verdicts).

[![Top language](https://img.shields.io/github/languages/top/sky-is-green/hivebench?style=flat&logo=python&logoColor=white)](https://github.com/sky-is-green/hivebench)
[![Last commit](https://img.shields.io/github/last-commit/sky-is-green/hivebench/main?style=flat&label=Last%20commit&logo=git)](https://github.com/sky-is-green/hivebench/commits/main)


## 🛠️ My Tech Stack & Tools

**LLM & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black) ![Transformers](https://img.shields.io/badge/Transformers-2C2255?style=flat) ![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat) ![Triton](https://img.shields.io/badge/Triton-4B8BBE?style=flat) ![JAX](https://img.shields.io/badge/JAX-2C8EBB?style=flat) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

**Systems & Performance**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white) ![ROCm](https://img.shields.io/badge/ROCm-ED1C24?style=flat&logo=amd&logoColor=white) ![OpenCL](https://img.shields.io/badge/OpenCL-2E8BC0?style=flat) ![Vulkan](https://img.shields.io/badge/Vulkan-A41E22?style=flat&logo=vulkan&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Web & Tooling**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat&logo=pnpm&logoColor=white) ![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Data & Testing**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat&logo=ruff&logoColor=black) ![Hypothesis](https://img.shields.io/badge/Hypothesis-BD1C2B?style=flat)

### 📬 Connect With Me

[![Hugging Face](https://img.shields.io/badge/Hugging_Face-SkyIsNotGreen-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/SkyIsNotGreen)
[![Reddit](https://img.shields.io/badge/Reddit-u%2FBotSympathiser-FF4500?style=flat&logo=reddit&logoColor=white)](https://www.reddit.com/user/BotSympathiser)

---

*Note: Unless otherwise stated, the source code for my current projects is hosted in private repositories for intellectual property and security reasons.*
