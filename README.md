# Pytorch lightning practice

Pytorch lightning basic example.

## How to Run

The scripts are tested in Apple Silicon. This should work in other platforms but not guaranteed.

1. Prepare a virtual env.

```bash
$ cd ${project_root}
$ python3 -m venv ./venv
$ source ./venv/bin/activate
$ python3 -m pip install --upgrade pip
$ python3 -m pip install -r requirements.txt
```
2. Run a notebook.

You may run a jupyter server and run interactively. 

If you want to avoid a hassle setting up, you can run directly from the command line like below.

```bash
$ jupyter nbconvert --to notebook --execute autoencoder.ipynb # or other files in this repo
```

## Examples in this repo.

- autoencoder.ipynb

  A short hello-world like example from the official [repo](https://github.com/Lightning-AI/lightning/blob/233f23de076066fff643bfc57455b1d5ba2751c5/README.md).

- classification.ipynb

  Another short example with a classic classification from [the official documentation](https://pytorch-lightning.readthedocs.io/en/latest/notebooks/lightning_examples/mnist-hello-world.html).