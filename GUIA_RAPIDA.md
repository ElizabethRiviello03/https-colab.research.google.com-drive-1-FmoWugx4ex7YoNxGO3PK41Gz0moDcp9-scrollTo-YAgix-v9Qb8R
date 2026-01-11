# Guía Rápida - Análisis de Vacunación Mundial

## 🎯 Objetivo
Analizar el progreso de vacunación contra COVID-19 a nivel mundial utilizando datos actualizados.

## 📖 Cómo usar este proyecto

### Para Google Colab (Recomendado)
1. Visita: https://colab.research.google.com/
2. Click en "Archivo" → "Abrir cuaderno"
3. Selecciona la pestaña "GitHub"
4. Pega la URL del repositorio
5. Selecciona `analisis_vacunacion_mundial.ipynb`
6. Ejecuta las celdas en orden (Shift + Enter)

### Para Jupyter Local
```bash
# Clonar repositorio
git clone [URL_DEL_REPO]
cd [NOMBRE_DEL_REPO]

# Instalar dependencias
pip install -r requirements.txt

# Iniciar Jupyter
jupyter notebook analisis_vacunacion_mundial.ipynb
```

## 📊 Contenido del Análisis

### Secciones Principales:
1. **Carga de Datos** - Obtiene datos actualizados de Our World in Data
2. **Exploración** - Estadísticas descriptivas y estructura
3. **Limpieza** - Preprocesamiento y validación de datos
4. **Análisis por País** - Rankings y comparaciones
5. **Análisis Temporal** - Evolución de la vacunación
6. **Visualizaciones** - Gráficos interactivos y mapas
7. **Análisis Regional** - Foco en América Latina
8. **Resumen Ejecutivo** - Conclusiones y hallazgos

### Visualizaciones Incluidas:
- 📊 Gráficos de barras (Top países)
- 📈 Gráficos de línea temporal
- 🌍 Mapas coropléticos mundiales
- 📉 Histogramas y box plots
- 🔥 Matrices de correlación
- 📊 Gráficos comparativos regionales

## 🔑 Características Clave

### 1. Datos en Tiempo Real
- Conexión directa con Our World in Data
- Actualización automática
- Datos de 200+ países

### 2. Análisis Completo
- Cobertura de vacunación per cápita
- Vacunación completa por país
- Velocidad de administración
- Comparaciones regionales

### 3. Visualizaciones Interactivas
- Gráficos con Plotly
- Mapas mundiales
- Gráficos estáticos con Matplotlib/Seaborn

### 4. Exportación de Resultados
- CSV con datos procesados
- Top 50 países
- Listo para análisis adicional

## 💡 Casos de Uso

1. **Investigación Académica**
   - Análisis de tendencias de vacunación
   - Estudios comparativos entre países
   - Investigación en salud pública

2. **Reportes y Presentaciones**
   - Visualizaciones para informes
   - Datos actualizados para presentaciones
   - Estadísticas para medios

3. **Aprendizaje de Data Science**
   - Ejemplo de análisis exploratorio
   - Técnicas de visualización
   - Manejo de datos temporales

4. **Monitoreo de Salud Pública**
   - Seguimiento del progreso de vacunación
   - Identificación de brechas
   - Análisis de políticas públicas

## 🛠️ Personalización

### Modificar Países de Análisis
En la sección "Análisis de Progreso Temporal", modifica:
```python
countries_of_interest = ['País1', 'País2', 'País3']
```

### Cambiar Período de Análisis
En la sección "Análisis por Velocidad de Vacunación", ajusta:
```python
date_30_days_ago = recent_date - pd.Timedelta(days=30)  # Cambiar días
```

### Agregar Nuevas Visualizaciones
Añade celdas de código con tus propios análisis usando:
- `matplotlib` para gráficos estáticos
- `plotly` para gráficos interactivos
- `seaborn` para análisis estadísticos

## 📝 Notas Importantes

### Requisitos de Sistema
- Python 3.7 o superior
- Conexión a internet (para obtener datos)
- 2GB RAM mínimo recomendado

### Tiempo de Ejecución
- Carga de datos: 10-30 segundos
- Análisis completo: 2-5 minutos
- Depende de la velocidad de conexión

### Solución de Problemas

**Error de conexión:**
- Verifica tu conexión a internet
- El notebook usará datos de ejemplo si no puede conectar

**Error en visualizaciones:**
- Asegúrate de instalar todas las dependencias
- Ejecuta: `pip install -r requirements.txt`

**Notebook no carga:**
- Verifica que el archivo .ipynb no esté corrupto
- Intenta abrirlo en Google Colab

## 📚 Recursos Adicionales

### Fuentes de Datos
- [Our World in Data - COVID-19 Vaccinations](https://github.com/owid/covid-19-data)
- Dataset actualizado diariamente
- Metodología transparente y documentada

### Documentación de Librerías
- [Pandas](https://pandas.pydata.org/docs/)
- [Matplotlib](https://matplotlib.org/stable/contents.html)
- [Plotly](https://plotly.com/python/)
- [Seaborn](https://seaborn.pydata.org/)

## 🤝 Contribuir

¿Quieres mejorar el análisis?
1. Haz fork del repositorio
2. Crea una rama para tu mejora
3. Añade tus cambios
4. Envía un pull request

## 📧 Soporte

Para preguntas o problemas:
- Abre un issue en GitHub
- Revisa la documentación
- Consulta los recursos adicionales

---

**Última actualización:** 2026  
**Versión:** 1.0  
**Licencia:** Uso educativo y de investigación
