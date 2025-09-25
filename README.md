# Adversarial Attacks on ResNet-50 (CIFAR-10)

This project is part of my Master's Thesis and aims to analyze the **vulnerability of the ResNet-50 model** trained on the **CIFAR-10 dataset** against adversarial attacks. It also implements and evaluates various **defense techniques**, seeking to improve the model's robustness against threats in cybersecurity contexts.

---

## Repository Contents

### `CIFAR10_resnet50.pth`
Pre-trained **ResNet-50** model on CIFAR-10, used as a base for adversarial experiments and defensive testing.

### `Dataset Preparation.ipynb`
Notebook that:
- Loads and transforms the **CIFAR-10** dataset
- Adjusts the format to be compatible with the **ResNet-50** architecture

### `FGSM Attack.ipynb`
Implementation of the **Fast Gradient Sign Method** attack:
- Generation of adversarial examples in a single step.
- Visualization of original vs. perturbed images.
- Evaluation of model degradation.

### `PGD Attack.ipynb`
Example of the **Projected Gradient Descent** attack:
- A more powerful iterative version of FGSM.
- Explores different perturbation rates and iteration numbers.

### `OnePixel Attack.ipynb`
Implementation of the **One Pixel Attack**:
- Attack based on **differential evolution**.
- Perturbs only **a single pixel** of the image.
- Requires careful configuration of hyperparameters.
