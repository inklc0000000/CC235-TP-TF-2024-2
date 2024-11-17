# CC235-TP-TF-2024-2
Desarrollo del Trabajo Final de Procesamiento de Imagenes utilizando DenseNet y AlexNet
# Ojetivo del trabajo
Se desarrollará un modelo de clasificación de residuos usando redes convolucionales y DenseNet. Este sistema analizará imágenes de residuos sólidos y los clasificará en categorías como plástico, papel, metal y vidrio, facilitando la gestión de residuos y promoviendo la cultura del reciclaje en Lima
# Integrantes
- U202216895 - Nicolas Francisco Miranda Rafael
- U202212510 - Joaquín Eduardo Velarde Leyva
- U20221B751 - Daniel Ivan Carbajal Robles


# Dataset
El dataset contiene 4,752 imágenes en formato .jpg organizadas en diferentes categorías de residuos para la clasificación adecuada de materiales. Las categorías incluyen: Cardboard (cartón) con 461 imágenes de cajas y empaques, Food Organics con 411 imágenes de residuos alimenticios naturales o procesados, Glass (vidrio) con 420 imágenes de botellas, Metal con 790 imágenes de latas, Miscellaneous Trash con 495 imágenes de varios objetos como juguetes y pañales, Paper (papel) con 500 imágenes de revistas y productos de papel, Plastic (plástico) con 921 imágenes de envases y bolsas, Textile Trash con 318 imágenes de prendas en mal estado y Vegetation con 431 imágenes de plantas.

# Conclusiones
El entrenamiento de AlexNet mostró un desempeño inicial limitado, donde se obtuvo una precison en validación baja (19.39%) y una pérdida elevada, dado que la arquitectura de AlexNet es menos compleja que otros algoritmos. Por tanto, se decidió realizar más iteraciones para DenseNet,donde se obtuvo mayor precisión de validación.
A lo largo de los entrenamientos de DenseNet, se observaron mejoras graduales en la precisión. Sin embargo, las categorías como plástico y metal siguen mostrando altos falsos positivos y falsos negativos. Por ello, se decidió utilizar el tercer entrenamiento donde la precisión de validación es del 68.60%.
Link del dataset: https://www.kaggle.com/datasets/luvvalecha/real-waste-dataset

