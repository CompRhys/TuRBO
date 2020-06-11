## Overview

This is the code-release for the TuRBO algorithm from ***Scalable Global Optimization via Local Bayesian Optimization*** appearing in NeurIPS 2019. This is an implementation for the noise-free case and may not work well if observations are noisy as the center of the trust region should be chosen based on the posterior mean in this case.

Note that TuRBO is a **minimization** algorithm, so please make sure you reformulate potential maximization problems.

## Install as Package

In your desired environment (`conda`/`venv`) run:

```
git clone https://github.com/CompRhys/TuRBO
cd TuRBO
python setup.py sdist
pip install -e .
```

## Citing the Original Work

The final version of the original paper is available at: http://papers.nips.cc/paper/8788-scalable-global-optimization-via-local-bayesian-optimization.

```
@inproceedings{eriksson2019scalable,
  title = {Scalable Global Optimization via Local {Bayesian} Optimization},
  author = {Eriksson, David and Pearce, Michael and Gardner, Jacob and Turner, Ryan D and Poloczek, Matthias},
  booktitle = {Advances in Neural Information Processing Systems},
  pages = {5496--5507},
  year = {2019},
  url = {http://papers.nips.cc/paper/8788-scalable-global-optimization-via-local-bayesian-optimization.pdf},
}
```
