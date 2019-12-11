# Can a Machine Learn the Outcome of Planetary Collisions?

Planetary-scale collisions are common during the last stages of formation of solid planets, including the Solar system terrestrial planets. The problem of growing planets has been divided into studying the gravitational interaction of embryos relevant in million year timescales and treated with N-body codes and the collision between objects with a timescale of hours to days and treated with smoothed-particle hydrodynamics. These are now being coupled with simple parameterized models. We set out to investigate if machine learning techniques can offer a better solution by predicting the outcome of collisions which can then be used in N-body simulations. We considered three different supervised machine learning approaches: gradient boosting regression trees, nested models, and gaussian processes. We found that the former produced the best results, and that it was slightly surpassed by ensembling different algorithms. With gaussian processes, we found the regions of parameter space that may yield the most information to machine learning algorithms. Thus, we suggest SPH calculations to focus first on mass ratios above 0.5.

Our related research paper was published on 29 August 2019 in The Astrophysical Journal. 

The paper is available here: https://iopscience.iop.org/article/10.3847/1538-4357/ab2bfb

And the public preprint is available here: https://arxiv.org/abs/1902.04052

The code is present in a Jupyter Notebook and the data in a csv file named "collisions.csv"
