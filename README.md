# Rust EDA

Performing data analysis on the iris dataset in a Rust kernel.

## Steps

- Install rust toolchain:

```rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y --default-toolchain nightly
```

- Create a new project and cd into it:

```sh
cargo new project
cd project
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

## TODO

For more info, you can refer to this medium article.