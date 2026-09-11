# CA3: Hoda digit classification

This project trains multilayer perceptron models for Persian handwritten digit classification on the Hoda dataset.

## Contents

- `notebooks/hoda_mlp_baseline.ipynb`: baseline MLP training and evaluation.
- `notebooks/keras_optimizer_experiments.ipynb`: Keras optimizer experiments.
- `notebooks/pytorch_optimizer_experiments.ipynb`: PyTorch optimizer experiments.
- `data/Data_hoda_full.mat`: Hoda dataset file used by the notebooks.

## Results from the project notes

- Base MLP experiment: about 99.22% training accuracy and 97.45% test accuracy.
- Tuned experiment: about 100.00% training accuracy and 98.05% test accuracy.
- Optimizer-search notes report best test accuracy around 98.45% to 98.55%, depending on the run.

The Comet notebooks were cleaned before upload. Outputs and online experiment links were removed.
