# Rust EDA

Performing data analysis on the iris dataset in a Rust kernel.

## Steps

- Install rust toolchain:

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y --default-toolchain nightly
```

- Install [Jupyter Notebook](https://jupyter.org/install).

- Install `evcxr_jupyter`

```sh
cargo install evcxr_jupyter
evcxr_jupyter --install
```

- Run the notebook:

```sh
jupyter notebook
```

Make sure you have the rust kernel is selected from the top right corner of the kernel. You should see the official rust logo.

For more info, you can refer to [this medium article](https://towardsdatascience.com/rust-the-next-big-thing-in-data-science-319a03305883).
