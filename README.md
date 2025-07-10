# Clasificación de clientes para el plan Ultra 📱✨

Este proyecto tiene como objetivo predecir si un cliente va a contratar el plan Ultra de Megaline, una empresa ficticia de telecomunicaciones. Se utilizan datos del comportamiento de los usuarios como llamadas, mensajes y uso de internet.

---

## 📊 Descripción general

Trabajé con un dataset llamado `users_behavior.csv` que incluye variables como:

- Número de llamadas
- Minutos hablados
- Mensajes enviados
- MB usados

La variable objetivo (`is_ultra`) indica si el cliente es usuario del plan Ultra (`1`) o no (`0`). El dataset está algo desbalanceado, con una proporción aproximada de 70% a 30%.

---

## ⚙️ Tecnologías usadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🧪 Modelos utilizados

Entrené dos modelos:

1. **Árbol de Decisión** (Decision Tree)
   - Quise probarlo aunque sé que no es ideal para datos desbalanceados.
   - Precisión obtenida: alrededor del 0.72

2. **Random Forest**
   - Mejor desempeño con datos desbalanceados.
   - Precisión: más de 0.75
   - F1-score ponderado fue bastante aceptable, así que considero que este modelo es sólido.

---

## 🧼 Proceso general

1. Exploración inicial de los datos
2. Limpieza básica y verificación de nulos
3. Visualización de la distribución del target
4. División entre variables (`X`) y target (`y`)
5. Split entre train y test con proporción 70/30
6. Entrenamiento y evaluación de los modelos

---

## 📌 Notas personales

Fue interesante ver cómo Random Forest puede manejar mejor los datos desbalanceados. También me ayudó a reforzar el concepto de métricas como el F1-score, más allá de solo mirar el accuracy. El proyecto no requirió limpieza pesada, lo cual ayudó a enfocarme más en el modelado.

---

## 👨‍💻 Autor

**Pablo Sebastián Morán**  
📧 psmoran01@gmail.com  
🔗 [GitHub](https://github.com/PSMORAN01)  
🔗 [LinkedIn](https://www.linkedin.com/in/tu-usuario) ← cámbialo si es necesario
