# Makemore_Shakespeare

This repository contains an implementation of a character-level language model inspired by Andrej Karpathy's YouTube series. The model is trained to generate text in the style of Shakespeare using the `tiny_shakespeare.txt` dataset.

## Contents

- `Mini_GPT.ipynb`: A Jupyter notebook containing the complete implementation of the character-level language model. This notebook includes the training process, model architecture, and text generation.

- `tiny_shakespeare.txt`: The dataset used for training, containing a collection of Shakespeare's works in plain text.

## Requirements

To run the notebook, you will need the following dependencies:

- Python 3.x
- PyTorch

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/Daimon5/Mini_GPT.git
    ```
2. Run the notebook cells to train the model and generate text.

## How to Use

- **Training the Model**:
    - Follow the steps in the notebook to train the character-level language model on the `tiny_shakespeare.txt` dataset.
    - You can adjust hyperparameters within the notebook for different results.

- **Generating Text**:
    - After training, use the notebook to generate Shakespeare-like text.
    - The generated text will imitate the style of Shakespeare but may contain imperfections due to the simplicity of the model.

## References

- [Andrej Karpathy's YouTube Series](https://www.youtube.com/watch?v=Py4xvZx-A1E)
- [Original Char-RNN Paper](https://arxiv.org/abs/1506.02078)
- [PyTorch Documentation](https://pytorch.org/docs/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
