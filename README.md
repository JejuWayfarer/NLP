# NLP Fine-Tuning

    Organize fine-tuning results for different datasets and models by taks.

## 1. Classification

Dataset | Model | Acc | LR | Optizmier | batch size (# gpu)
Bluehouse petition | BERT | 88.26 | 5e-6 | Adamw | 15
---- | KoELECTRA V1 | 88.9 | 5e-6 | AdamP | 96(2)
**---- | KoELECTRA V2 | 89.14 | 5e-6 | AdamP | 96(2)**
---- | XLM-RoBERTa-Large | 89.52 | AdamP | 24(2)

Dataset : https://dacon.io/competitions/open/235597/data/


## 2. Summarization

Dataset | Model | ROGUE-1 | ROGUE-2 | ROGUE-L | LR | Optizmier | batch size (# gpu) | Max_seq_Len
Dacon Abstract Summarization | KoBART | 0.430 | 0.273 | 0.320 | 3e-5 | Adafactor | 4(2) | 512
**---- | KoBART | 0.517 | 0.386 | 0.463 | 1e-4 | Adafactor | 4(2) | 512**
---- | KoBART | 0.505 | 0.371 | 0.449 | 1e-3 | Adafactor | 4(2) | 512

Dataset : https://dacon.io/competitions/official/235673/data/
