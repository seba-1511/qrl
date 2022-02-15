# Policy Learning and Evaluation with Randomized Quasi-Monte Carlo

[![AISTATS](https://img.shields.io/badge/AISTATS-2022-informational.svg)](http://seba1511.net/projects/qrl/)

Code release for "Policy Learning and Evaluation with Randomized Quasi-Monte Carlo", AISTATS 2022.

This code provides a re-implementation of SAC combined with RQMC. It is based on the PyTorch implementation of SAC in [spinning-up](https://github.com/openai/spinningup).

## Resources

* Website: [seba1511.net/projects/qrl](http://seba1511.net/projects/qrl)
* Preprint: [arxiv.org/abs/XXX](https://arxiv.org/abs/XXX)
* Code: [github.com/seba-1511/qrl](https://github.com/seba-1511/qrl)

## Citation

Please cite this work as follows:

> S. M. R. Arnold, P. L'Ecuyer, L. Chen, Y. Chen, F. Sha, *Policy Learning and Evaluation with Randomized Quasi-Monte Carlo*. AISTATS 2022.

or with the following BibTex entry:

~~~bibtex
@inproceedings{Arnold2022qrl,
    title={Policy Learning and Evaluation with Randomized Quasi-Monte Carlo},
    author={Arnold, S\'ebastien M. R. and L'Ecuyer, Pierre and Chen, Liyu and Chen, Yi-fan and Sha, Fei},
    year={2022},
    booktitle={Proceedings of The 25th International Conference on Artificial Intelligence and Statistics},
    volume={131},
    series={Proceedings of Machine Learning Research},
    publisher={PMLR},
}
~~~
~~~

## Usage

Policy learning experiments can be run with the following command:

~~~shell
python qsac.py --env HalfCheetah-v2 --rqmc --multi_actions 4
~~~
