# 🎬 GUION PARA VIDEO EXPLICATIVO - APLICACIÓN DE MACHINE LEARNING

## 📋 ESTRUCTURA DEL VIDEO (3 INTEGRANTES)

---

## 🎥 **INTRODUCCIÓN (30 segundos)**
**Todos los integrantes juntos**

- "Hola, somos [Nombre 1], [Nombre 2] y [Nombre 3]"
- "Hoy les presentamos nuestra aplicación web de Machine Learning que predice el abandono de clientes y realiza clustering de tarjetas de crédito"
- "Utilizamos tres modelos: Regresión Logística, K-Nearest Neighbors y K-Means"

---

## 👤 **INTEGRANTE 1: REGRESIÓN LOGÍSTICA (3-4 minutos)**

### 1. Introducción al modelo (30 seg)
- "Yo me encargué del modelo de **Regresión Logística**"
- "Este es un modelo supervisado de clasificación que predice la probabilidad de que un cliente abandone el servicio"
- "Utiliza el dataset de Telco Customer Churn"

### 2. Explicación técnica breve (1 min)
- "La Regresión Logística calcula la probabilidad usando una función sigmoide"
- "Es ideal para problemas de clasificación binaria (Abandono: Sí/No)"
- "Entrenamos el modelo con variables como género, servicios contratados, facturación, etc."

### 3. Demostración en la web (2 min)
- Abrir la aplicación web
- Seleccionar "Regresión Logística" en el sidebar
- **Completar el formulario con datos ficticios:**
  - Género: Masculino
  - Adulto Mayor: No
  - Pareja: Sí
  - Dependientes: No
  - Tiempo: 24 meses
  - Servicios: Completar todos los campos
  - Facturación: Cargos mensuales y totales
- Hacer clic en "Predecir"
- **Mostrar y explicar los resultados:**
  - "Como pueden ver, el modelo predice una probabilidad de abandono del X%"
  - "La clasificación es: [Sí/No] Abandono"
  - **Explicar la tabla de probabilidades:**
    - "Esta tabla muestra la probabilidad de abandono vs no abandono"
    - "El gráfico de barras visualiza estas probabilidades"
  - "El modelo también muestra un indicador de progreso que representa la probabilidad"

### 4. Reflexión personal (30 seg)
- **Dificultades:** "Tuve que lidiar con el preprocesamiento de datos categóricos y numéricos"
- **Aprendizaje:** "Aprendí cómo funciona la función sigmoide y cómo interpretar probabilidades"
- **Mejora:** "Podríamos agregar más variables o usar técnicas de balanceo de clases"

---

## 👤 **INTEGRANTE 2: K-NEAREST NEIGHBORS - KNN (3-4 minutos)**

### 1. Introducción al modelo (30 seg)
- "Yo trabajé con el modelo **K-Nearest Neighbors (KNN)**"
- "Es un algoritmo supervisado que clasifica basándose en los 'k' vecinos más cercanos"
- "También usa el dataset de Telco Customer Churn"

### 2. Explicación técnica breve (1 min)
- "KNN busca los k clientes más similares en el dataset de entrenamiento"
- "La clasificación se basa en la mayoría de los vecinos más cercanos"
- "Es un algoritmo no paramétrico, no hace suposiciones sobre la distribución de los datos"
- "Elegimos k=5 después de validar con diferentes valores"

### 3. Demostración en la web (2 min)
- Seleccionar "K-Nearest Neighbors (KNN)" en el sidebar
- **Usar los MISMOS datos que el Integrante 1** (para comparar)
- Hacer clic en "Predecir"
- **Mostrar y explicar los resultados:**
  - "KNN clasifica este cliente como: [Sí/No] Abandono"
  - "A diferencia de Regresión Logística, KNN no da probabilidades, solo clasificación"
  - **Explicar la diferencia:**
    - "Regresión Logística nos da una probabilidad (ej: 65% de abandono)"
    - "KNN nos da una clasificación directa (Sí o No)"
  - "Esto es útil cuando solo necesitamos saber si un cliente va a abandonar o no"

### 4. Reflexión personal (30 seg)
- **Dificultades:** "Tuve que normalizar los datos y encontrar el valor óptimo de k"
- **Aprendizaje:** "Comprendí cómo funciona la distancia euclidiana y la importancia de normalizar datos"
- **Mejora:** "Podríamos implementar diferentes métricas de distancia o usar validación cruzada para optimizar k"

---

## 👤 **INTEGRANTE 3: K-MEANS CLUSTERING (3-4 minutos)**

### 1. Introducción al modelo (30 seg)
- "Yo implementé el modelo **K-Means Clustering**"
- "Es un algoritmo no supervisado que agrupa clientes en clusters según sus características"
- "Utiliza el dataset de Credit Card para clustering"

### 2. Explicación técnica breve (1 min)
- "K-Means agrupa clientes similares en clusters"
- "No necesita etiquetas, encuentra patrones por sí solo"
- "Usamos el método del codo y silhouette para encontrar el número óptimo de clusters"
- "Encontramos que 4 clusters es el número óptimo"

### 3. Demostración en la web (2 min)
- Seleccionar "K-Means Clustering" en el sidebar
- **Completar el formulario con datos ficticios de tarjeta de crédito:**
  - **Tab "Balance y Compras":**
    - Saldo: 2000
    - Compras: 1500
    - Compras únicas: 800
    - Compras a plazos: 700
  - **Tab "Frecuencias":**
    - Frecuencia de compras: 0.5
    - Frecuencia única: 0.3
    - Frecuencia a plazos: 0.2
  - **Tab "Pagos y Límites":**
    - Pagos mínimos: 200
    - Pagos completos: 1500
    - Límite de crédito: 10000
    - Tiempo (meses): 12
- Hacer clic en "Predecir"
- **Mostrar y explicar los resultados:**
  - "El cliente fue asignado al Cluster [número]"
  - **Explicar el perfil del cluster:**
    - "Este cluster representa clientes con [características]"
    - "Por ejemplo: clientes con saldo medio, compras moderadas, etc."
  - **Mostrar la tabla de características del cluster:**
    - "Esta tabla muestra el perfil promedio del cluster"
    - "Nos ayuda a entender qué tipo de cliente es"

### 4. Reflexión personal (30 seg)
- **Dificultades:** "Fue desafiante interpretar los clusters y crear perfiles significativos"
- **Aprendizaje:** "Aprendí sobre clustering no supervisado y cómo interpretar resultados sin etiquetas"
- **Mejora:** "Podríamos usar técnicas de reducción de dimensionalidad como PCA para visualizar mejor los clusters"

---

## 🤝 **REFLEXIÓN FINAL - TODOS JUNTOS (2-3 minutos)**

### Dificultades encontradas (1 min)
**Integrante 1:** "El preprocesamiento de datos fue complejo, especialmente manejar valores faltantes y variables categóricas"

**Integrante 2:** "Encontrar el valor óptimo de k para KNN requirió mucha experimentación y validación"

**Integrante 3:** "Interpretar los clusters y crear perfiles significativos fue desafiante sin etiquetas previas"

### Qué aprendieron (1 min)
**Integrante 1:** "Aprendí sobre modelos supervisados, probabilidades y cómo interpretar resultados de clasificación"

**Integrante 2:** "Comprendí algoritmos basados en instancias y la importancia de la normalización de datos"

**Integrante 3:** "Aprendí sobre aprendizaje no supervisado y cómo encontrar patrones en datos sin etiquetas"

**Todos:** "Aprendimos a integrar modelos de ML en una aplicación web funcional usando Streamlit"

### Cómo podrían mejorar el sistema (1 min)
- **Integrante 1:** "Agregar más variables o usar técnicas de balanceo de clases para mejorar la precisión"
- **Integrante 2:** "Implementar validación cruzada para optimizar hiperparámetros automáticamente"
- **Integrante 3:** "Usar técnicas de reducción de dimensionalidad para visualizar clusters mejor"
- **Todos:** "Podríamos agregar más visualizaciones, implementar autenticación de usuarios, o desplegar en la nube"

---

## 🎬 **CIERRE (30 segundos)**
**Todos juntos**

- "Gracias por ver nuestra presentación"
- "Pueden encontrar el código en nuestro repositorio de GitHub: [enlace]"
- "Cualquier pregunta, estamos a su disposición"

---

## 📝 **NOTAS IMPORTANTES PARA LA GRABACIÓN:**

1. **Datos ficticios consistentes:** Usar los mismos datos para Regresión Logística y KNN para poder comparar resultados

2. **Tiempo total:** Aproximadamente 12-15 minutos

3. **Transiciones:** Cada integrante debe hacer una transición suave al siguiente

4. **Pantalla compartida:** Mostrar claramente la aplicación web y los resultados

5. **Explicar las tablas:** No solo mostrar, sino explicar qué significan los números

6. **Comparar modelos:** Mencionar las diferencias entre los modelos supervisados (Regresión Logística vs KNN)

---

## 🎯 **PUNTOS CLAVE A DESTACAR:**

✅ **Regresión Logística:** Da probabilidades (0-100%)
✅ **KNN:** Da clasificación directa (Sí/No)
✅ **K-Means:** Agrupa clientes similares sin etiquetas previas
✅ **Aplicación funcional:** Interfaz web interactiva
✅ **Modelos entrenados:** Pre-cargados y listos para usar
✅ **Visualizaciones:** Gráficos y tablas para interpretar resultados


