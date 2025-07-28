1. Introducción
Empresa: Telecom X
Problema: Alta tasa de cancelación de clientes (churn)
Objetivo del proyecto: Identificar factores asociados a la cancelación para diseñar estrategias de retención y soporte para modelos predictivos.

2. Metodología
Importación de datos (API/CSV)
Limpieza y normalización de variables
Análisis Exploratorio de Datos (EDA)
Visualización de patrones y tendencias
Análisis de correlación
Generación de hallazgos y recomendaciones
3. Distribución de Cancelación
Activos: 71.2%
De Baja: 25.7%
Cancelación desconocida: 3.08%
NOTA: Una de cada cuatro personas se da de baja: foco de acción estratégica.

4. Análisis por Variables Personales
Variable	Mayor churn en...	Porcentaje
No Adulto Mayor	Menores de 65	40.3%
Pareja	Sin pareja	32%
Dependientes	Sin dependientes	30.3%
Factura	Electrónica	32.5%
Adulto Mayor: menor tasa de cancelación (22.9%) vs. no adultos mayores (40.3%).
Tiene Pareja: sin pareja tienen mayor churn (32%) que quienes sí tienen (19%).
Tiene Dependientes: sin dependientes → 30.3% de churn vs. 14.9% con dependientes.
Factura Electrónica: mayor churn (32.5%) que quienes reciben factura física (15.9%).
NOTA: Perfil de mayor riesgo: Jóvenes, solteros, sin dependientes y digitales.

5. Variables Categóricas relevantes
Género: no influye significativamente (cancelación similar).
Tipo de Internet: Fibra óptica con mayor cancelación (40.6%).
Tipo de contrato: mensual → 41.3% de churn. Contratos a 1 o 2 años
Mensual: 41.3% e churn.(alto riesgo)
1 año: 3%
2 años: 1.9%
Método de pago:
Electronic Check: 43.8% (alto riesgo)
6. Análisis de Variables Numéricas
Clientes que cancelan tienen:
Meses de contrato: clientes que cancelan lo hacen en los primeros meses.
Factura mensual: mediana más alta en clientes cancelados.
Cargos totales: menores en quienes cancelan temprano.
Cargos diarios: patrón similar a cargos totales.
Boxplots muestran patrones visuales claros entre activos y cancelados.

7. Correlación de Variables
Se exploró la correlación entre variables numéricas para detectar patrones que ayuden a construir modelos predictivos.

El heatmap mostró correlaciones relevantes:
Meses_Contrato y Cargos_Totales: alta correlación positiva.
Cantidad_Servicios tiene correlación negativa con churn.
Cuenta_Diaria se relaciona con otros indicadores de gasto.
Este análisis refuerza que mayor compromiso (más meses o más servicios) está asociado con menor riesgo de cancelación.

8. Conclusiones e Insights
Clientes con menos compromiso jóvenes, solteros, sin dependientes, y que reciben factura online muestran tasas de cancelación más altas.

El tipo de contrato es un fuerte predictor de churn. Contratos mensuales están más expuestos a cancelaciones.

Factura electrónica y método de pago electrónico se asocian a mayores cancelaciones.

Contratos largos retienen más clientes.

Las variables numéricas refuerzan la idea de que los clientes cancelan en las primeras etapas de su contrato.

9. Recomendaciones Estratégicas
Fomentar contratos a largo plazo (anuales/bianuales) con incentivos o beneficios exclusivos.
Crear campañas de retención personalizadas para clientes con perfil de riesgo alto.
Investigar la experiencia de pago por Electronic Check y optimizar el canal si es necesario.
Desarrollar modelos predictivos de cancelación con estas variables como insumo.
Explorar más relaciones entre servicios contratados y churn para estrategias de satisfaccion del cliente.
10. Conclusión
Este análisis permite entender mejor los factores asociados a la cancelación de clientes, y es una base sólida para:

Diseñar campañas de retención efectivas
Reducir el churn
Construir modelos de predicción para decisiones estratégicas
