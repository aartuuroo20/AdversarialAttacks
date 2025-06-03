# AdversarialAttacks

Este proyecto tiene como objetivo analizar la vulnerabilidad del modelo ResNet-50, entrenado sobre el conjunto de datos CIFAR-10, frente a ataques adversarios. Además, se implementan y evalúan distintas técnicas de defensa para mejorar la robustez del modelo en contextos de ciberseguridad.

# Contenido del Repositorio
CIFAR10_resnet50.pth: Modelo ResNet-50 entrenado sobre el dataset CIFAR-10, utilizado como base para los ataques y pruebas de defensa.

Preparacion del dataset.ipynb: Notebook que contiene la carga, transformación y preparación del conjunto CIFAR-10 para su uso con ResNet-50.

Ataque FGSM.ipynb: Implementación del ataque Fast Gradient Sign Method (FGSM), análisis del impacto sobre el modelo y visualización de resultados.

Ataque PGD.ipynb: Implementación del ataque Projected Gradient Descent (PGD), incluyendo generación iterativa de ejemplos adversariales.

Ataque OnePixel.ipynb: Implementación del One Pixel Attack mediante evolución diferencial. Este ataque ha requerido una implementación compleja y cuidadosa configuración de parámetros para garantizar su funcionalidad.
