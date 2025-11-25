# anime-recommender-system-or-unsupervised-learning-project
Project to predict how a user will rate an anime title they have not yet viewed

## Environment Setup with Anaconda

### Prerequisites
- Anaconda or Miniconda installed on your system
- Git (for cloning the repository)

### Creating the Environment

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone <repository-url>
   cd anime-recommender-system-or-unsupervised-learning-project
   ```

2. **Create the Anaconda environment**:
   ```bash
   conda create --name anime-recommender python=3.9
   ```
   
   > You can replace `3.9` with another Python version if needed (e.g., `3.10`, `3.11`)

3. **Activate the environment**:
   - **Windows**:
     ```bash
     conda activate anime-recommender
     ```
   - **macOS/Linux**:
     ```bash
     conda activate anime-recommender
     ```

4. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   
   Or, if using a `conda` environment file (if available):
   ```bash
   conda env update --file environment.yml --prune
   ```

### Deactivating the Environment

When you're finished working, deactivate the environment:
```bash
conda deactivate
```

### Removing the Environment

To completely remove the environment:
```bash
conda env remove --name anime-recommender
```

### Useful Anaconda Commands

- **List all environments**:
  ```bash
  conda env list
  ```
  
- **View environment information**:
  ```bash
  conda info
  ```

- **Update Anaconda**:
  ```bash
  conda update conda
  ```

## Project Structure

```
anime-recommender-system-or-unsupervised-learning-project/
│
├── data/                    # Datasets and data files
│   └── (raw and processed data)
│
├── notebooks/               # Jupyter notebooks for exploration and analysis
│   └── (analysis, EDA, model experimentation)
│
├── src/                     # Python scripts and modules
│   └── (reusable functions, model classes, utilities)
│
├── docs/                    # Documentation
│   └── (project documentation, API docs, etc.)
│
├── README.md                # Project overview and instructions
├── requirements.txt         # Project dependencies
└── .gitignore               # Git ignore file

```

### Directory Descriptions

- **`/data`**: Contains datasets used for training and testing. Organize into subdirectories like `/raw` for original data and `/processed` for cleaned data.
- **`/notebooks`**: Jupyter notebooks for data exploration, analysis, and model development. Useful for interactive development.
- **`/src`**: Reusable Python modules and scripts including data preprocessing, model training, and utility functions.
- **`/docs`**: Documentation files including project documentation, API references, and guides.
- **`requirements.txt`**: Lists all Python package dependencies for easy environment reproduction.

