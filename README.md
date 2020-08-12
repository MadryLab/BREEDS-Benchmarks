# Creating BREEDS Sub-population shift Benchmarks

This repository contains the code and data for our paper:

**BREEDS: Benchmarks for Subpopulation Shift** <br>
*Shibani Santurkar\*, Dimitris Tsipras\*, Aleksander Madry* <br>
Paper: https://arxiv.org/abs/2008.04859 <br>

![](pipeline.png)

```bibtex
    @InProceedings{santurkar2020breeds,
        title={BREEDS: Benchmarks for Subpopulation Shift},
        author={Shibani Santurkar and Dimitris Tsipras and Aleksander Madry},
        year={2020},
        booktitle={ArXiv preprint arXiv:2008.04859}
    }
```

## Getting started
*Our code relies on the [MadryLab](http://madry-lab.ml/) public [robustness library](https://github.com/MadryLab/robustness), which will be automatically installed when you follow the instructions below.*
1.  Clone our repo: `git clone https://github.com/MadryLab/BREEDS-Benchmarks.git`

2.  Install dependencies:
    ```
    conda create -n breeds-benchmarks python=3.7 pip
    conda activate breeds-benchmarks
    pip install -r requirements.txt
    conda install pygraphviz
    ```
3.  Download the [ImageNet](http://www.image-net.org/) dataset.

That's it! Now you can create new BREEDS datasets, or look closer at the ones
we use in our paper using this
[notebook](https://github.com/MadryLab/BREEDS-Benchmarks/blob/master/Constructing%20BREEDS%20datasets.ipynb).
You can also find a detailed walkthrough of this code in this
[documentation](https://robustness.readthedocs.io/en/latest/example_usage/breeds_datasets.html).
In order to train models using these datasets, you can use simply use [existing
code](https://robustness.readthedocs.io/en/latest/example_usage/training_lib_part_1.html) from the robustness library.


# Maintainers

* [Shibani Santurkar](https://twitter.com/ShibaniSan)
* [Dimitris Tsipras](https://twitter.com/tsiprasd)
* [Aleksander Madry](https://twitter.com/aleks_madry) 
