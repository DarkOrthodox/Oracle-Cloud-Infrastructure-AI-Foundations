# DeepDemo: Classification with Multilayer Perceptron

This repository demonstrates classification using a Multilayer Perceptron (MLP) on a synthetic dataset generated with `make_circles`. The notebook visualizes how changing the number of hidden units in the MLP affects the decision boundary.

## Features

- Generates a 2D synthetic dataset with two classes arranged in concentric circles.
- Visualizes the dataset and the MLP's decision boundary.
- Interactive widget to adjust the number of hidden units in the MLP and observe the effect in real-time.

## Requirements

- Python 3.x
- numpy
- matplotlib
- scikit-learn
- ipywidgets
- Jupyter Notebook

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/DeepDemo.git
    cd DeepDemo
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch the notebook:
    ```bash
    jupyter notebook DeepDemo.ipynb
    ```

## Usage

- Run all cells in the notebook.
- Use the slider to change the number of hidden units in the MLP and observe how the decision boundary adapts.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [scikit-learn](https://scikit-learn.org/)
- [ipywidgets](https://ipywidgets.readthedocs.io/)