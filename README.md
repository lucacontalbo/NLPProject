# NLPProject

The task is to evaluate whether a given claim is verified/refuted or not by a set of evidence sentences. Initial tests are performed using BM25, TF-IDF, and pre-trained SBERT and SGPT. Subsequently, fine-tuning is done on SBERT and boosting algorithms (xgboost library) are applied to improve ranking scores (MRR, MAP@, etc.). Additionally, we propose to use GPT for data augmentation, obtaining a larger synthetic dataset that allows us to achieve higher results. The results can be consulted in the report.pdf file
