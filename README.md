# learning-python


# Conda Environment Setup: Jupyter, Pandas, & Plotnine

This guide walks through the complete setup for a clean Conda environment configured.
Conda is a package manager that allows you to install libraries that extend the core functionality available with python.

Note: Before you begin, please download and unzip this GitHub Repository, Click the Green **< > Code button**, and choose **Download Zip**

---

## 1. Install Conda

To use Conda you'll first need to install [Conda Forge](https://conda-forge.org/download/). Choose the latest version for your operating system from the web page, download and install.

## 2. Create and Activate the Environment

Open Miniforge Prompt (Windows) or Terminal (Mac) and execute the following commands to set up the environment with Python:

```bash
# Create the environment
conda create -n learning_python

# Activate the environment
conda activate learning_python
```

---

## 3. Install Core Packages

Install Jupyter, `pandas`, `plotnine`, and `ipykernel` using the `conda-forge` channel for optimal package compatibility:

```bash
conda install -c conda-forge jupyter pandas plotnine ipykernel -y
```

---

## 4. Launch and Use

Launch your Jupyter interface:

```bash
jupyter notebook
```

