# Prediccion de Abandono de Clientes en Beta Bank

## Descripcion del Proyecto

Beta Bank enfrenta una perdida gradual de clientes cada mes. Retener a los clientes actuales es mas economico que atraer nuevos, por lo que se requiere un modelo predictivo que determine si un cliente dejara el banco pronto, utilizando datos de comportamiento pasado.

## Objetivo

El objetivo es desarrollar un modelo con un valor F1 minimo de 0.59 y medir la metrica AUC-ROC para compararla con el valor F1.

## Datos

Los datos incluyen informacion sobre:

- ID de cliente
- Puntuacion de credito
- Pais de residencia
- Genero
- Edad
- Periodo de tenencia
- Saldo de cuenta
- Numero de productos bancarios
- Si tiene tarjeta de credito
- Si es miembro activo
- Salario estimado
- Si el cliente ha dejado el banco

## Pasos Realizados

1. **Exploracion de Datos:** Entendimiento de la estructura y contenido de los datos.
2. **Preprocesamiento de Datos:** Manejo de valores faltantes, escalado de caracteristicas y codificacion de variables categoricas.
3. **Division de Datos:** Division en conjuntos de entrenamiento y prueba.
4. **Entrenamiento de Modelos:** Modelos de clasificacion incluyendo Regresion Logistica, Arbol de Decision y Bosque Aleatorio.
5. **Evaluacion de Modelos:** Evaluacion utilizando F1-score y AUC-ROC.
6. **Seleccion del Mejor Modelo:** Seleccion basado en el mejor rendimiento.

## Conclusiones

- **Objetivo Cumplido:** Se alcanzo un F1-score maximo de 0.59.
- **Desafios del Desbalance de Clases:** El desbalance afecto el rendimiento de los modelos, especialmente en la clase minoritaria.
- **Desempeno de los Modelos:** El Bosque Aleatorio mostro el mejor rendimiento con un F1-score equilibrado.
- **Mejoras Futuras:** Ajuste de hiperparametros y tecnicas adicionales para mejorar el recall y rendimiento general del modelo.

## Librerias Utilizadas

- Pandas
- Numpy
- Scikit-learn
- Matplotlib

