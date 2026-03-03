# CS-328: Numerical Methods for Visual Computing and ML (EPFL)

This repository contains Python implementations of core numerical algorithms used in computer graphics, vision, and machine learning. The projects focus on stability, efficiency, and applications like image deblurring, shape analysis, and differentiable rendering.

## 📂 Project Structure

### [Homework 1: Floating Point & Linear Systems](CS328-homework-1.ipynb)
- **Topics:** IEEE 754 arithmetic, error propagation, LU decomposition.
- **Implementation:** Analyzed catastrophic cancellation in geometric computations; implemented stable linear solvers for image processing tasks.
- **Key Concepts:** Numerical Stability, Condition Number, Forward/Backward Error.

### [Homework 2: Least Squares & Geometry Processing](CS328-homework-2.ipynb)
- **Topics:** Linear Least Squares, QR Factorization, Regularization.
- **Implementation:** Built a shape deformation engine using least-squares optimization; applied Tikhonov regularization for image deconvolution (deblurring).
- **Key Concepts:** Normal Equations, Sparse Matrices, Overdetermined Systems.

### [Homework 3: Dimensionality Reduction & PCA](CS328-homework-3.ipynb)
- **Topics:** Singular Value Decomposition (SVD), Principal Component Analysis (PCA).
- **Implementation:** Implemented "Eigenfaces" for facial recognition; compressed high-dimensional visual datasets while preserving variance.
- **Key Concepts:** Low-rank Approximation, Spectral Theory, Eigen-gap.

### [Homework 4: Optimization & Neural Networks](CS328-homework-4.ipynb)
- **Topics:** Non-linear Optimization, Automatic Differentiation (Autodiff).
- **Implementation:** Built a scalar-valued Autodiff engine from scratch (similar to PyTorch's core); trained a neural network to approximate functions and classify visual data.
- **Key Concepts:** Gradient Descent, Newton's Method, Computational Graphs.

## 🛠️ Technologies
- **Python**: NumPy, SciPy.
- **Visuals**: Matplotlib for plotting convergence and image results.
- **Tools**: Jupyter Notebooks for interactive analysis.