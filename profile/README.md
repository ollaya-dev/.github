<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ollaya-dev/.github/main/profile/logo-dark.svg">
    <img src="https://raw.githubusercontent.com/ollaya-dev/.github/main/profile/logo-light.svg" alt="Ollaya" width="88">
  </picture>
</p>

<h3 align="center">The decision layer for AI agents.</h3>

<p align="center">
  Ollaya runs open decision models on your own hardware, the way Ollama runs LLMs.<br>
  Typed questions in, calibrated answers out, in milliseconds: routing, guardrails, triage and tool approval without an LLM call.
</p>

<p align="center">
  <a href="https://ollaya.dev">Website</a> ·
  <a href="https://ollaya.dev/search">Models</a> ·
  <a href="https://bench.ollaya.dev">Bench</a> ·
  <a href="https://ollaya.dev/docs">Docs</a> ·
  <a href="https://github.com/ollaya-dev/ollaya/releases">Releases</a> ·
  <a href="https://huggingface.co/ollaya-dev">Hugging Face</a>
</p>

```sh
curl -fsSL https://ollaya.dev/install.sh | sh
ollaya run winnow:e4b --preset triage "I was charged twice this month and want a refund."
```

29 model families, from millisecond encoders that run on a CPU (`laya`, `nli`, `gliclass`, `von`, `decima`) to
decoders that take a GPU (`winnow`, `pplx-decider`, `clef`, `jeeves`, `nimble`, `kev`, `jeb`, `d3` and more), behind a
self-hosted, Jev-compatible API. Their accuracy, calibration and speed on our own GPUs and CPUs, with the raw data,
are at [bench.ollaya.dev](https://bench.ollaya.dev).

Weights always come from their authors' own Hugging Face repositories, pinned to a commit and
verified by sha256. Ollaya never re-hosts them.

Created and maintained by [Mert Cobanov](https://github.com/cobanov) ([@mertcobanov](https://x.com/mertcobanov)).
Apache-2.0. Ollaya is an independent project, not affiliated with Ollama or TypeSafe.
