# 📊 Proyecto Churn de Clientes – Interconnect

👋 ¡Hola! Soy Víctor, Data Scientist Junior.  
Te presento un resumen del análisis y modelo de predicción de cancelaciones (churn) en Interconnect.
---

## 🔍 Introducción  
Analizamos más de 100 000 contratos (2013–2020) para identificar **qué factores** llevan a que un cliente cancele su servicio y construir un modelo que lo anticipe.

---

## 🎯 Objetivos  
- 📈 **Detectar patrones** de cancelación según:  
  - Tipo de contrato (mensual ↔ anual ↔ bienal)  
  - Servicio de Internet (DSL vs. Fibra)  
  - Método de pago  
  - Duración del contrato  
- ✅ **Validar** esas relaciones con pruebas estadísticas.  
- 🤖 **Desarrollar** un modelo ML con AUC-ROC > 0.80 para predecir churn.

---

## 📌 Hallazgos Clave  
1. **Contratos mensuales** son 2× más propensos a churn que los anuales/bianuales.  
2. **Fibra óptica** registra más cancelaciones que DSL.  
3. El pago con **“Electronic check”** se asocia a cancelaciones elevadas.  
4. **Clientes nuevos** (menor tiempo de contrato) muestran mayor riesgo de churn.

---

## 🚀 Conclusiones  
- 🛠️ Foco en clientes **mensuales** y de **fibra óptica** para planes de retención.  
- 🎯 Ofertas personalizadas a usuarios con “Electronic check” y contrataciones recientes.  
- 🤝 El modelo LightGBM logró un **AUC-ROC de 0.85**, validando la robustez de las variables seleccionadas.  
- 📈 Estrategias recomendadas: promociones dirigidas, seguimiento proactivo y mejoras en la experiencia de fibra.

---

💡 Toda la implementación y código están disponibles en este repositorio. ¡Gracias por tu interés!  
