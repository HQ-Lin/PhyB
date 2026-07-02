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

## Citation
```
@inproceedings{
lin2026regularized,
title={Regularized Offline Policy Optimization with Posterior Hybrid Bayesian Belief},
author={Hongqiang Lin and Pengfei Wang and Nenggan Zheng},
booktitle={Forty-third International Conference on Machine Learning},
year={2026},
url={https://openreview.net/forum?id=v8BF1g3u8r}
}
```
