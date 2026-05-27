# Simulación de Sistema Bancario M/M/1

Proyecto desarrollado en Google Colab utilizando Python para simular el comportamiento de un sistema bancario mediante teoría de colas M/M/1 y simulación de eventos discretos.

---

# Descripción

El objetivo del proyecto es analizar el desempeño de un sistema de atención bancaria compuesto por múltiples cajeros, evaluando métricas como:

- Tiempo promedio de espera
- Tiempo promedio de servicio
- Tiempo promedio en el sistema
- Cantidad de clientes atendidos
- Comparación entre diferentes escenarios de atención

La simulación utiliza distribuciones exponenciales para modelar:
- tiempos entre llegadas,
- tiempos de servicio,
- comportamiento estocástico del sistema.

---

# Objetivos

## Objetivo General

Analizar el comportamiento del sistema bancario mediante simulación de eventos discretos y teoría de colas M/M/1.

## Objetivos Específicos

- Simular 10 réplicas independientes del sistema.
- Identificar el cajero con menor y mayor tiempo promedio de atención.
- Calcular el promedio de usuarios por tipo.
- Analizar tiempos de espera y tiempos de servicio.
- Evaluar la necesidad de agregar un nuevo cajero.
- Comparar diferentes configuraciones de atención.

---

# Tecnologías Utilizadas

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib

---

# Escenarios Evaluados

Se analizaron los siguientes escenarios:

| Escenario | Cajeros |
|---|---|
| 3 Cajeros Mixtos | 3 |
| 2 Cajeros | 2 |
| 4 Cajeros | 4 |

---

# Resultados Obtenidos

| Escenario | Clientes Atendidos | Espera Promedio | Servicio Promedio | Sistema Promedio |
|---|---|---|---|---|
| 3 Cajeros Mixtos | 2018 | 0.43 | 3.17 | 3.60 |
| 2 Cajeros | 2018 | 2.85 | 3.17 | 6.02 |
| 4 Cajeros | 2018 | 0.08 | 3.17 | 3.26 |

---

# Conclusiones

- El escenario con 4 cajeros presentó el mejor desempeño del sistema.
- El escenario con 2 cajeros mostró mayor congestión y saturación.
- La configuración de 3 cajeros mixtos mantuvo tiempos de espera relativamente bajos.
- El número de cajeros influye directamente en el tiempo promedio de espera.
- La simulación permitió apoyar la toma de decisiones operativas del sistema bancario.

---

# Estructura del Proyecto

```bash
.
├── Laboratorio_Problema_Bancario.ipynb
├── resultados_banco.xlsx
└── README.md
```

---

# Ejecución

1. Abrir el notebook en Google Colab.
2. Ejecutar las celdas en orden.
3. Generar las simulaciones y gráficas.
4. Exportar resultados a Excel.

---

# Autor

Jorge Paniagua
