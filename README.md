# Penguins K-Means Clustering Analysis

A machine learning project that performs K-means clustering on penguin morphological data to identify natural groupings within the penguin population.

## Project Overview

This project demonstrates the complete workflow of clustering analysis including:
- Data loading and exploratory analysis
- Data preprocessing (handling categorical variables and standardization)
- Optimal cluster detection using the Elbow Method
- K-means clustering implementation
- Cluster statistics and interpretation

## Dataset

The analysis uses penguin morphological measurements including:
- `culmen_length_mm`: Bill length in millimeters
- `culmen_depth_mm`: Bill depth in millimeters
- `flipper_length_mm`: Flipper length in millimeters
- Additional categorical features

## Key Steps

1. **Data Loading & Exploration**: Load the penguins dataset and examine its structure
2. **Preprocessing**: 
   - Convert categorical variables to dummy/indicator variables
   - Standardize numerical features using StandardScaler
3. **Optimal Cluster Detection**: Use the Elbow Method to determine the optimal number of clusters (k=8)
4. **Clustering**: Apply K-means algorithm to segment the penguins into clusters
5. **Analysis**: Generate cluster statistics and visualizations

## Methodology

- **Algorithm**: K-Means Clustering
- **Optimal Clusters**: 8 (determined via Elbow Method)
- **Scaling**: StandardScaler for feature normalization
- **Visualization**: Matplotlib and cluster-based scatter plots

## Results

The model successfully identifies 8 distinct clusters within the penguin population, enabling detailed cluster-wise statistical analysis of morphological features.

## Requirements

See `requirements.txt` for all dependencies.

## Usage

Run the Jupyter notebook to execute the complete analysis:

```bash
jupyter notebook penguins_group.ipynb
```

Or use JupyterLab:

```bash
jupyter lab penguins_group.ipynb
```

## Installation

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Files

- `penguins_group.ipynb`: Main analysis notebook
- `penguins.csv`: Dataset containing penguin measurements
- `requirements.txt`: Python package dependencies
- `README.md`: Project documentation
- `.gitignore`: Git ignore rules

## Author

Machine Learning Analysis Project

## License

MIT License

## References

- [Scikit-learn K-Means Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [StandardScaler Scaling Importance](https://scikit-learn.org/stable/auto_examples/preprocessing/plot_scaling_importance.html)
