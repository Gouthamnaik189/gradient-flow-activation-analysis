# 📉 Gradient Flow Activation Analysis

## Project Overview
This project is an academic tutorial demonstrating how different **activation functions** fundamentally influence **gradient flow** and training stability in deep neural networks.

The core experiment uses a custom PyTorch model to train on the MNIST dataset, focusing specifically on measuring the **gradient norm** (magnitude of the learning signal) across layers to quantify the **vanishing gradient problem**.

## 🚀 Key Findings
The tutorial proves the theoretical differences between activation functions:

* **Sigmoid & Tanh:** Gradient norms drop instantly to near zero (Vanishing Gradient), making deep learning infeasible.
* **ReLU & LeakyReLU:** Maintain high, stable gradient norms, enabling stable optimization of deep networks.
* **GELU:** Offers the best balance of stability and empirical performance.

## 📁 Repository Contents

* **`Activation Functions Influence Gradient Flow in Deep Neural Networks.pdf`** (or `.docx`): The main tutorial report analyzing the results and theory.
* **`gradient_flow_analysis_with_activation_functions.ipynb`**: The complete source code, model definition, training loop, and plotting steps.
* **`LICENSE`**: The MIT License governing usage of this code.

## 🛠️ Requirements

This project requires Python 3.x and the following libraries:

```bash
pip install torch torchvision matplotlib numpy

```markdown
## How to Run the Experiment

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Gouthamnaik189/gradient-flow-activation-analysis]
    cd [gradient-flow-activation-analysis]
    ```

2.  **Install Libraries:**
    Install the necessary packages using the command line:
    ```bash
    pip install torch torchvision matplotlib numpy
    ```

3.  **Execute the Notebook:**
    Open the file **`gradient_flow_analysis_with_activation_functions (1).ipynb`** in a Jupyter environment (e.g., JupyterLab, VS Code, or Google Colab) and run all cells sequentially.
