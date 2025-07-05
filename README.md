# Proyecto Educativo de Sistemas de Recomendación

Este proyecto tiene como finalidad servir como una base de conocimiento práctica y teórica para explorar múltiples temas asociados a sistemas de recomendación. A través de una serie de módulos progresivos, se abordan conceptos clave como evaluación de modelos, optimización, diversidad, contexto, usuarios fríos y mitigación de sesgos.

## Estructura del Proyecto

El proyecto está dividido en 10 módulos, cada uno con un foco específico de aprendizaje y desarrollo:

| Módulo | Tema principal                              | Tecnologías utilizadas            |
|--------|---------------------------------------------|-----------------------------------|
| 1      | Exploración del dataset (EDA)               | Python, pandas, matplotlib        |
| 2      | Modelos básicos de recomendación            | `surprise`, `cornac`              |
| 3      | Evaluación de métricas                      | RMSE, MAE, Precision@k, NDCG@k    |
| 4      | Visualización de resultados                 | matplotlib, seaborn               |
| 5      | Diversidad y cobertura del catálogo         | análisis intra-lista, cobertura   |
| 6      | Optimización de hiperparámetros             | Grid search, random, genéticos    |
| 7      | Simulación dinámica                         | batch por tiempo, reentrenamiento |
| 8      | Recomendación contextual artificial         | Cornac, simulación de contexto    |
| 9      | Mitigación de sesgos de popularidad         | penalización, re-ranking          |
| 10     | Usuarios fríos                              | filtrado vs híbrido (simulado)    |

## Cómo empezar

```bash
# Clonar el repositorio
git clone https://github.com/IvannPeralta/recommender-system.git
cd recommender-system

# Crear entornos e instalar dependencias
python3 -m venv surprise-venv
source surprise-venv/bin/activate
pip install -r requirements_surprise.txt
deactivate 

python3 -m venv cornac-venv
source cornac-venv/bin/activate
pip install -r requirements_cornac.txt


# Ejecutar notebook
jupyter notebook 
