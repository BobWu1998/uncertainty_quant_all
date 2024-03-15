
# Uncertainty-Aware Deployment of Pre-trained Language-Conditioned Imitation Learning Policies

This repository aggregates the repositories of the three models which have been adapted with the uncertainty-aware action selection strategy. 

Our adaptation of the three models are included as submodules. Each of the submodules contain detailed instruction for original model preparation, model calibration, and testing the model with our uncertainty-aware action selection strategy. You can access the submodules directly following the links below:

[**UA-Perceiver-Actor**](https://github.com/anonymous23099/uncertainty_quant_peract.git)

[**UA-RVT: Robotic View Transformer**](https://github.com/anonymous23099/uncertainty_quant_rvt.git)

[**UA-CLIPort**](https://github.com/anonymous23099/uncertainty_quant_cliport.git)

To download them, you can simply run the following command after cloning this repository. 
```
git submodule update --init --recursive
```



We also provide the links to the original github repository for the three models:

[**Perceiver-Actor**](https://github.com/peract/peract.git)

[**RVT: Robotic View Transformer**](https://github.com/NVlabs/RVT.git)

[**CLIPort**](https://github.com/cliport/cliport)

## Citations
**PerAct**
```
@inproceedings{shridhar2022peract,
  title     = {Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation},
  author    = {Shridhar, Mohit and Manuelli, Lucas and Fox, Dieter},
  booktitle = {Proceedings of the 6th Conference on Robot Learning (CoRL)},
  year      = {2022},
}
```

**RVT**
```
@article{goyal2023rvt,
  title={RVT: Robotic View Transformer for 3D Object Manipulation},
  author={Goyal, Ankit and Xu, Jie and Guo, Yijie and Blukis, Valts and Chao, Yu-Wei and Fox, Dieter},
  journal={arXiv preprint arXiv:2306.14896},
  year={2023}
}
```

**CLIPort**
```
@inproceedings{shridhar2021cliport,
  title     = {CLIPort: What and Where Pathways for Robotic Manipulation},
  author    = {Shridhar, Mohit and Manuelli, Lucas and Fox, Dieter},
  booktitle = {Proceedings of the 5th Conference on Robot Learning (CoRL)},
  year      = {2021},
}
```