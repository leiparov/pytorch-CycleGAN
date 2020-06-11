# pytorch-CycleGAN
 
# Traducción de Imágenes


---


[Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/pdf/1703.10593v6.pdf).<br>
[Jun-Yan Zhu](https://people.eecs.berkeley.edu/~junyanz/)\*,  [Taesung Park](https://taesung.me/)\*, [Phillip Isola](https://people.eecs.berkeley.edu/~isola/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros). In ICCV 2017. (* equal contributions)


---
## Integrantes

*   Montalvo García, Peter
*   Rojas Bustamante, Leibnitz Pavel

## Descripción

Este notebook muestra la traducción de imagen a imagen a través de una arquitectura de redes neuronales conocida como CycleGan, tal como se describe en el artículo:  [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/pdf/1703.10593v6.pdf). El modelo propone un método para capturar las características de un dominio de imagen y descubrir de qué forma estas características podrían traducirse a otro dominio de imagem; todo en ausencia de ejemplos de entrenamiento emparejados.

CycleGan utiliza un función de pérdida cíclica para permitir que el entrenamiento se realice sin necesidad de emparejar los datos. En otras palabras, puede traducir de un dominio X a un dominio Y si necesidad de mapear uno a uno cada elemento en los dominios origen y destino.
