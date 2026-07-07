# ACT4 – Multi-Variant Text Analysis and Generation (BERT, GPT, and Text-GAN)

Comparison of three NLP approaches on the IMDB movie review dataset: BERT for sentiment classification, GPT-2 for text generation, and a Text-GAN for adversarial text generation. All three are trained on the same data splits and evaluated using shared metrics.

## Dataset
IMDB Dataset of 50K Movie Reviews (Kaggle): https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## Contents
- `ACT4_Multi_Variant_Text_Analysis_and_Generation.ipynb` — full notebook: preprocessing, all three model variants, evaluation, interpretations, discussion
- `results.json` — training histories, test metrics, BLEU/ROUGE scores, and discriminator accuracy for all three variants
- `sample_generations.txt` — generated text samples from the GPT-2 and Text-GAN variants

## Summary of Results
| Model Variant | Primary Metric | Generative Quality Metric |
|---|---|---|
| BERT | F1 = 0.923 | N/A (classification task) |
| GPT-2 | N/A (generative task) | BLEU = 0.0, ROUGE-1 = 0.207, Perplexity = 46.50 |
| Text-GAN | Discriminator Accuracy ≈ 57–67% | BLEU = 0.0, ROUGE-1 = 0.129 |

Full metrics, interpretations, and discussion are in the notebook.

By: Gian Eugene Sibayan
