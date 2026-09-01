## cairn

**An open-source control plane for governed ModelOps.**

Fine-tune, evaluate, promote, and serve models as single governed commands —
cost-capped before the GPU spins up, policy-gated, paused for human approval
where it matters, and audited end to end.

**Self-hosted by default:** your keys, your GPUs, your logs, nothing leaving
your perimeter. A **managed cloud** is in private beta for teams who would
rather not run it themselves — the engine is the same either way.

### Why governed?

The failures that hurt are the silent ones — data leakage found after the GPU
bill, an eval regression that ships because nothing blocked it, a model in
production with no record of who approved it. cairn turns each of those into a
loud, gated, audited stop, on the same command you already run.

### Where to start

| | |
|---|---|
| [cairndev.sh](https://cairndev.sh) | Overview and early-access waitlist |
| [docs.cairndev.sh](https://docs.cairndev.sh) | Architecture, CLI reference, governance model |
| [cairn](https://github.com/cairndev-sh/cairn) | The control plane — source opens at release, Apache 2.0 |

cairn is in **early access**. [Join the waitlist](https://cairndev.sh) for
access and release updates, or to ask about the managed private beta.
