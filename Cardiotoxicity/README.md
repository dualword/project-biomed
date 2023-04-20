
Prediction of cardiotoxicity using C++ DNN framework and RDKit.  

* training dataset containing 6000+ compounds.  
* Single-task DNN, input: molecular fingerprint, fully-connected layers.  

<p>
100 epochs:   

|Drug|Result
| :---: | :---:
| Acetylsalicylic acid  | 8.76176e-11
| Acetaminophen  | 1.28852e-11
| Piracetam  | 2.76039e-15
| Cefazolin  | 0.0238207
| Propranolol  | 0.0430008
| Vardenafil  | 0.141336
| Cisapride  | 0.926802
| Dextromethorphan  | 0.999978
| Ziprasidone  | 0.999942
| Loratadine  | 0.995072
| Astemizole  | 1
| Verapamil  | 0.999998

<p>
1000 epochs:  

|Drug|Result
| :---: | :---:
| Acetylsalicylic acid  | 2.94566e-11
| Acetaminophen  | 5.37125e-18
| Piracetam  | 2.77795e-27
| Cefazolin  | 0.000928662
| Propranolol  | 0.546924
| Vardenafil  | 0.000166856
| Cisapride  | 0.999998
| Dextromethorphan  | 1
| Ziprasidone  | 0.999995
| Loratadine  | 0.998948
| Astemizole  | 1
| Verapamil  | 1

