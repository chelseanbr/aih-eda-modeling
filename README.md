# EDA & Predictive Modeling Tutorial for AI in Healthcare
👷🏽‍♀️ Readme under construction, but please feel free to check out the [slides](aih-sl-tutorial-slides.pdf) and [code](aih-sl-tutorial.ipynb)! 

## Installation

1. Create file `aih_sl_tutorial.yml` (or use existing `aih_sl_tutorial.yml` provided):
```yaml
name: aih-sl-tutorial
channels:
  - conda-forge
  - defaults
platforms:
  - osx-arm64
dependencies:
  - python=3.11.10
  - pip=24.2
  - notebook=7.2.2
  - ipywidgets=8.1.5
  - numpy=1.26.4
  - pandas=2.2.3
  - matplotlib=3.9.2
  - pytorch=2.4.1
  - plotly=6.0.0
  - wordcloud=1.9.4
  - scikit-learn=1.5.2
  - tqdm=4.66.6
```

2. Use Miniconda (https://docs.conda.io/en/latest/miniconda.html) to create the `aih-sl-tutorial` environment and install the required packages:
```bash
conda env create -f aih_sl_tutorial.yml
```

3. Select kernel: `aih-sl-tutorial` to run .ipynb notebook
