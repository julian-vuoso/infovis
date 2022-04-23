# TP1 - Datos Personales
## Transformación de los datos crudos a procesados

1. Eliminación de nombre del día de la semana
2. Agregado de campos de Dormirse y Levantarse, transformando cada `Horario` a `Minutos transcurridos` (Ej. 02.30am -> 180) para facilitar la comprensión y construcción de algunos gráficos
3. Para algunas herramientas, conversión de `,` a `.` como separador decimal
4. Agregado de campo `Imagen` para el gráfico dinámico de Fluorish (además de alternar los ejes en ese caso)
5. Eliminación de campo `Despertadas` que indicaba las veces en que despertaba en cada noche, por desuso (se usó unicamente el tiempo despierto)
6. Agregado de campo `N° Día` para mejorar visualización con RawGraph
