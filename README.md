# Rust EDA

<div align="center">

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?logo=rust&logoColor=white)

</div>

This repository is a collection of Jupyter notebooks, all powered by a Rust kernel. With these notebooks, you'll be able to dive deep into the realm of data analysis with Rust, exploring different datasets and extracting insights with ease using different Rust libraries such as ndarray, plotters, and much more.

## Steps

- Install a Rust toolchain (e.g. nightly):

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y --default-toolchain nightly
```

- Install [`Jupyter`](https://jupyter.org/install).

- Install [`evcxr_jupyter`](https://github.com/evcxr/evcxr/blob/main/evcxr_jupyter/README.md)

```sh
cargo install evcxr_jupyter
evcxr_jupyter --install
```

- Run Jupyter:

```sh
jupyter notebook
```

## Resources

I have written a series of articles titled:

1. [Rust: The Next Big Thing in Data Science](https://towardsdatascience.com/rust-the-next-big-thing-in-data-science-319a03305883?source): In this article, you will delve into the exciting world of Rust libraries for exploratory data analysis on the famed iris dataset. You can open up [this notebook](./1-iris-data-analysis-rust.ipynb) associated with this article to follow along.

1. [The Ultimate Ndarray Handbook: Mastering the Art of Scientific Computing with Rust](https://towardsdatascience.com/the-ultimate-ndarray-handbook-mastering-the-art-of-scientific-computing-with-rust-ef5ab767212a): This article is an overview of different Rust’s built-in data structures and a deep dive into the Ndarray library. You can open up [this notebook](./2-ndarray-tutorial.ipynb) associated with this article to follow along.

1. [Rust Polars: Unlocking High-Performance Data Analysis — Part 1](https://towardsdatascience.com/rust-polars-unlocking-high-performance-data-analysis-part-1-ce42af370ece). This article is part 1 of exploring the Polars library. You can open up [this notebook](./3-polars-tutorial-part-1.ipynb) associated with this article to follow along.

1. [Rust Polars: Unlocking High-Performance Data Analysis — Part 2](https://towardsdatascience.com/rust-polars-unlocking-high-performance-data-analysis-part-2-7c58a3cb7a1f). This article is part 2 of exploring the Polars library. You can open up [this notebook](./4-polars-tutorial-part-2.ipynb) associated with this article to follow along.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=wiseaidev/rust-data-analysis&type=Date)](https://star-history.com/#wiseaidev/rust-data-analysis&Date)
