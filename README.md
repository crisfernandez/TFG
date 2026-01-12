# Trabajo de Fin de Grado

Cristina Fernández Gómez - cristina.fgomez@alumnos.upm.es 

Escuela Técnica Superior de Ingenieros Informáticos

Universidad Politécnica de Madrid

Dentro de este proyecto llamado 'EEG e Inteligencia Artificial para el Análisis de Respuestas Cerebrales a la Confianza' encontramos diversos ficheros:
## Estructura del Repositorio
### 1. `/models`
Contiene los artefactos generados tras el entrenamiento:
* **`.pt`**: Pesos del modelo y estado del optimizador.
* **`.pkl`**: Configuración con los hiperparámetros.
* **`.json`**: Historial de entrenamiento (Loss y Accuracy).

### 2. `/Predicciones`
* **`.xlsx`**: Resultados de las predicciones sobre el conjunto de test para cada participante.

### 3. `/scripts`
* **`.ipynb`**: Cuadernos de Jupyter individuales por participante.

### 4. Visualización y Gráficas
Scripts específicos para la generación de figuras de la memoria:
* **oversampling_pesos**: Gráficas que muestran del impacto de las técnicas de oversampling y pesos ponderados.
* **f1-score**: Gráficas en las que se observa la evolución del f1-score durante la etapa de entrenamiento.
* **balanceo_clases**: Visualización de la distribución de muestras.
* **seleccion_caracteristicas**: Visualización del impacto de las técnicas de selección de características.

### 5. Requirements
  Las dependencias necesarias para ejecutar el proyecto.
