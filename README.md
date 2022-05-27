
- [TODO](#todo)
- [Folder Structure](#folder-structure)
- [Setup](#setup)
## TODO
- [X] add conda setup guide

## Folder Structure

```
├───data
│   ├───processed           -> processed data
│   └───raw                 -> unnormalised data
├───docs                    -> documentations, project plans
├───htmlcov
│   └───coverage
├───myproject
│   └───__pycache__
├───results                 -> analysis output, figures
├───src                     -> scripts and notebooks
│   └───01_preprocessing    -> data download and preprocessing
└───tests                   -> unit tests
    └───__pycache__
```

## Setup

Clone the git folder.

```
git clone https://github.com/mdmanurung/learn-to-code.git
```

Download the latest miniconda. Click [here](https://docs.conda.io/en/latest/miniconda.html) for the installation guide.

Create conda environment from the `environment.yml` file.

```bash
conda env create -f environment.yml
```

Activate conda environment

```
conda activate learn-to-code
```