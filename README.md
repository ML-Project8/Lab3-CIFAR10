# Lab3-CIFAR10

### Directions
- [This site](https://www.cs.toronto.edu/~kriz/cifar.html) is the data source and describes the format of the pixel data
- Keras, a neuran network library has an import that downloads the CIFAR-10 dataset and spits out a training/test ndarray, which saves us a couple of steps (rather than downloading tand parsing the data directly from the source
- If plotly causes issues, run with:
jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000
