<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ollaya-dev/.github/main/profile/logo-dark.png">
    <img src="https://raw.githubusercontent.com/ollaya-dev/.github/main/profile/logo-light.png" alt="Ollaya" width="96">
  </picture>
</p>

<h3 align="center">Run open decision models locally.</h3>

<p align="center">
  Typed questions in, calibrated answers out, in milliseconds.<br>
  One binary, models pulled by name and a TypeSafe-compatible API, the way Ollama runs LLMs.
</p>

<p align="center">
  <a href="https://ollaya.dev">Website</a> ·
  <a href="https://ollaya.dev/search">Models</a> ·
  <a href="https://ollaya.dev/docs">Docs</a> ·
  <a href="https://github.com/ollaya-dev/ollaya/releases">Releases</a> ·
  <a href="https://huggingface.co/ollaya-dev">Hugging Face</a>
</p>

```sh
curl -fsSL https://ollaya.dev/install.sh | sh
ollaya run laya --preset triage "I was charged twice this month and want a refund."
```

| Model | Author | |
|---|---|---|
| [`laya`](https://ollaya.dev/library/laya) | Convai Innovations | The fastest: 8–10 ms for five questions on an RTX 4090. English and 100+ languages. |
| [`decider`](https://ollaya.dev/library/decider) | Mapika | The most accurate: Qwen3.5 decoders, 2B and 0.8B. |
| [`nli`](https://ollaya.dev/library/nli) | Moritz Laurer | Zero-shot NLI classifiers, the most accurate encoder. |
| [`gliclass`](https://ollaya.dev/library/gliclass) | Knowledgator | Instruction-following zero-shot classifier. |

Weights always come from their authors' own Hugging Face repositories, pinned to a commit and
verified by sha256. Ollaya never re-hosts them.

Apache-2.0. Ollaya is an independent project, not affiliated with Ollama or TypeSafe.
