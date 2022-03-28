# Cancer Data Aggregator
Playing with the [Cancer Data Aggregator (CDA)](https://cda.readthedocs.io/). 

Use cases explored thus far,
- [identify bams in a TCGA cohort and create a GDC manifest file](identify-tcga-bams/)

## Installation
### Download this repository from Github
This package can be downloaded through Github on the website or by using terminal. To download on the website, navigate to the top of this page, click the green `Clone or download` button, and select `Download ZIP`. This will download this repository in a compressed format. To install using Github on terminal, type 

```bash
git clone https://github.com/brendanreardon/cancer-data-aggregator.git
cd cancer-data-aggregator
```

### Install Python dependencies
This repository uses Python 3.9. We recommend using a [virtual environment](https://docs.python.org/3/tutorial/venv.html) and running Python with either [Anaconda](https://www.anaconda.com/download/) or  [Miniconda](https://conda.io/miniconda.html). 

To create a virtual environment and install dependencies with Anaconda or Miniconda, run the following from this repository's directory:
```bash
conda create -y -n cancer-data-aggregator python=3.9
conda activate cancer-data-aggregator
pip install -r requirements.txt
ipython kernel install --user --name=cancer-data-aggregator
```

If you are using base Python, you can create a virtual environment and install dependencies by running:
```bash
virtualenv cancer-data-aggregator
source activate cancer-data-aggregator/bin/activate
pip install -r requirements.txt
ipython kernel install --user --name=cancer-data-aggregator
```
