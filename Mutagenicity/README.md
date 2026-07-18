Mutagenicity prediction, Single-Task Binary Classification; PyTorch, GNN, RDKit; Ames Mutagenicity dataset (mutagenic (1) or not mutagenic (0)), random split;  

PERFORMANCE METRICS:  

|Name|Score
| :---: | :---:
|Test Acc  : | 0.78
|ROC-AUC   : | 0.86
|PR-AUC    : | 0.87
|F1-Score  : | 0.80
|Precision : | 0.80
|Recall    : | 0.80


|Dataset|Drug|Prediction|Smiles
| :---: | :---: | :---: | :---:
|0|Phloretin   | 0.07 | `C1=CC(=CC=C1CCC(=O)C2=C(C=C(C=C2O)O)O)O`
|-|Ursolic acid   | 0.10 | `O=C(O)[C@@]54[C@H](/C3=C/C[C@H]1[C@](CC[C@@H]2[C@]1(C)CC[C@H](O)C2(C)C)(C)[C@]3(C)CC4)[C@@H](C)[C@H](C)CC5`
|0|Aspirin        | 0.12 | `O=C(C)Oc1ccccc1C(=O)O`
|1|Quercetin       | 0.36 | `O=C1c3c(O/C(=C1/O)c2ccc(O)c(O)c2)cc(O)cc3O`
|0|Caffeine       | 0.38 | `CN1C=NC2=C1C(=O)N(C(=O)N2C)C`
|1|Nitroglycerin  | 0.33 | `C(C(CO[N+](=O)[O-])O[N+](=O)[O-])O[N+](=O)[O-]`
|1|3-chloro-4-(dichloromethyl)-5-hydroxy-2(5H)-furanone (MX) | 0.79 | `O=C1OC(O)C(C(Cl)Cl)=C1Cl`
|1|Furylfuramide  | 0.90 | `O=[N+]([O-])c2oc(/C=C(/c1occc1)C(=O)N)cc2`
|1|N-ethyl-N-nitrosourea (ENU) | 0.91 | `CCN(N=O)C(N)=O`
|1|Benzo(a)pyrene | 0.91 | `c1ccc2c(c1)cc3ccc4cccc5c4c3c2cc5`
|-|3-Nitrobenzanthrone | 0.94 | `C1=CC=C2C(=C1)C3=C4C(=C(C=C3)[N+](=O)[O-])C=CC=C4C2=O`

[Thalidomide](https://en.wikipedia.org/wiki/Development_of_analogs_of_thalidomide)  

|Dataset|Drug|Prediction|Smiles
| :---:| :---: | :---: | :---:
|0|Thalidomide  | 0.44 | `O=C1c2ccccc2C(=O)N1C3CCC(=O)NC3=O`
|-|Lenalidomide | 0.76 | `O=C1NC(=O)CCC1N3C(=O)c2cccc(c2C3)N`
|-|Pomalidomide | 0.78 | `O=C1C=2C=CC=C(N)C2C(=O)N1C3C(=O)NC(=O)CC3`
|-|Mezigdomide  | 0.30 | `N#Cc1ccc(N2CCN(Cc3ccc(COc4cccc5c4CN([C@H]4CCC(=O)NC4=O)C5=O)cc3)CC2)c(F)c1`
|-|Iberdomide   | 0.30 | `O=C1CC[C@H](N2Cc3c(OCc4ccc(CN5CCOCC5)cc4)cccc3C2=O)C(=O)N1`


<hr/>
