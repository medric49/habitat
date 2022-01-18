# habitat

## Installation

* Install environment
```shell
conda env create -f env.yml
conda activate habitat
```
Install Habitat-Lab
```shell
git clone --branch stable https://github.com/facebookresearch/habitat-lab.git
cd habitat-lab
pip install -r requirements.txt
python setup.py develop --all
```
