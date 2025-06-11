# eigenfaces-face-recognition

> Face Recognition with Eigenfaces (PCA)

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/eigenfaces-face-recognition)
![License](https://img.shields.io/github/license/J1u2a3n8/eigenfaces-face-recognition)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/eigenfaces-face-recognition)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/eigenfaces-face-recognition?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/eigenfaces-face-recognition)

## Description

Classic computer vision implementation of face recognition using Principal Component Analysis (Eigenfaces). Includes dataset preprocessing, PCA dimensionality reduction, classifier training (SVM/k-NN), and real-time recognition demo with OpenCV.

## Architecture

CV Pipeline: Image Loading → Preprocessing → PCA (Eigenfaces) → Feature Extraction → Classification → Visualization

## Quick Start

### Prerequisites

.NET 8 SDK, Visual Studio 2022 / VS Code with C# Dev Kit

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/eigenfaces-face-recognition.git
cd eigenfaces-face-recognition

pip install -r requirements.txt
# jupyter lab
```

### Usage

```bash
jupyter notebook notebooks/eigenfaces-face-recognition.ipynb
```

## Testing

```bash
pytest tests/
```

## Project Structure

```
eigenfaces-face-recognition/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

Python, OpenCV, NumPy, Scikit-learn, Matplotlib, Jupyter

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://www.linkedin.com/in/juan-luis-canedo-villarroel-189783227/)

---

⭐ If you found this project useful, give it a star!
