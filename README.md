# AutoML-Benchmarking
Benchmarking of state-of-practice AutoML tools for text: 

- [Auto-Sklearn](Notebook%20Benchmarking/AutoML%20test%20-%20Auto-sklearn.ipynb) 
- [TPOT](Notebook%20Benchmarking/AutoML%20test%20-%20TPOT.ipynb) 
- [AutoGluon-Text](Notebook%20Benchmarking/AutoML%20test%20-%20AutoGluon-Text.ipynb) 
- [AutoViML](Notebook%20Benchmarking/AutoML%20test%20-%20AutoViML.ipynb) 

## Test on B2W-Reviews dataset

| Framework      | Training time | Accuracy | F1-Score |
|----------------|:-------------:|:--------:|:--------:|
| Auto-Sklearn   |     1800s+    |   0.85   |   0.85   |
| TPOT           |      N/A      |    N/A   |    N/A   |
| AutoGluon-Text |     1800s+    | **0.89** | **0.88** |
| AutoViML       |      N/A      |    N/A   |    N/A   |

## Test on COVID-19 NLP dataset

| Framework      | Training time | Accuracy | F1-Score |
|----------------|:-------------:|:--------:|:--------:|
| Auto-Sklearn   |     1800s+    |   0.42   |   0.42   |
|  TPOT          |     1800s+    |   0.60   |   0.61   |
| AutoGluon-Text |     1218s     | **0.85** | **0.86** |
|  AutoViML      |    **854s**   |   0.58   |   0.57   |

## Test on NLP on Research Articles dataset

| Framework      | Training time | Accuracy | F1-Score |
|----------------|:-------------:|:--------:|:--------:|
|  Auto-Sklearn  |     1800s+    |   0.85   |   0.85   |
|  TPOT          |     1800s+    |   0.85   |   0.84   |
| AutoGluon-Text |     1090s     | **0.87** | **0.87** |
|  AutoViML      |    **722s**   |   0.85   |   0.85   |