# Results Summary — 3-Class Dementia Classification

| Model | Accuracy | Macro-F1 | Weighted-F1 | Spec_Normal | Spec_MCI | Spec_Dementia | Spec_MacroAvg | AUC_Normal | AUC_MCI | AUC_Dementia | AUC_MacroAvg | AUC_WeightedAvg |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Random Forest | 0.8021 | 0.7577 | 0.8058 | 0.8808 | 0.8695 | 0.9548 | 0.9017 | 0.9331 | 0.8157 | 0.9814 | 0.9101 | 0.927 |
| FT-Transformer | 0.8222 | 0.7787 | 0.8248 | 0.8906 | 0.8847 | 0.9588 | 0.9114 | 0.9445 | 0.8417 | 0.9834 | 0.9232 | 0.9381 |
| TabNet | 0.822 | 0.7805 | 0.8256 | 0.8896 | 0.881 | 0.9637 | 0.9115 | 0.9445 | 0.8439 | 0.9828 | 0.9237 | 0.9383 |
| TabPFN | 0.833 | 0.7788 | 0.8287 | 0.8725 | 0.9172 | 0.9495 | 0.9131 | 0.9473 | 0.8511 | 0.9844 | 0.9276 | 0.9415 |