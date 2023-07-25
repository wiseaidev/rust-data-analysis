# 📚 Rust Data Analysis

[![Gitter](https://img.shields.io/badge/GITTER-join%20chat-green.svg?logo=gitter&logoColor=white&color=black)](https://matrix.to/#/#rusty-data:gitter.im)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/wiseaidev)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![made-with-rust](https://img.shields.io/badge/Made%20with-Rust-1f425f.svg?logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg?logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-blue.svg?logo=Jupyter&logoColor=orange)](https://jupyter.org/)

Welcome to the Rust Data Analysis repository! This collection of Jupyter notebooks provides a comprehensive exploration of data analysis using Rust. Powered by a Rust kernel, these notebooks allow you to dive deep into the realm of data analysis, leveraging the capabilities of the Rust programming language. With the help of various Rust libraries, such as ndarray, plotters, and more, you'll be able to extract valuable insights from different datasets with ease.

## 📝 Table of Contents

- [Installation](#-installation)
- [Tutorials](#-tutorials)
- [Contributing](#-contributing)
- [Licence](#-licence)
- [Star History](#-star-history)

## 🚀 Installation

To use the notebooks in this repository, you need to set up your environment. Follow these steps to get started:

1. Clone the repository to your local machine:

	```sh
	git clone https://github.com/wiseaidev/rust-data-analysis.git
	```

1. Install the required dependencies and libraries. Make sure you have [`Rust`](https://rustup.rs/), [`Jupyter Notebook`](https://jupyter.org/install), and [`evcxr_jupyter`](https://github.com/evcxr/evcxr/blob/main/evcxr_jupyter/README.md) installed on your system.

	```sh
	# Install a Rust toolchain (e.g. nightly):
	curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y --default-toolchain nightly

	# Install Jupyter Notebook
	pip install notebook

	# Install evcxr_jupyter
	cargo install evcxr_jupyter
	evcxr_jupyter --install	
	```

1. Navigate to the cloned repository:

	```sh
	cd rust-data-analysis
	```

1. Start Jupyter Notebook:

	```sh
	jupyter notebook
	```

1. Access the notebooks in your web browser by clicking on the notebook file you want to explore.

## 📌 Tutorials

| ID | Article | Thumbnail | Read Time (mins) | Description | Open on GitHub | Launch on Binder |
|----|---------------|-----------|:-------------:|-------------|----------------|------------------|
| 1  | [Rust: The Next Big Thing in Data Science](https://towardsdatascience.com/rust-the-next-big-thing-in-data-science-319a03305883) | ![Article 1](https://miro.medium.com/v2/resize:fit:720/format:webp/1*2jSP2n1KukVJYKVg2u4RuA.png) | 25 | A Contextual Guide for Data Scientists and Analysts. | [GitHub](./1-iris-data-analysis-rust.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wiseaidev/rust-data-analysis/main?filepath=1-iris-data-analysis-rust.ipynb) |
| 2  | [The Ultimate Ndarray Handbook: Mastering the Art of Scientific Computing with Rust](https://towardsdatascience.com/the-ultimate-ndarray-handbook-mastering-the-art-of-scientific-computing-with-rust-ef5ab767212a) | ![Article 2](https://miro.medium.com/v2/resize:fit:720/format:webp/1*bgmO2hUgZXpCHPC1XaBy3w.png) | 31 | This article is an overview of different Rust’s built-in data structures and a deep dive into the Ndarray library. | [GitHub](./2-ndarray-tutorial.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wiseaidev/rust-data-analysis/main?filepath=2-ndarray-tutorial.ipynb) |
| 3  | [Rust Polars: Unlocking High-Performance Data Analysis — Part 1](https://towardsdatascience.com/rust-polars-unlocking-high-performance-data-analysis-part-1-ce42af370ece) | ![Article 3](https://miro.medium.com/v2/resize:fit:720/0*Le8YYCDuEhc4A7tN) | 32 | This article is part 1 of exploring the Polars library. | [GitHub](./3-polars-tutorial-part-1.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wiseaidev/rust-data-analysis/main?filepath=3-polars-tutorial-part-1.ipynb) |
| 4  | [Rust Polars: Unlocking High-Performance Data Analysis — Part 2](https://towardsdatascience.com/rust-polars-unlocking-high-performance-data-analysis-part-1-ce42af370ece) | ![Article 4](https://miro.medium.com/v2/resize:fit:720/format:webp/1*wbXTzoBWnmGXH7WVkAu4PQ.jpeg) | 24 | This article is part 2 of exploring the Polars library. | [GitHub](./4-polars-tutorial-part-2.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wiseaidev/rust-data-analysis/main?filepath=4-polars-tutorial-part-2.ipynb) |
| 5  | [Exploring Probability Theory with Rust: A Pioneering Journey](https://levelup.gitconnected.com/exploring-probability-theory-with-rust-a-pioneering-journey-749ce7cdf747) | ![Article 5](https://miro.medium.com/v2/resize:fit:720/0*gSrM4bMl7eBy6jxM) | 38 | This article is a deep dive into probability theory with Rust. | [GitHub](./5-probability-theory-tutorial.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wiseaidev/rust-data-analysis/main?filepath=5-probability-theory-tutorial.ipynb) |
| 6  | [Rustic Data: Data Visualization with Plotters — Part 1](https://towardsdatascience.com/rustic-data-data-visualization-with-plotters-part-1-7a34b6f4a603) | ![Article 6](https://miro.medium.com/v2/resize:fit:720/format:webp/1*SDpfhuT8gB24i2hRlZKS3Q.png) | 20 | A detailed guide on how to transform raw numbers into stunning graphs in Rust | [GitHub](./6-plotters-tutorial-part-1.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wiseaidev/rust-data-analysis/main?filepath=6-plotters-tutorial-part-1.ipynb) |
| 7  | Todo | Todo | Todo | Todo | [GitHub](./7-calculas-tutorial.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wiseaidev/rust-data-analysis/main?filepath=7-calculas-tutorial.ipynb) |

## 🤝 Contributing

We welcome contributions to enhance the Rust Data Analysis repository! To contribute, please follow the [`CONTRIBUING.md`](CONTRIBUING.md) file guidelines. Thank you for helping make this project better!

## 📜 License

This project is licensed under the [Apache License 2.0](https://opensource.org/licenses/Apache-2.0). For more details, You can refer to the [LICENSE](LICENSE) file.

## 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=wiseaidev/rust-data-analysis&type=Date)](https://star-history.com/#wiseaidev/rust-data-analysis&Date)