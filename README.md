# EASA Method Official Repository

Welcome to the official repository of the Edge-Attention SAM-Adapter (EASA) method. This repository serves as the primary source for accessing the EASA implementation, including pre-trained models, checkpoints, and a demonstration of its application in image manipulation localization tasks.

## Getting Started

To begin using the EASA method, follow the steps outlined below:
### Cloning the Repository

First, clone this repository to your local machine using the following git command:
```bash
git clone https://github.com/erliufashi/EASA-Method-Repository.git
cd EASA-Method-Repository
```
Replace `yourusername` with the actual username where the repository is hosted.

### Installing Dependencies

This project requires PyTorch for running the deep learning models. Install PyTorch by following the instructions on the [official PyTorch website](https://pytorch.org/get-started/locally/), ensuring compatibility with your system's CUDA version for GPU support.

```bash
pip install torch torchvision
```

### Using the Project

This repository includes a Jupyter Notebook `demo.ipynb` that demonstrates the usage of the EASA method. To run the notebook, ensure you have Jupyter installed:

```bash
pip install notebook
```

Then, start the Jupyter Notebook server:

```bash
jupyter notebook
```

Navigate to the `demo.ipynb` file within the Jupyter Notebook interface in your browser to view and run the demo.

### Checkpoints

The repository contains checkpoints of pre-trained models under the `checkpoints` directory. These can be loaded as per the instructions in `demo.ipynb` to reproduce our results or to use the EASA method for your tasks.

## Support

For any queries or support related to the EASA method, please open an issue in this repository.

---

Feel free to customize the README according to the specifics of your project, such as the actual repository URL, additional dependencies, or any special instructions related to your implementation of the EASA method.
