# CataLiUst

Welcome to the **CataLiUst initiative**!  

We develop **DFT datasets** and **tools**, and train **machine learning models** for use in computational catalysis and surface chemistry research.

---

## Datasets

Here you will find the datasets we have released so far.
Each entry includes a short description, the type of data, the level of theory, a link to Zenodo where the dataset is hosted, the repository containing code for using the dataset, and the publication introducing the dataset.

***If you use a dataset***, please cite the corresponding publication and acknowledge **CataLiUst**.

| Name | Description | Data type |  Level of theory | Zenodo DOI |   Repository   | Publication  |
|------|------------|-----------|---------------|------------|------------|------------|
| CataLiUst Ti2C-MXene | Molecules (CO<sub>2</sub>, HCOOH, H<sub>2</sub>O, O<sub>2</sub>, H<sub>2</sub>) on Ti<sub>2</sub>C MXenes | Formation energies and forces | DFT (rev-vdW-DF2 [^Hamada14]) | [doi.org/10.5281/zenodo.17652071](https://doi.org/10.5281/zenodo.17652071) | [equimodel-mxene](https://github.com/CataLiUst/equimodel-mxene) | P. Melnyk, *et al.*, Equivariant Modelling for Catalysis on 2D MXenes, [EurIPS **2025** Workshop on SIMBIOCHEM](https://openreview.net/forum?id=GHGRyCrSz4) |

---


## Machine Learning Models

Here you will find the machine learning models we have trained so far.
Each entry may include multiple models that differ, for example, in whether they were pretrained or trained from scratch, 
and in the number of parameters (i.e., model size).

For each model set, we list the dataset used for training, the model type, the underlying architecture, the Zenodo DOI where the trained model files are hosted, the repository containing code for using the models, and the publication introducing the work.

***If you use a model***, please cite the corresponding publication and acknowledge **CataLiUst**.

| Trained on dataset   | Model type | Architecture |   Zenodo DOI |   Repository   | Publication  |
|------|-------------|-----------|---------------|------------|------------|
| CataLiUst Ti2C-MXene  | MLIP | EquiformerV2[^EquiformerV2] | [doi.org/10.5281/zenodo.17654434](https://doi.org/10.5281/zenodo.17654434) | [equimodel-mxene](https://github.com/CataLiUst/equimodel-mxene) | P. Melnyk, *et al.*, Equivariant Modelling for Catalysis on 2D MXenes, [EurIPS **2025** Workshop on SIMBIOCHEM](https://openreview.net/forum?id=GHGRyCrSz4) |

---

## Citation
Please cite the associated publications when using data or models.
<!---
% Please cite the dataset DOI or associated publications when using data or models.
-->



[^Hamada14]: I. Hamada. van der Waals density functional made accurate. [*Phys. Rev. B* **2014**, *89*, 121103(R)](https://doi.org/10.1103/PhysRevB.89.121103).
[^EquiformerV2]: Y.-L. Lioa, B. Wood, A. Das, and T. Smidt. EquiformerV2: Improved equivariant transformer for scaling
to higher-degree representations. [*ICLR* **2024**](https://openreview.net/forum?id=mCOBKZmrzD)


