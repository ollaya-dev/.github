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
  <a href="https://ollaya.dev/results">Results</a> ·
  <a href="https://ollaya.dev/docs">Docs</a> ·
  <a href="https://github.com/ollaya-dev/ollaya/releases">Releases</a> ·
  <a href="https://huggingface.co/ollaya-dev">Hugging Face</a>
</p>

```sh
curl -fsSL https://ollaya.dev/install.sh | sh
ollaya run winnow:e4b --preset triage "I was charged twice this month and want a refund."
```

19 model families, from millisecond encoders that run on a CPU (`laya`, `nli`, `gliclass`, `von`, `decima`) to
decoders that take a GPU (`winnow`, `clef`, `kev`, `decider`, `nimble`, `jeb`, `jeeves`, `cygnet`, `snap`, `arbiter` and more).
Their accuracy, calibration and speed on our own GPUs and CPUs, with the raw data, are at
[ollaya.dev/results](https://ollaya.dev/results).

Weights always come from their authors' own Hugging Face repositories, pinned to a commit and
verified by sha256. Ollaya never re-hosts them.

Created and maintained by [Mert Cobanov](https://github.com/cobanov) ([@mertcobanov](https://x.com/mertcobanov)).
Apache-2.0. Ollaya is an independent project, not affiliated with Ollama or TypeSafe.
