# Trabajo-Grado
## Generación Automática de Reportes Radiológicos

### Descripción

Este repositorio contiene el código para la generación automática de reportes radiológicos utilizando redes neuronales con mecanismos de atención. El modelo está diseñado para interpretar imágenes de rayos X y generar descripciones detalladas que pueden asistir a los radiólogos en su diagnóstico.

### Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- `Archivos_csv/`: Archivos con los datos para entrenar y probar el modelo.
- `Diagnostico PADCHEST/`: Datos originales.
- `Iteracion 1/`: Primer acercamiento al procesamiento de texto.
- `Iteracion 2/`: Proceso de limpieza y filtrado de los datos.
- `Modelo_Final.ipynb`: Scripts para preprocesamiento de datos, entrenamiento y evaluación del modelo, para probar en Colab.
- `modelo.py`: Script principal para preprocesamiento de datos, entrenamiento y evaluación del modelo.

### Requisitos

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
```

### Descargar y Ejecutar el Modelo

1. **Descargar el archivo del modelo:**
   - Dirígete a la carpeta donde se encuentra el archivo `modelo.py` en el repositorio.

2. **Preparar los datos:**
   - Asegúrate de tener los archivos CSV necesarios en la carpeta `Archivos_csv/`.

3. **Ejecutar el modelo:**
   - Abre una terminal y navega al directorio donde está ubicado el archivo `modelo.py`.
   - Ejecuta el script para cargar el modelo y realizar la inferencia con los datos en la carpeta `Archivos_csv/`. Usa el siguiente comando:

     ```bash
     python modelo.py
     ```

   - El script `modelo.py` está diseñado para realizar el preprocesamiento, entrenamiento y evaluación del modelo utilizando los datos en `Archivos_csv/`.

### Mecanismos de Atención

Este proyecto implementa dos tipos de mecanismos de atención:

1. **Self-Attention**: Utilizado en la arquitectura de Transformer para mejorar la interpretación de las imágenes.
2. **Bahdanau Attention**: Integrado en el decodificador para mejorar la generación de reportes.

### Dataset

Este proyecto utiliza el dataset PADChest-COVID-19 para entrenamiento y evaluación. Puedes descargar el dataset desde los siguientes enlaces:

- [Repositorio PADChest-COVID-19 en GitHub](https://github.com/BIMCV-CSUSP/BIMCV-COVID-19/tree/master/padchest-covid#data-sources-bimcv-padchest)
- [Descargar desde BSC-TranBioNet](https://b2drop.bsc.es/index.php/s/BIMCV-PadChest)

Asegúrate de seguir las instrucciones en el repositorio para obtener los datos correctos y para su adecuada integración en tu entorno de trabajo.

### Licencia
Este proyecto está licenciado bajo la Licencia Pública General de GNU v3.0 (GPL 3.0). Para más detalles, consulta el archivo LICENSE.md.

### Contribuir

Si deseas contribuir al proyecto, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio [Trabajo-Grado](https://github.com/fabirian/Trabajo-Grado).
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`).
3. Realiza los commits de tus cambios (`git commit -m 'Add some AmazingFeature'`).
4. Empuja tu rama (`git push origin feature/AmazingFeature`).
5. Abre un Pull Request en el repositorio original.

### Contacto

Para cualquier consulta o información adicional, puedes contactarnos en:

- [afgalindez@unicauca.edu.co](mailto:afgalindez@unicauca.edu.co)
- [santiagorap@unicauca.edu.co](mailto:santiagorap@unicauca.edu.co)
