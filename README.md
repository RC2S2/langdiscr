# The language of discrimination: Assessing attention discrimination by Hungarian local governments
This repository contains the codes used in the paper [*The language of discrimination: Assessing attention discrimination by Hungarian local governments*](https://link.springer.com/article/10.1007/s10579-022-09612-5)

## Structure
The individual py files were run in sequence.
 * 1_preproc.py: preprocessing the corpus (cleaning, and standardizing, small parts of the preprocessing scripts are omitted in this repository due to privacy reasons)
 * 2_a_1_stat_features.py: descriptive statistics based feature extraction
 * 2_a_2_stat_features_modeling.py: modelling based on descriptive statistical features extracted with 2_a_1_stat_features.py and feature importance measures for model interpretation
 * 2_b_ngram_model.py: ngram based modelling and feature importance measures for model interpretation
 * 3_model_compar.py: comaprison of the two models (descriptive statistics and n-gram based) and stacking model based on the output of the previous models

## Citation

```bibtex
@article{buda_németh_simonovits_simonovits_2022,
  title={The language of discrimination: Assessing attention discrimination by Hungarian local governments},
  author={Buda, Jakab and Németh, Renáta and Simonovits, Bori and Simonovits, Gábor},
  journal={Language Resources and Evaluation}, 
  year={2022},
  DOI={10.1007/s10579-022-09612-5}
} 
```
