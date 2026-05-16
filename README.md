<div align="center">
**Guitar Signal Chain Modelling with Deep Learning**
</div>

This is a repository to show off my bachelor's degree dissertation. This research was performed during my time studying Computer Science at the University of Surrey.

This research investigates the ability of structured state space models with temporal feature-wise linear modulation to learn to replicate entire guitar signal chains that include both effects pedals and amplifiers. Recent research released earlier in the year had proved the ability of this neural architecture to simulate both linear and non-linear effects pedals, and so I extended this application to chains of multiple effects. I showed that single black box neural models outperform grey-box equivalents comprised of chains of individual models trained on each effect in isolation.

The [NablAFx](https://github.com/mcomunita/nablafx) framework was used to train and test models. The datasets created for this research used existing guitar recordings from the [ToneTwisT AFx Dataset](https://github.com/willgrimshaw/tonetwist-afx-dataset) and can be found on [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Grimshaw%2C%20William%22&l=list&p=1&s=10&sort=bestmatch).

## Contents
- **Guitar Signal Chain Modelling with Deep Learning.pdf**
    Dissertation report on research findings.
- **demo.ipynb**
    A demonstration notebook for calculating accuracy metrics for the trained models. The example test datasets are so smaller than those used in the research. As such, the metrics produced are not representative of model performance. Requires the [NablAFx](https://github.com/mcomunita/nablafx) package to run.
- **Model Weight**
    Trained model checkpoints and configs.
- **Test Data**
    A small subset of the test dataset for each model.
