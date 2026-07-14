Mutagenicity prediction, Single-Task Binary Classification; PyTorch, GNN, RDKit; Ames Mutagenicity dataset, random split;  

PERFORMANCE METRICS:  

|Name|Score
| :---: | :---:
|ROC-AUC   : | 0.82
|PR-AUC    : | 0.85
|F1-Score  : | 0.76
|Precision : | 0.81
|Recall    : | 0.71


|Drug|Prediction|Smiles
| :---: | :---: | :---:
|Aspirin       | 0.20 | O=C(C)Oc1ccccc1C(=O)O
|Nitroglycerin | 0.89 | C(C(CO[N+](=O)[O-])O[N+](=O)[O-])O[N+](=O)[O-]
|Furylfuramide | 0.85  | O=[N+]([O-])c2oc(/C=C(/c1occc1)C(=O)N)cc2

[Thalidomide](https://en.wikipedia.org/wiki/Development_of_analogs_of_thalidomide)  

|Drug|Prediction|Smiles
| :---: | :---: | :---:
|Thalidomide  | 0.51 | O=C1c2ccccc2C(=O)N1C3CCC(=O)NC3=O
|Lenalidomide | 0.73 | O=C1NC(=O)CCC1N3C(=O)c2cccc(c2C3)N
|Pomalidomide | 0.77 | O=C1C=2C=CC=C(N)C2C(=O)N1C3C(=O)NC(=O)CC3
|Mezigdomide  | 0.34 | N#Cc1ccc(N2CCN(Cc3ccc(COc4cccc5c4CN([C@H]4CCC(=O)NC4=O)C5=O)cc3)CC2)c(F)c1
|Iberdomide   | 0.41 | O=C1CC[C@H](N2Cc3c(OCc4ccc(CN5CCOCC5)cc4)cccc3C2=O)C(=O)N1


<hr/>
