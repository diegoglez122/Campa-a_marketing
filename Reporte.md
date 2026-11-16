REPORTE DE RESULTADOS: FASE 1 DE LANZAMIENTO

Proyecto: Sitio Web Triciclos Cuba
Período evaluado: Fase 1 (Atracción Digital y Lanzamiento)
Estatus: Completado con contingencias técnicas resueltas.

1. Resumen Ejecutivo

La Fase 1 del Plan de Marketing se ejecutó en su totalidad en los canales digitales. El video corto (Reel) y la difusión en comunidades de Facebook lograron un alto nivel de alcance y generación de interés, captando a cientos de usuarios del público objetivo.

Sin embargo, la fase de conversión (el paso del usuario desde las redes hacia el motor de búsqueda) se vio severamente afectada por contingencias técnicas externas: la caída del servidor de hosting por límite de horas y los bloqueos de red locales a herramientas de medición (Google Analytics). Estos percances fueron identificados y solucionados (migración de servidor e implementación de nueva analítica), dejando la infraestructura lista para escalar las conversiones en la Fase 2.

2. Evaluación de los Objetivos Estratégicos

· Objetivo Principal (Atraer tráfico cualificado): ✅ Cumplido. Se alcanzó a casi 1,000 personas únicas en Instagram (80% público nuevo) y se difundió el proyecto en grupos estratégicos de Facebook.
· Objetivo de Conversión (Interacción con el motor): ⚠️ Afectado y corregido. La caída del servidor impidió medir el impacto inicial del tráfico que sí llegó desde las redes. Tras la migración, el nuevo sistema ya registra interacciones reales en el motor de búsqueda.
· Objetivo de Alcance: 🟡 Parcial. Los canales digitales se activaron con éxito. El canal físico (Guerrilla/QR) fue pausado estratégicamente para no enviar usuarios a una web caída.

3. Análisis de Resultados por Canal

Canal 1: Redes Sociales (Reel / Short)

· Alcance: 1,370 visualizaciones y 998 espectadores únicos.
· Atracción: El 80.4% de las vistas provino de no seguidores. El gancho inicial y el algoritmo funcionaron a la perfección.
· Interacción: 25 comentarios, 46 "Me gusta", 3 guardados. El Call To Action (CTA) de comentar "triciclo" demostró un interés real y una alta tasa de conversación.
· Retención: Tiempo promedio de 16 segundos (el video dura 1:07).
· Público: El 85.6% tiene entre 18 y 34 años, validando que el mensaje llega al segmento de emprendedores y compradores.

Canal 2: Comunidades en Línea (Grupos de Facebook)

· Ejecución: Se realizaron las publicaciones planificadas aportando datos de valor (precios de Revolico vs. Importadoras, fallas comunes, rentabilidad).
· Resultado: La estrategia generó discusión y tráfico hacia el enlace del recomendador interactivo.
· Impacto del percance: Los usuarios que hicieron clic desde Facebook se encontraron con la web fuera de línea temporalmente (debido al límite de Render). Esto cortó el embudo de conversión justo en el momento de mayor interés.
· Acción: Se mantendrán las publicaciones activas y se responderán los comentarios pendientes compartiendo el nuevo enlace estable.

Canal 3: Guerrilla Marketing (QR en Calles)

· Estatus: Pospuesto.
· Razón: Por estrategia y experiencia de usuario, se decidió no desplegar los QRs en las calles (piqueras y talleres) hasta estabilizar la web. Enviar tráfico físico a un servidor caído habría dañado la reputación del proyecto.

4. Registro de Contingencias Técnicas (Los Percances)

Esta sección documenta los fallos imprevistos que afectaron la conversión, demostrando la capacidad de resolución técnica del equipo:

1. Colapso del Hosting (Límite de Render): La plataforma web experimentó una caída al superar el límite de horas del plan gratuito de Render durante el pico de tráfico generado por el Reel y los grupos de Facebook.
   · Solución: Se redesplegó la aplicación en una nueva instancia de Render de inmediato. La web está nuevamente en línea.
2. Bloqueo Geográfico de Google Analytics (GA4): Se confirmó que las restricciones de red en Cuba bloquean los servidores de Google, impidiendo registrar las visitas reales (el panel mostraba 0).
   · Solución: Se eliminó el código de GA4 y se implementó streamlit-analytics2 (código abierto, del lado del servidor), que no sufre bloqueos en Cuba. Esta herramienta ya está operativa y registrando las primeras visitas y el uso de los filtros del buscador.

5. Conclusiones y Lecciones Aprendidas

· El contenido y los datos generan interés: Tanto en Instagram como en Facebook, el tema de la rentabilidad y los precios de los triciclos captó la atención del público. El marketing de atracción funcionó.
· La infraestructura es el cuello de botella: Un buen plan de marketing genera tráfico, pero se necesita un alojamiento robusto (y medidores locales) para retenerlo y medirlo en el contexto de conectividad de Cuba.
· La comunidad está activa: Los 25 comentarios en Instagram y la respuesta en Facebook son usuarios "calientes" esperando la herramienta.

6. Plan de Acción Inmediato (Fase 2)

1. Capitalizar el interés: Responder los comentarios en Facebook e Instagram, entregando el enlace actualizado y funcional de la web (disculpando el fallo técnico).
2. Medir la conversión real: Monitorear el panel de streamlit-analytics2 para ver cuántos de los que llegan desde redes completan el flujo del motor de búsqueda.
3. Desplegar la Guerrilla: Una vez confirmada la estabilidad, proceder con la impresión y pegado de los QRs en las calles.
