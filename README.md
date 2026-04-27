# 🚀 OLIST GROWTH ENGINE

**Sistema para recomendar productos y optimizar las ventas analizando el comportamiento del cliente.**

---

### 📝 ¿QUÉ HACE EL PROYECTO?
Analiza los datos de Olist para agrupar clientes según cuánto gastan y cuándo compran. Con esto, el sistema predice qué productos ofrecer a nuevos usuarios para asegurar que la recomendación sea exitosa.

---

### 🛠️ STACK TECNOLÓGICO
* **LENGUAJE:** `Python`
* **MACHINE LEARNING:**
    * `K-Prototypes` para clustering de datos mixtos.
    * `LightGBM` para la clasificación predictiva.
* **INGENIERÍA DE DATOS:** Uso de `Periodic Splines` para el tratamiento cíclico de variables temporales.

---

### ⚙️ PIPELINE DEL PROYECTO
1. **ANÁLISIS EXPLORATORIO (EDA):** Identificación de tendencias de ventas y patrones de comportamiento.
2. **INGENIERÍA DE CARACTERÍSTICAS:** Limpieza y creación de variables de tiempo (Splines).
3. **SEGMENTACIÓN:** Creación de grupos de clientes con K-Prototypes.
4. **PREDICCIÓN:** Modelo entrenado con LightGBM para identificar el clúster de un cliente nuevo.
5. **RECOMENDACIÓN:** Función final que entrega los productos ideales para cada tipo de cliente.

---

### 🚧 ESTADO DEL PROYECTO
> 
> En desarrollo.Faltan comentarios y mejorar el análisis pues he optado por hacer un proyecto funcional y a continuación finalizarlo.

---


