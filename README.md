Actuá como arquitecto de software senior, analista de datos, financiero, contable, IT, productivo y logístico.

Quiero que desarrolles un sistema web profesional donde el usuario pueda subir cualquier archivo Excel, Word o PDF, y el sistema analice automáticamente el contenido, detecte el tipo de información y genere un tablero de análisis con indicadores, conclusiones y recomendaciones.

Objetivo del sistema:
Crear una plataforma inteligente de análisis documental y de datos que permita subir archivos y obtener automáticamente:
- Clasificación del archivo.
- Resumen ejecutivo.
- Indicadores clave.
- Tablero visual.
- Alertas y desvíos.
- Análisis profesional.
- Recomendaciones accionables.
- Exportación de reporte.

Tipos de archivos soportados:
- Excel: .xlsx, .xls, .csv.
- Word: .docx.
- PDF: texto, reportes, balances, facturas, informes, documentación técnica.

El sistema debe detectar automáticamente si el archivo corresponde a:
- Finanzas.
- Estado de resultados.
- Balance.
- Cashflow.
- Cobranzas.
- Pagos.
- Ventas.
- Compras.
- Inventario.
- Producción.
- Logística.
- Recursos humanos.
- IT / infraestructura.
- Contratos.
- Reportes técnicos.
- Documentación general.

Funcionalidad principal:
1. Pantalla para subir archivo.
2. Backend que procese el archivo.
3. Extracción de datos:
   - Tablas.
   - Texto.
   - Fechas.
   - Montos.
   - Clientes.
   - Proveedores.
   - Estados.
   - Categorías.
   - Métricas relevantes.
4. Clasificación automática del contenido.
5. Generación de KPIs según el tipo de archivo.
6. Detección de anomalías, desvíos, riesgos y oportunidades.
7. Generación de tablero dinámico.
8. Informe profesional con:
   - Resumen ejecutivo.
   - Hallazgos principales.
   - Indicadores.
   - Riesgos.
   - Recomendaciones.
   - Próximas acciones.
9. Exportación a PDF y Excel.

Módulos de análisis esperados:

Módulo financiero:
- Ventas totales.
- Costos.
- Margen bruto.
- Rentabilidad.
- EBITDA estimado si corresponde.
- Evolución mensual.
- Desvíos contra presupuesto.
- Clientes principales.
- Productos principales.
- Alertas de caída de margen.
- Recomendaciones financieras.

Módulo contable:
- Cuentas contables.
- Saldos.
- Movimientos.
- Conciliaciones.
- Diferencias.
- Cuentas con desvíos.
- Riesgos contables.
- Inconsistencias.

Módulo cobranzas / pagos:
- Total vencido.
- Total a vencer.
- Aging.
- Clientes morosos.
- Proveedores críticos.
- Concentración de deuda.
- Recomendaciones de gestión.

Módulo ventas:
- Ventas por cliente.
- Ventas por producto.
- Ticket promedio.
- Evolución.
- Ranking.
- Caídas relevantes.
- Oportunidades comerciales.

Módulo compras:
- Compras por proveedor.
- Variación de precios.
- Concentración.
- Proveedores críticos.
- Oportunidades de negociación.

Módulo inventario:
- Stock valorizado.
- Stock inmovilizado.
- Rotación.
- Quiebres.
- Sobrestock.
- Productos críticos.

Módulo producción:
- Producción por período.
- Eficiencia.
- Merma.
- Desvíos.
- Capacidad.
- Cuellos de botella.

Módulo logística:
- Entregas.
- Demoras.
- Costos logísticos.
- Rutas.
- Incumplimientos.
- Recomendaciones operativas.

Módulo IT:
- Infraestructura detectada.
- Servidores.
- Backups.
- Seguridad.
- Licencias.
- Riesgos.
- Obsolescencia.
- Recomendaciones técnicas.

Módulo contratos / legales:
- Partes involucradas.
- Fechas clave.
- Montos.
- Plazos.
- Obligaciones.
- Riesgos.
- Cláusulas relevantes.
- Alertas de vencimiento.

Requisitos técnicos:
- Frontend moderno y responsive.
- Backend robusto.
- Base de datos para guardar análisis.
- Sistema de usuarios.
- Historial de archivos analizados.
- Procesamiento seguro de documentos.
- Manejo de errores.
- Logs.
- Exportación de reportes.
- Código claro, modular y mantenible.

Stack sugerido:
- Frontend: React / Next.js.
- Backend: Node.js o Python FastAPI.
- Base de datos: PostgreSQL.
- Procesamiento Excel: pandas / openpyxl.
- Procesamiento PDF: pdfplumber / PyMuPDF.
- Procesamiento Word: python-docx.
- Gráficos: Recharts / Plotly.
- IA: integrar con API de modelo LLM configurable.

Diseño esperado:
- Dashboard profesional tipo BI.
- Cards de KPIs.
- Gráficos de evolución.
- Tablas dinámicas.
- Alertas con colores.
- Panel de recomendaciones.
- Vista de resumen ejecutivo.
- Vista técnica del análisis.
- Botón para descargar informe.

Reglas importantes:
- El sistema no debe asumir que todos los archivos tienen la misma estructura.
- Debe analizar encabezados, nombres de columnas, textos y valores.
- Debe inferir el tipo de documento.
- Debe indicar nivel de confianza de la clasificación.
- Debe avisar cuando la calidad del archivo sea baja.
- Debe separar datos detectados de conclusiones generadas.
- Debe permitir revisar el análisis antes de exportarlo.
- Debe generar recomendaciones profesionales, no genéricas.
- Debe estar preparado para archivos reales de empresas argentinas.

Quiero que primero analices el requerimiento y propongas:
1. Arquitectura del sistema.
2. Estructura de carpetas.
3. Modelo de base de datos.
4. Flujo completo de análisis.
5. Diseño de pantallas.
6. Componentes principales.
7. Endpoints del backend.
8. Librerías necesarias.
9. Prompt interno para la IA.
10. Plan de implementación por etapas.

Después de eso, generá el código inicial completo del proyecto, dejando una base funcional donde pueda:
- Subir un archivo.
- Procesarlo.
- Detectar el tipo.
- Mostrar resumen.
- Mostrar KPIs básicos.
- Mostrar tablero.
- Mostrar recomendaciones.
- Exportar reporte básico.
