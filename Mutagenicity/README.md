Mutagenicity prediction, Single-Task Binary Classification; PyTorch, GNN, RDKit; Ames Mutagenicity dataset (mutagenic (1) or not mutagenic (0)), random split;  

PERFORMANCE METRICS:  

|Name|Score
| :---: | :---:
|Test Acc  : | 0.79
|ROC-AUC   : | 0.85
|PR-AUC    : | 0.86
|F1-Score  : | 0.80
|Precision : | 0.80
|Recall    : | 0.80


|Dataset|Drug|Prediction|Smiles
| :---: | :---: | :---: | :---:
|0|Aspirin        | 0.12 | `O=C(C)Oc1ccccc1C(=O)O`
|0|Caffeine       | 0.45 | `CN1C=NC2=C1C(=O)N(C(=O)N2C)C`
|1|Nitroglycerin  | 0.83 | `C(C(CO[N+](=O)[O-])O[N+](=O)[O-])O[N+](=O)[O-]`
|1|Furylfuramide  | 0.87 | `O=[N+]([O-])c2oc(/C=C(/c1occc1)C(=O)N)cc2`
|1|Benzo(a)pyrene | 0.94 | `c1ccc2c(c1)cc3ccc4cccc5c4c3c2cc5`

[Thalidomide](https://en.wikipedia.org/wiki/Development_of_analogs_of_thalidomide)  

|Dataset|Drug|Prediction|Smiles
| :---:| :---: | :---: | :---:
|0|Thalidomide  | 0.61 | `O=C1c2ccccc2C(=O)N1C3CCC(=O)NC3=O`
|-|Lenalidomide | 0.75 | `O=C1NC(=O)CCC1N3C(=O)c2cccc(c2C3)N`
|-|Pomalidomide | 0.82 | `O=C1C=2C=CC=C(N)C2C(=O)N1C3C(=O)NC(=O)CC3`
|-|Mezigdomide  | 0.35 | `N#Cc1ccc(N2CCN(Cc3ccc(COc4cccc5c4CN([C@H]4CCC(=O)NC4=O)C5=O)cc3)CC2)c(F)c1`
|-|Iberdomide   | 0.44 | `O=C1CC[C@H](N2Cc3c(OCc4ccc(CN5CCOCC5)cc4)cccc3C2=O)C(=O)N1`


<hr/>
