# 🌍 Contributing.

Contributions are welcome, and they are greatly appreciated! Every little bit helps, and credit will always be given.

## 👶 Getting Started!

Ready to contribute? Here's how to set up `rust-data-analysis` for local development.

1. Fork the `rust-data-analysis` repo on GitHub.
1. Clone your fork locally:

	```sh
	git clone git@github.com:your_name_here/rust-data-analysis.git
	```

1. Navigate to the recently created directory:

	```sh
	cd rust-data-analysis
	```

1. Install the main dependencies:

	```sh
	# Install a Rust toolchain (e.g. nightly):
	curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y --default-toolchain nightly

	# Install Jupyter Notebook
	pip install notebook

	# Install evcxr_jupyter
	cargo install evcxr_jupyter
	evcxr_jupyter --install	
	```

1. Start Jupyter Notebook:

	```sh
	jupyter notebook
	```

1. Create a branch for local development:

	```sh
	git checkout -b name-of-your-bugfix-or-feature
	```

Now you can make your changes locally.

1. Commit your changes and push your branch to GitHub:

	```sh
	git add .
	git commit -m "Your detailed description of your changes."
	git push origin name-of-your-bugfix-or-feature
	```

1. Submit a pull request through the GitHub website.

Thank you for helping us improve!