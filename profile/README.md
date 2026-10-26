<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cairndev-sh/.github/main/profile/logo-dark.svg">
  <img src="https://raw.githubusercontent.com/cairndev-sh/.github/main/profile/logo.svg" alt="cairn" width="56">
</picture>

## cairn

**An open-source control plane for governed ModelOps.**

Fine-tune, evaluate, promote, and serve models as single governed commands —
cost-capped before the GPU spins up, policy-gated, paused for human approval
where it matters, and audited end to end.

**Self-hosted:** your keys, your GPUs, your logs, nothing leaving your
perimeter.

### Why governed?

The failures that hurt are the silent ones — data leakage found after the GPU
bill, an eval regression that ships because nothing blocked it, a model in
production with no record of who approved it. cairn turns each of those into a
loud, gated, audited stop, on the same command you already run.

### Where to start

| | |
|---|---|
| [cairndev.sh](https://cairndev.sh) | Overview and use cases |
| [demo.cairndev.sh](https://demo.cairndev.sh) | Live demo of the console |
| [docs.cairndev.sh](https://docs.cairndev.sh) | Architecture, CLI reference, governance model |
| [cairn](https://github.com/cairndev-sh/cairn) | The control plane: source, issues and releases, Apache 2.0 |
| [cairn-extensions](https://github.com/cairndev-sh/cairn-extensions) | Operator packs and domain packs, such as dataset preparation and fine-tuning, Apache 2.0 |

cairn is open source and in early development. Start with the
[quickstart](https://docs.cairndev.sh/quickstart/) or try the [live demo](https://demo.cairndev.sh).
