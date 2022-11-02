# Model Soups for Text Classification 🍜

Shows an implementation of model soups [1] for text classification models.

## Notebooks

* `notebooks/train-models.ipynb` shows how to obtain the fine-tuned text classification
models using `Trainer` and `AutoModelForSequenceClassification` classes from 🤗 Transformers.
* `notebooks/model-soups.ipynb` shows how to obtain model soups using two recipes presented in [1].
* `notebooks/logit-ensembling.ipynb` shows how to perform the classic logit ensembling. It's here for
comparison purposes.

## Results

TBA

## References

[1] [Model soups: averaging weights of multiple fine-tuned models improves accuracy without increasing inference time](https://arxiv.org/abs/2203.05482) (ICML 2022)
