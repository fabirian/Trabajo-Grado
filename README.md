# Trabajo-Grado
# Generación Automática de Reportes Radiológicos

## Descripción

Este repositorio contiene el código para la generación automática de reportes radiológicos utilizando redes neuronales con mecanismos de atención. El modelo está diseñado para interpretar imágenes de rayos X y generar descripciones detalladas que pueden asistir a los radiólogos en su diagnóstico.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- `Iteracion 1/`: Primer acercamiento al procesamiento de texto.
- `Iteracion 2/`: Proceso de limpieza y filtrado de los datos.
- `Diagnostico PADCHEST/`: Datos originales.
- `Modelo_Final`: Scripts para preprocesamiento de datos, entrenamiento y evaluación del modelo.

## Requisitos

Para ejecutar el proyecto, necesitas tener instalado lo siguiente:

- Python 3.8+
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn

Puedes instalar las dependencias utilizando el archivo `requirements.txt`:

```bash
pip install -r requirements.txt

## Mecanismos de Atención

Este proyecto implementa dos tipos de mecanismos de atención:

1. **Self-Attention**: Utilizado en la arquitectura de Transformer para mejorar la interpretación de las imágenes.
2. **Bahdanau Attention**: Integrado en el decodificador para mejorar la generación de reportes.

## Contribuir

Si deseas contribuir al proyecto, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`).
3. Realiza los commits de tus cambios (`git commit -m 'Add some AmazingFeature'`).
4. Empuja tu rama (`git push origin feature/AmazingFeature`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para cualquier consulta o información adicional, puedes contactarnos en
[afgalindez@unicauca.edu.co](mailto:afgalindez@unicauca.edu.co) o
[santiagorap@unicauca.edu.co](mailto:santiagorap@unicauca.edu.com).

