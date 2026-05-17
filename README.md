# Regularized-Offline-Policy-Optimization-with-Posterior-Hybrid-Bayesian-Belief
Official implementation of the ICML 2026 regular paper "Regularized Offline Policy Optimization with Posterior Hybrid Bayesian Belief"
## Requirements
1. Linux is preferred.
2. Python 3.7 or greater.
3. Pytorch.
4. [MuJoCo](https://github.com/deepmind/mujoco/releases).

The environment can be built using the Dockerfile.
## Quick Start
For instance, use the following command to run hopper-medium-v2 benchmark.

```
python main.py --task=hopper-medium-v2
```

Detailed configuration settings are available in `utilities/arguments.py`.
