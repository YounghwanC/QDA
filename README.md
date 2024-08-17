# Discriminative vs. QDA: A Comparative Analysis

This repository contains a series of Jupyter notebooks that explore the differences between a discriminative model and a Quadratic Discriminant Analysis (QDA) model. The notebooks are designed to incrementally build on each other, starting with basic 2D visualizations and extending to more complex 3D visualizations using synthetic data generated from Gaussian distributions.

## Notebooks Overview

### 1. `Discriminative-vs-QDA-One-Gaussian.ipynb`
In this notebook, we introduce the core concepts behind discriminative models and QDA. We compare their performances on data generated from a single 2-dimensional Gaussian distribution. The notebook covers:
- Generating 2D synthetic data.
- Implementing a discriminative model and QDA from scratch.
- Visualizing decision boundaries in a 2D space.
- Analyzing the models' performances using misclassification error rates.

This notebook serves as the foundation for understanding the differences between the two models in a simple 2D setting.

### 2. `Discriminative-vs-QDA-Two-Gaussians.ipynb`
Building on the first notebook, this analysis extends the comparison to data generated from two distinct Gaussian distributions. The key elements include:
- Generating more complex synthetic data from two different Gaussian distributions.
- Extending the implementation of the discriminative model and QDA to handle this more complex scenario.
- Visualizing the decision boundaries in a 2D space to observe how the models adapt to the new data distribution.
- Further analysis of model performance in this more challenging setting.

This notebook is crucial for understanding how model performance varies when the data becomes more complex.

### 3. `Discriminative-vs-QDA-3D-Visualization.ipynb`
This notebook is an extension of the `Discriminative-vs-QDA-One-Gaussian.ipynb` and introduces 3D visualization to the analysis. Here, we explore:
- Generating 3D synthetic data from a Gaussian distribution.
- Training both the discriminative model and QDA on this 3D data.
- Visualizing the decision boundaries in a 3-dimensional space using `mayavi`.
- Comparing the models' performances with a focus on how they behave in higher-dimensional settings.

This notebook provides a more advanced visualization technique to better understand the decision boundaries in 3D space.

## License
This work is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the content in this repository, provided you give appropriate credit to the original author.

## Contributing
Contributions to this repository are welcome. If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## Contact
For any questions or further information, please contact:
- **Younghwan Brian Cho** - [yhcho9270@gmail.com](yhcho9270@gmail.com)
