# RepPad for Sequential Recommendation

Implementation and evaluation of **Repeated Padding (RepPad)** based on Dang et al. (RecSys 2024).

The project evaluates RepPad across two datasets and introduces **Cold-User Targeted RepPad**, a selective augmentation strategy for users with sparse interaction histories.

## Datasets
- H&M Personalized Fashion Recommendations
- Amazon Musical Instruments Reviews

## Methodology
- GRU4Rec and SASRec
- Sequential data preprocessing
- Repeated Padding (RepPad)
- Cold-User Targeted RepPad (proposed)
- Ablation study across five RepPad variants

## Key Findings
- RepPad benefits SASRec more consistently than GRU4Rec.
- Its effectiveness depends on sequence length and available padding space.
- Cold-User Targeted RepPad partially recovers performance on H&M.
- Fixed repetition count of two outperforms the recommended stochastic variant in our ablation study.
- SASRec + RepPad improves NDCG@10 by 2.2% on Amazon Musical Instruments.

## Technologies
Python · PyTorch · Pandas · NumPy · Matplotlib · CUDA

## Reference
Dang et al. (2024). *Repeated Padding for Sequential Recommendation*. RecSys '24.

[Original RepPad Repository](https://github.com/KingGugu/RepPad)

## Team
- Joori Ahmed Shareef
- Sarah Sulaiman Aldarwish
- Rahaf Alhodali
