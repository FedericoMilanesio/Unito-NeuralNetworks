# Tutorial Notebooks for Pytorch
This repository contains Jupyter notebooks used to tutor students in the [Neural Networks](https://www.fisicamagistrale.unito.it/do/corsi.pl/Show?_id=6e6f) and [Deep Learning](https://fisica-sc.campusnet.unito.it/do/corsi.pl/Show?_id=curx) courses during the academic years 2023/2024, 2024/2025, and 2025/2026. The tutorials cover various topics related to PyTorch, a popular deep learning framework.

### Contents
The repository includes the following notebooks:

*Lesson 0* - **Introduction to Python**: An overview of Python for those who have never coded before

*Lesson 1* - **Pytorch**: This notebook covers the main features of Torch, including its basic operations, tensor manipulation, and autograd

*Lesson 2* - **Building Neural Networks**: We cover PyTorch's torch.nn module, with topics such as defining network architectures, implementing forward and backward passes, and optimizing models with different optimization algorithms

*Lesson 3* - **Convolutional Neural Networks**: We dive into the world of CNNs with PyTorch. This notebook demonstrates how to create CNN architectures for image classification tasks. In it, we also discuss the difference between GPUs and CPUs and how to perform data augmentation.

*Lesson 4* - **Autoencoders**: A shorter lesson with the basics of how to implement and train a simple autoencoder for MNIST digits

*Lesson 5* - **Setting up a project**: In this notebook, we explain how to find a dataset and upload it to PyTorch, how to tune your model hyperparameters, and how to create a saliency map


### Usage
You can either run these notebooks on Google Colab or download them to your local machine and execute them using Jupyter Notebook or JupyterLab. To run them locally, ensure you have Python installed, then run:

```bash
pip install -r requirements.txt
```

If you want GPU support for PyTorch, install it separately first:

```bash
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121
pip install -r requirements.txt
```

You can also use conda to create an environment first:

```bash
conda create -n unito-nn python=3.10
conda activate unito-nn
pip install -r requirements.txt
```

### Feedback and Contributions
We welcome any feedback or contributions to improve these tutorials. Feel free to open an issue or submit a pull request with your suggestions, corrections, or additional content.

### Authors
The tutorials were originally developed by Federico Milanesio and Davide Pirovano at UniTO, both as PhD students working in neural networks and deep learning. In 2025, Samuele Marabotto took over from Davide as tutor and helped update and revise the tutorials for the current edition.

Federico Milanesio - federico.milanesio@unito.it

Davide Pirovano - davide.pirovano@unito.it

Samuele Marabotto - samuele.marabotto@unito.it

### License
© 2024. This work is openly licensed via [CC BY-NC-SA 4.0 DEED](https://creativecommons.org/licenses/by-nc-sa/4.0/)
