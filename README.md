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

- **Update Anaconda **:
  ```bash
  conda update conda
  ```

