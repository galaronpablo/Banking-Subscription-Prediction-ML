# 🏦 Banking Marketing: Advanced Predictive Modeling


<img width="200" height="300" alt="RStudio-Logo-Flat" src="https://github.com/user-attachments/assets/d96d466f-29a3-41d8-97dc-3add906ac8b9" />


**Subject:** Supervised Learning II / Aprendizaje Supervisado II


**Tools:** R, Caret, GLMNet, Random Forest, GBM (Gradient Boosting)


**Focus:** Classification, Model Comparison, Hyperparameter Tuning

## 👥 Authors
Project developed by:
* **Pablo Galarón Mateo**
* **Hugo Alonso Bejarano**
* **Gonzalo Blanca Ortega**

---

This project aims to optimize a bank's direct marketing campaign. Using a dataset of over 45,000 observations, we built several **supervised learning models** to predict if a client will subscribe to a term deposit.

The challenge involved handling a highly imbalanced dataset and comparing the performance of linear models against complex ensemble algorithms.

### 🛠️ What we did
* **Data Engineering:** Performed class balancing (50/50 undersampling) and feature engineering to improve model stability.
* **Model Benchmarking:**
    * **GLM (Logistic Regression):** Baseline model with Lasso and Ridge regularization to prevent overfitting.
    * **Classification Trees:** Simple and interpretable decision models.
    * **Random Forest:** Reduced variance through bagging and decorrelated trees.
    * **Gradient Boosting (GBM):** Iterative optimization to minimize prediction errors.
* **Evaluation:** Used **AUC (Area Under the Curve)**, Sensitivity, and Specificity as primary metrics to determine the best model for business needs.

### 💡 Key Findings
* **The Winner:** **Random Forest** achieved the highest AUC (0.947), proving to be the most robust model for detecting potential customers.
* **Key Variables:** The *duration* of the call and the *month* of contact were the strongest predictors of success.
* **Trade-off:** While Boosting is highly accurate, Random Forest provided a better balance between precision and computational cost.

### 📂 Files in this repo
* `📄 TrabajoGrupal_Predicción_Clasificación_Grupo8.pdf`: Full technical report.
* `📊 Presentación_TrabajoGrupal_Predicción_Clasificación_Grupo8.pdf`: Summary slides.
* `📝 grupal.qmd`: Quarto document with the complete R code.
* `📂 data/`: Original datasets from the UCI Machine Learning Repository.

---

Este proyecto busca optimizar las campañas de marketing directo de un banco. Utilizando un dataset de más de 45.000 observaciones, construimos varios **modelos de aprendizaje supervisado** para predecir si un cliente contratará un depósito a plazo.

El reto principal fue gestionar un dataset muy desbalanceado y comparar el rendimiento de modelos lineales frente a algoritmos de ensamblado más complejos.

### 🛠️ Qué hicimos
* **Ingeniería de Datos:** Realizamos un balanceo de clases (submuestreo 50/50) y preprocesamiento para mejorar la estabilidad de los modelos.
* **Comparativa de Modelos:**
    * **GLM (Regresión Logística):** Modelo base con regularización Lasso y Ridge para evitar el sobreajuste.
    * **Árboles de Clasificación:** Modelos de decisión simples e interpretables.
    * **Random Forest:** Reducción de varianza mediante bagging y árboles descorrelacionados.
    * **Gradient Boosting (GBM):** Optimización iterativa para minimizar errores de predicción.
* **Evaluación:** Usamos el **AUC (Área bajo la curva ROC)**, la Sensibilidad y la Especificidad para determinar el mejor modelo para el negocio.

### 💡 Conclusiones Principales
* **El Ganador:** **Random Forest** obtuvo el mayor AUC (0.947), demostrando ser el modelo más robusto para detectar clientes potenciales.
* **Variables Clave:** La *duración* de la llamada y el *mes* de contacto resultaron ser los predictores más potentes del éxito.
* **Equilibrio:** Aunque Boosting es muy preciso, Random Forest ofreció un mejor equilibrio entre precisión y coste computacional.

### 📂 Archivos en este repo
* `📄 TrabajoGrupal_Predicción_Clasificación_Grupo8.pdf`: Informe técnico detallado.
* `📊 Presentación_TrabajoGrupal_Predicción_Clasificación_Grupo8.pdf`: Presentación resumen.
* `📝 grupal.qmd`: Código completo en Quarto con toda la lógica en R.
* `📂 data/`: Datasets originales.
