# CalidadA10
```mermaid
graph TD
    A[Inicio: Definir el problema/objetivo] --> B{¿Existen datos disponibles?};
    B -- Sí --> C[Recopilar datos relevantes];
    B -- No --> D[Diseñar un plan de recolección de datos];
    D --> C;
    C --> E[Limpiar y preparar los datos];
    E --> F[Seleccionar herramientas estadísticas adecuadas];
    F --> G[Aplicar técnicas estadísticas. Ejemplo: gráficos de control, pruebas de hipótesis];
    G --> H[Analizar los resultados estadísticos];
    H --> I{¿El proceso está bajo control estadístico?};
    I -- Sí --> J[Monitorear el proceso continuamente];
    I -- No --> K[Identificar y analizar las causas de variación];
    K --> L[Implementar acciones correctivas];
    L --> M[Verificar la efectividad de las acciones correctivas];
    M --> N{¿Se logró el control estadístico?};
    N -- Sí --> J;
    N -- No --> K;
    J --> O[Tomar decisiones basadas en los datos y análisis];
    O --> P[Documentar el proceso y las decisiones];
    P --> Q[Fin: Mejora continua del proceso];
