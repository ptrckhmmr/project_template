# Setup

Create a [miniconda](https://docs.conda.io/en/latest/miniconda.html) environment by running the following command:

```bash
conda env create -f environment.yml
```

Install [jq](https://stedolan.github.io/jq/download/) and run the following code in the root folder of the project to configure `git`.

```bash
git config --local include.path ../.gitconfig
```