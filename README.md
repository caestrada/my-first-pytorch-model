# My First Pytorch Model

[My Notebook](./first-pytorch-model.ipynb)

[Build Your First Pytorch Model In Minutes!](https://www.youtube.com/watch?v=tHL5STNJKag) YouTube tutorial.

[Kaggle Notebook](https://www.kaggle.com/code/robikscube/train-your-first-pytorch-model-card-classifier) from tutorial.

[Cards Image Dataset-Classification](https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification/). This is the dataset used in this problem.

---

The author mentions that these are the 3 fundamental steps to training in any PyTorch model.

- PyTorch Dateset
- PyTorch Model
- PyTorch Training Loop

PyTorch datasets are very flexible. They could be modified to be loaaded however we want. Then we could get thaT dataset and wrap it with a DataLoader for batching.

```python
fron torch.utils.data import Dataset, DataLoader

dataset = PlayingCardDataset(data_dir)
# Create dataloader
dataloader = DataLoader(dataset, )
```
