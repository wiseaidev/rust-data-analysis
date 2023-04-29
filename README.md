# Rust EDA

This repository is a collection of Jupyter notebooks, all powered by a Rust kernel. With these notebooks, you'll be able to dive deep into the realm of data analysis with Rust, exploring different datasets and extracting insights with ease using different Rust libraries such as ndarray, plotters, and much more.

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

Make sure you have the rust kernel selected from the top right corner of the kernel. You should see the official Rust logo.

## Resources

I have written a series of articles titled:

1. [Rust: The Next Big Thing in Data Science](https://wiseai.medium.com/rust-the-next-big-thing-in-data-science-319a03305883?source=user_profile---------0----------------------------): In this article, you will delve into the exciting world of Rust libraries for exploratory data analysis on the famed iris dataset. You can open [this notebook](./1-iris-data-analysis-rust.ipynb) associated with this article to follow along.

1. TODO. You can open up [this notebook](./2-ndarray-tutorial.ipynb) associated with this article to follow along.
