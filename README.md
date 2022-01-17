# Alert

This is an implementation of the MDVC method with some customizations. 

The original implementation and running instructions are in [MDVC](https://github.com/v-iashin/MDVC). However, works that use this customized version does not work with the original implementation (e.g. https://github.com/valterlej/dvcusi or https://github.com/valterlej/zsarcap).

# Clonning

```shell
git clone https://github.com/valterlej/CustomMDVC.git
conda env create -f ./conda_env.yml
conda activate mdvc
# install spacy language model. Make sure you activated the conda environment
python -m spacy download en
```
