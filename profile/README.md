<div align="center">
  <img src="https://raw.githubusercontent.com/basebin/.github/main/profile/banner.jpg" alt="basebin" width="100%">
  
  <h1>basebin 🦌 — primitives for builders</h1>
  <p><strong><em>History is boring. Shipping is not.</em></strong></p>
  <p>Small, sharp, open-source building blocks — from GPU kernels to ML APIs. No nostalgia, just stuff you can fork and ship today.</p>
  
  <p>
    <a href="https://github.com/orgs/basebin/repositories"><img src="https://img.shields.io/badge/103-repos-0A84FF?style=flat-square" alt="repos"></a>
    <img src="https://img.shields.io/badge/kernels_%E2%80%A2_inference_%E2%80%A2_APIs_%E2%80%A2_SDKs-black?style=flat-square" alt="focus">
    <img src="https://img.shields.io/badge/stack-Python%20%7C%20C%2B%2B%20%7C%20Swift%20%7C%20Rust%20%7C%20TS-blue?style=flat-square" alt="stack">
    <img src="https://img.shields.io/badge/license-MIT_%2F_Apache--2.0-green?style=flat-square" alt="license">
  </p>

  <p>
    <a href="https://github.com/orgs/basebin/repositories"><strong>Explore All Repositories →</strong></a> &nbsp;•&nbsp;
    <a href="https://github.com/basebin/.github/issues">Request a primitive</a> &nbsp;•&nbsp;
    <a href="#-featured-labs">Featured Labs ↓</a>
  </p>
</div>

---

### ⚡ No history lecture

**basebin** isn't a museum. It's a workbench.

We publish the unglamorous primitives that make AI products real — GPU kernels, inference runtimes, API clients, SDKs, and the CLI/build glue in between. Each repo is small enough to read in one sitting, practical enough to reuse tomorrow.

> Study it. Fork it. Steal the good parts. Ship faster.

### 🧭 What we ship

| Pillar | What you get | Dive in |
| :--- | :--- | :--- |
| **⚙️ Compute & Kernels** | Low-level GPU work, inference, tiling | [`kernels`](https://github.com/basebin/kernels) `Swift` • [`bitinfer`](https://github.com/basebin/bitinfer) `C++` • [`mlxlm`](https://github.com/basebin/mlxlm) `Apple Silicon` • [`thread`](https://github.com/basebin/thread) `tiled pipeline` |
| **🧠 ML & Inference** | Frameworks, APIs, benchmarks | [`ml`](https://github.com/basebin/ml) `C++` • [`mlapi`](https://github.com/basebin/mlapi) `Python` • [`benchmark`](https://github.com/basebin/benchmark) `speech` • [`vesper`](https://github.com/basebin/vesper) `Gemini client` |
| **🛠️ DevX & Infra** | SDKs, CLIs, build anywhere | [`cli`](https://github.com/basebin/cli) • [`buildanywhere`](https://github.com/basebin/buildanywhere) • [`dotfiles`](https://github.com/basebin/dotfiles) • [`appsdk`](https://github.com/basebin/appsdk) • [`hautofix`](https://github.com/basebin/hautofix) |
| **✨ Apps & Experiments** | Reference apps, toys, probes | [`browser`](https://github.com/basebin/browser) `Dart/Flutter` • [`tts`](https://github.com/basebin/tts) • [`hub`](https://github.com/basebin/hub) • [`metal`](https://github.com/basebin/metal) `Swift` |

### 🔬 Featured Labs

| Repository | One-liner | Stack |
| :--- | :--- | :--- |
| [**kernels**](https://github.com/basebin/kernels) | Swift GPU kernels — fast, readable, hackable | `Swift` `Metal` |
| [**bitinfer**](https://github.com/basebin/bitinfer) | C++ inference framework, minimal dependencies | `C++` |
| [**thread**](https://github.com/basebin/thread) | Tiled image pipeline (tile → upscale → stitch) + Flask API | `C++` `Python` |
| [**ml**](https://github.com/basebin/ml) | Machine learning framework in C++ | `C++` |
| [**mlapi**](https://github.com/basebin/mlapi) | Python ML API — clean, typed, extensible | `Python` |
| [**mlxlm**](https://github.com/basebin/mlxlm) | M1/Apple Silicon inference tests & notes | `Python` |
| [**xaisdk**](https://github.com/basebin/xaisdk) | SDK + client libraries for xAI & friends | `Python/TS` |
| [**buildanywhere**](https://github.com/basebin/buildanywhere) | Cross-platform build tooling that just works | `Shell` |
| [**vesper**](https://github.com/basebin/vesper) | Minimal Gemini client | `Python` |
| [**metal**](https://github.com/basebin/metal) | Swift package notes & experiments | `Swift` |

> Want the full map? **[View all 103 repositories →](https://github.com/orgs/basebin/repositories)**

### 🚀 Quick start

```bash
# pick a primitive — e.g. the tiled inference pipeline
git clone https://github.com/basebin/thread.git && cd thread
# or the Python ML API
git clone https://github.com/basebin/mlapi.git && cd mlapi && pip install -e .

# list everything by language
gh repo list basebin --limit 103 --json name,primaryLanguage,description --jq '.[] | "\(.name) (\(.primaryLanguage.name)): \(.description)"'
```

### 🧪 Pick your stack

`Python` 27 • `TypeScript` 11 • `Shell` 9 • `C++` 7 • `JavaScript` 7 • `Swift` 7 • `C` 4 • `Dart` 3 • `Rust` 3 — and Haskell, Lean, Elixir, Ruby, Java for the curious.

Every repo is designed to be **read in <30 min, fork in <5 min, adapt in <1 day**.

### 🤝 Build with us

No roadmap theatre. Just open repos, open issues, open PRs.

- **Fork & experiment** — everything is MIT/Apache-2.0/BSD where possible
- **Open an issue** — request a primitive, report a papercut
- **Ship a PR** — small, focused PRs get merged fast

---

<div align="center">

**If history is boring, build the future.**

`fork` → `hack` → `ship` → `repeat`

<br>

[substack](https://basebin.substack.com) • [github](https://github.com/basebin) • [issues](https://github.com/basebin/.github/issues)

</div>
