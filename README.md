# tiny-rl-reasoning

A small reasoning environment with a verifier, trained with a reward in PyTorch.

**Status:** scaffold (2026-10-16). Training and curves are not implemented yet. Start after [agent-eval-harness](https://github.com/gokulnathan66/agent-eval-harness) is public and runnable.

## What this will prove

A reviewer can run a training script and see a learning curve. This is a trained policy with a reward, not an API-only notebook.

- Environment with checkable answers: public clinical protocol questions or GSM8K-style math
- Training: PPO, GRPO, or REINFORCE in PyTorch on a small policy (LoRA on a small open model is enough)
- Plots: reward vs steps, eval accuracy vs steps, one ablation
- `REPORT.md`: problem, method, results, and what failed (1–2 pages)

The training method is one post-training paper, reproduced here. The paper note lives in this repo, not in a separate project.

## Run

Not runnable yet.

## License

MIT
