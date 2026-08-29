# Installation and Usage

## Repository Structure
```
Liver_Lipidomics_Paper/
├── data/
├── environment.yml
├── LICENSE
├── model
│   ├── best_params.json
│   ├── Healthy_vs_MASH_model.pkl
│   ├── Healthy_vs_NoMASH_model.pkl
│   └── NoMASH_vs_MASH_model.pkl
├── README.md
└── src
    ├── hyperparameter_tuning_notebook.ipynb
    ├── machine_learning_Healthy_vs_MASH.ipynb
    ├── machine_learning_Healthy_vs_NoMASH.ipynb
    ├── machine_learning_NoMASH_vs_MASH.ipynb
    └── preprocessing_notebook.ipynb
```

## Installation and Usage

### Requirements
- python == 3.11.0
- git == 2.7.4
- conda == 23.9.0

### Conda Installation
```
# Clone GitHub Repository
git clone https://github.com/rajanbit/Liver_Lipidomics_Paper.git

# Install conda environment using yml file
cd Liver_Lipidomics_Paper
conda env create -f environment.yml
```

### Usage
```
# Activate conda environment
conda activate ml

# Launch Jupyter Notebook
cd Liver_Lipidomics_Paper/src/
jupyter-notebook
```

