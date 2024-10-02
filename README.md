
# Explainable-AI-Techniques

This repository contains a Jupyter notebook demonstrating an explainable AI technique (LIME) using a pre-trained ResNet34 model.

## Repository Structure

```
.
├── .gitignore
├── Explainable AI.ipynb
├── imagenet_labels.json
└── README.md
```

- **Explainable AI.ipynb**: Jupyter notebook demonstrating explainable AI techniques.
- **imagenet_labels.json**: JSON file containing ImageNet class labels.

## Dependencies

To run the notebook, you need the following dependencies:

- Python 3.x
- Jupyter Notebook
- PyTorch
- Torchvision
- PIL (Python Imaging Library)
- LIME (Local Interpretable Model-agnostic Explanations)

You can install the required packages using `pip`:

```sh
pip install torch==2.3 torchvision==0.18 numpy==2.0 lime
```

## Usage

1. Clone the repository:

```sh
git clone https://github.com/yourusername/Explainable-AI-Techniques.git
cd Explainable-AI-Techniques
```

2. Open the Jupyter notebook:

```sh
jupyter notebook "Explainable AI.ipynb"
```

3. Run the notebook cells to see the explainable AI techniques in action.

## Explanation

The notebook demonstrates the following:

- Loading and preprocessing an image of a tiger shark.
- Using a pre-trained ResNet34 model to predict its label.
- Interpreting the model's predictions using the LIME Image Explainer.