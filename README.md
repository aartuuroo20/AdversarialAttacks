# 🔐 Adversarial Attacks on ResNet-50 (CIFAR-10)

Este proyecto tiene como objetivo analizar la **vulnerabilidad del modelo ResNet-50** entrenado sobre el conjunto de datos **CIFAR-10**, frente a ataques adversarios. También se implementan y evalúan distintas **técnicas de defensa**, buscando mejorar la robustez del modelo ante amenazas en contextos de ciberseguridad.

---

## Contenido del Repositorio

### CIFAR10_resnet50.pth
Modelo preentrenado **ResNet-50** sobre CIFAR-10, utilizado como base para los experimentos adversariales y pruebas defensivas.

### Preparacion del dataset.ipynb
Notebook que:
- Carga y transforma el conjunto **CIFAR-10**
- Ajusta el formato para ser compatible con la arquitectura **ResNet-50**

### Ataque FGSM.ipynb
Implementación del ataque **Fast Gradient Sign Method**:
- Generación de ejemplos adversarios en un solo paso.
- Visualización de imágenes originales vs. perturbadas.
- Evaluación de la degradación del modelo.

### Ataque PGD.ipynb
Ejemplo del ataque **Projected Gradient Descent**:
- Versión iterativa más potente que FGSM.
- Explora distintas tasas de perturbación y número de iteraciones.

### Ataque OnePixel.ipynb
Implementación del **One Pixel Attack**:
- Ataque basado en **evolución diferencial**.
- Perturba solo **un único píxel** de la imagen.
- Requiere configuración cuidadosa de hiperparámetros.


