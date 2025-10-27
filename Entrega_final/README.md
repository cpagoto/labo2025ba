Este notebook fue adaptado para que la Optimización Bayesiana (mlrMBO) maximice la ganancia económica del modelo en lugar del AUC. Se redefinió la funcion objetivo como "EstimarGanancia_lightgbm".
La BO evalúa distintos conjuntos de hiperparámetros de LightGBM buscando maximizar la ganancia económica esperada del modelo según la matriz de beneficios definida.
