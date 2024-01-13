Proyecto de Clasificación de Imágenes: Perro vs. Gato
Descripción
Este proyecto se centra en la creación de un modelo de clasificación de imágenes utilizando técnicas de Deep Learning para predecir si una imagen dada corresponde a un perro o a un gato. Se ha empleado un conjunto de datos compuesto por 20,000 imágenes para entrenar el modelo, buscando alcanzar la máxima precisión en las predicciones.

Estructura del Repositorio
src/: Contiene los scripts fuente del proyecto.

train_model.py: Script para entrenar el modelo.
predict.py: Script para realizar predicciones con el modelo entrenado.
data/: Directorio que almacena los datos utilizados para el entrenamiento.

train_data.csv: DataFrame que contiene información relevante sobre las imágenes de entrenamiento.
models/: Carpeta donde se guarda el modelo entrenado.

trained_model.h5: Archivo que contiene tanto los pesos como la arquitectura del modelo.
Configuración del Entorno
Se recomienda configurar un entorno virtual para ejecutar los scripts. Puedes instalar las dependencias necesarias ejecutando el siguiente comando:

bash
Copy code
pip install -r requirements.txt
Asegúrate de contar con TensorFlow, NumPy y otras dependencias esenciales.

Entrenamiento del Modelo
Para entrenar el modelo, ejecuta el script train_model.py. Puedes ajustar los parámetros del modelo, como el número de épocas y el tamaño del lote, según tus necesidades.

bash
Copy code
python src/train_model.py
El modelo entrenado se guardará en el directorio models/ con el nombre trained_model.h5.

Realización de Predicciones
Una vez que el modelo esté entrenado, utiliza el script predict.py para realizar predicciones sobre nuevas imágenes.

bash
Copy code
python src/predict.py path/to/image.jpg
Sustituye "path/to/image.jpg" con la ruta de la imagen que deseas clasificar.

¡Explora el proyecto y disfruta realizando predicciones! Si surge alguna pregunta o inconveniente, no dudes en abrir un problema en el repositorio.
