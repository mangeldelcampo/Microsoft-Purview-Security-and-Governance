# **Microsoft Purview: Gobernanza, Seguridad y Cumplimiento Unificado de Datos**

## **Guía Maestra para Presentación Corporativa (Slide-by-Slide Master Blueprint)**

### **Diapositiva 1: Portada Corporativa**

* **Título Principal:** Microsoft Purview: Seguridad, Gobernanza y Cumplimiento de Datos en la Era de la IA  
* **Subtítulo:** Estrategia integral para mitigar riesgos, automatizar la conformidad y habilitar la innovación de negocio  
* **Diseño Visual Sugerido:** Fondo profesional azul oscuro (Navy), con una abstracción gráfica que simule redes de nodos interconectados (datos) protegidos por un escudo de seguridad.  
* **Notas de Orador (Speaker Notes):**"Bienvenidos a la presentación sobre Microsoft Purview. En esta sesión analizaremos cómo el patrimonio de datos de nuestra organización, expuesto a una dispersión masiva y acelerado por la adopción de herramientas de Inteligencia Artificial, puede gestionarse mediante una plataforma única.1 Veremos cómo Purview unifica lo que tradicionalmente funcionaba en silos: la seguridad del dato, la gobernanza corporativa y el cumplimiento normativo legal.1 El objetivo de hoy es entender la arquitectura de esta solución, sus ventajas técnicas y cómo aplicarla en escenarios reales del mercado.3"


### **Diapositiva 2: El Desafío de los Datos Modernos**

* **Título de la Diapositiva:** La Crisis de Visibilidad en el Patrimonio de Datos  
* **Diseño Visual Sugerido:** Gráfico conceptual que compare un "Entorno Silado Tradicional" (con bases de datos locales, nubes públicas, carpetas en red y aplicaciones SaaS aisladas) frente a un "Entorno Centralizado". Iconos de advertencia en las áreas con mayor riesgo de fuga.  
* **Contenido Clave:**  
  * **Ecosistema Multinube Fragmentado:** Los datos residen en nubes públicas, sistemas locales, plataformas analíticas como Snowflake y herramientas SaaS.4  
  * **La Brecha de Visibilidad:** Es imposible proteger aquello que no se sabe que existe.1 Las organizaciones desconocen dónde se almacenan sus datos confidenciales.1  
  * **El Acelerador de la IA Generativa:** La proliferación de herramientas de IA incrementa exponencialmente el riesgo de sobrecompartición y fugas de propiedad intelectual.1  
* **Notas de Orador (Speaker Notes):**"El crecimiento exponencial de la información ha creado un panorama fragmentado.1 La TI híbrida y multinube ha diluido las fronteras tradicionales de la red de la empresa.4 Además, los equipos de trabajo están utilizando de forma autónoma modelos de IA generativa pública, lo que expone datos corporativos a la fuga de patentes o información privada de clientes.5 El problema crítico de hoy no es solo recopilar datos, sino saber exactamente qué datos tenemos, dónde residen y quién accede a ellos.1"


### **Diapositiva 3: La Propuesta de Microsoft Purview**

* **Título de la Diapositiva:** Microsoft Purview: Tres Pilares en una Plataforma Única  
* **Diseño Visual Sugerido:** Un diagrama de tres columnas verticales unificadas bajo un mismo techo que representa la "Plataforma Purview Portal".  
* **Contenido Clave:**  
  * **Gobernanza de Datos (Data Governance):** Habilita el descubrimiento y el entendimiento del contexto comercial e histórico de los datos.6  
  * **Seguridad de Datos (Data Security):** Protege los datos confidenciales de forma activa en tránsito, en reposo y en uso.  
  * **Cumplimiento de Datos (Data Compliance):** Automatiza el cumplimiento de regulaciones internacionales y minimiza riesgos legales.  
* **Notas de Orador (Speaker Notes):**"Microsoft Purview consolida bajo una misma interfaz de administración (el Portal unificado de Purview) tres áreas operativas críticas. Anteriormente, los equipos de TI utilizaban una herramienta de catálogo para gobernanza, otra suite para prevención de fugas de datos (DLP) y consultorías externas para auditorías de cumplimiento. Purview integra estas tres disciplinas sobre una base de datos común de metadatos, garantizando que una clasificación de seguridad afecte inmediatamente a las políticas de acceso y a los reportes de cumplimiento normativo.7"


### **Diapositiva 4: Pilar 1 \- Gobernanza Técnica y de Negocio**

* **Título de la Diapositiva:** Arquitectura del Gobierno de Datos: Data Map vs. Unified Catalog  
* **Diseño Visual Sugerido:** Diagrama en capas. En la base se ubica el **Data Map** (conectado a bases de datos, nubes y APIs).8 En la parte superior se sitúa el **Unified Catalog** mostrando conceptos como Glosarios y "Productos de Datos".  
* **Contenido Clave:**  
  * **Data Map (La Capa Física):** Escanea de forma automática los activos de datos corporativos, extrayendo metadatos técnicos y mapeando el linaje de datos sin copiar el contenido real.8  
  * **Unified Catalog (La Capa de Negocio):** Traduce los activos físicos en "Productos de Datos" comprensibles y accesibles para los usuarios empresariales bajo demanda.  
  * **Linaje de Datos (Data Lineage):** Mapeo de extremo a extremo que muestra visualmente de dónde proviene un dato, cómo se ha transformado y dónde se consume.8  
* **Notas de Orador (Speaker Notes):**"El corazón tecnológico de la gobernanza en Purview reside en la separación de dos capas críticas.8 Por un lado, el Data Map es un motor que actúa a nivel de infraestructura, conectando mediante APIs o redes privadas a nuestros orígenes de datos locales o multinube para recopilar metadatos.8 No duplica nuestros archivos; solo lee esquemas, nombres de columnas e información de linaje.8 Por encima de esto, el Unified Catalog expone esta información técnica en un lenguaje comercial.8 El usuario de finanzas no necesita saber en qué base de datos física reside una columna; solo busca el Producto de Datos de 'Ventas Globales' a través de un buscador de autoservicio guiado por permisos de acceso seguros."


### **Diapositiva 5: Zoom Técnico \- Elasticidad y Cálculo de Capacidad (CUs)**

* **Título de la Diapositiva:** Rendimiento y Costes del Data Map  
* **Diseño Visual Sugerido:** Gráfica lineal que muestre un pico de demanda en operaciones por segundo y almacenamiento de metadatos, correlacionando el escalado elástico con el consumo de unidades de capacidad (CUs).9 Incluir de forma destacada la fórmula matemática de asignación.  
* **Contenido Clave:**  
  * **Escalado Dinámico:** El Data Map se factura mediante un modelo de pago por uso medido en Capacity Units (CU).  
  * **Fórmula de Asignación por Hora:**  
    ![][image1]  
    Donde ![][image2] es el rendimiento de operaciones por segundo máximo alcanzado en la hora y ![][image3] es el volumen de metadatos almacenado expresado en gigabytes (GB).9  
  * **Capacidad de una CU Base:** Cada CU provee un rendimiento de hasta ![][image4] y un límite de almacenamiento de metadatos de ![][image5].9  
* **Notas de Orador (Speaker Notes):**"El coste del Data Map es altamente predecible y elástico.9 El sistema inicia por defecto con 1 Unidad de Capacidad (CU).9 Si durante procesos de escaneo intensivo o consultas recurrentes del catálogo superamos las 25 operaciones por segundo o acumulamos más de 10 GB de metadatos, Purview escalará elásticamente en incrementos exactos.9 Como vemos en la fórmula, la facturación por hora se determina por el valor limitante más alto entre el volumen de transacciones de metadatos o la capacidad física de almacenamiento que ocupan dichos metadatos.9"


### **Diapositiva 6: Pilar 2 \- Seguridad de Datos (Data Security)**

* **Título de la Diapositiva:** Seguridad Inteligente: Information Protection y DSPM  
* **Diseño Visual Sugerido:** Icono de un candado digital inteligente del cual fluyen tres engranajes funcionales: 1\. Identificación, 2\. Cifrado persistente, y 3\. Control de acceso en destino.  
* **Contenido Clave:**  
  * **Sensitivity Labels (Etiquetas de Sensibilidad):** Clasificación jerárquica de la información (p. ej., Público, Confidencial) aplicada automáticamente o sugerida a los usuarios.4  
  * **Cifrado Persistente:** El cifrado de seguridad se inyecta directamente dentro de los metadatos del archivo. La protección viaja con el documento incluso si se comparte fuera de los repositorios corporativos.4  
  * **Data Security Posture Management (DSPM):** Centraliza la visibilidad de los riesgos y evalúa continuamente la exposición de información sensible en entornos tradicionales e híbridos de IA.  
* **Notas de Orador (Speaker Notes):**"En el área de seguridad de datos, Purview ofrece un cambio de paradigma paradigmático: la protección que viaja con el dato.4 Tradicionalmente, la seguridad dependía de carpetas compartidas con permisos específicos; si alguien descargaba el archivo y lo enviaba por correo, la seguridad se rompía. Con Purview Information Protection, el archivo en sí es cifrado a nivel criptográfico.4 Aunque un empleado lo extraiga de SharePoint y lo guarde en un disco externo, el documento exigirá autenticación contra Microsoft Entra ID antes de poder abrirse o editarse, respetando las políticas originales de la organización.7"


### **Diapositiva 7: Protección de Datos frente a la IA Generativa**

* **Título de la Diapositiva:** Mitigación de Riesgos en la Era de Copilot e IA de Terceros  
* **Diseño Visual Sugerido:** Ilustración que muestre a un usuario interactuando con herramientas de IA. Un semáforo verde permite el flujo seguro hacia aplicaciones corporativas autorizadas, mientras que un semáforo rojo bloquea el copiado de información sensible en portales públicos.  
* **Contenido Clave:**  
  * **Control de Fugas de Información en IA:** Purview evita de forma proactiva que información clasificada como confidencial sea copiada o expuesta en motores de IA generativa públicos de terceros (como ChatGPT web).  
  * **Gobernanza de Datos para Copilot:** Garantiza que los modelos de IA corporativos (como Microsoft 365 Copilot) solo tengan acceso a datos que el usuario solicitante tiene autorización explícita para ver, evitando la sobrecompartición accidental.  
  * **Clasificadores Inteligentes Entrenables:** El motor de IA de Purview aprende de manera autónoma los patrones específicos de contratos, patentes o códigos de la organización.7  
* **Notas de Orador (Speaker Notes):***"Uno de los mayores temores de los directores de seguridad de la información (CISOs) hoy en día es que los empleados peguen código fuente propietario, planes financieros o información de clientes en herramientas de IA externas para resumir o traducir textos. Con Purview, podemos configurar políticas de Endpoint DLP (Prevención de pérdida de datos en el dispositivo final). Si un usuario intenta copiar texto de un documento confidencial y pegarlo en ChatGPT, el sistema bloquea la acción al instante y emite una alerta de riesgo al centro de seguridad."*


### **Diapositiva 8: Pilar 3 \- Cumplimiento y Gestión del Riesgo**

* **Título de la Diapositiva:** Minimización de Riesgos Regulatorios y Compliance Manager  
* **Diseño Visual Sugerido:** Panel visual que imite un velocímetro o indicador de "Puntuación de Cumplimiento" (Compliance Score) frente a múltiples estándares regulatorios internacionales.  
* **Contenido Clave:**  
  * **Compliance Manager:** Evaluación continua del estado tecnológico frente a más de 350 normativas, como GDPR, ISO 27001, NIS2, HIPAA y la nueva EU AI Act.4  
  * **Insider Risk Management (Riesgos Internos):** Análisis inteligente de comportamientos internos inusuales (descargas masivas de archivos, accesos fuera de horarios o intentos de saltar controles de acceso).4  
  * **eDiscovery y Retención Automatizada:** Herramientas automatizadas para congelar datos con fines de investigación legal y gestionar retenciones obligatorias de registros corporativos.7  
* **Notas de Orador (Speaker Notes):**"El cumplimiento regulatorio ya no es un proyecto estático de auditoría anual; es una operación continua.4 Purview Compliance Manager nos proporciona plantillas preconfiguradas que mapean los requisitos legales en acciones de control técnico automatizadas.4 El sistema analiza de manera dinámica nuestra configuración y nos dice exactamente qué hacer para mantener el cumplimiento.2 Asimismo, Purview Insider Risk analiza comportamientos sospechosos a nivel interno de la red, permitiéndonos identificar riesgos antes de que se materialice un incidente grave o fuga maliciosa.4"


### **Diapositiva 9: El Caso de Negocio: Retorno de Inversión (ROI)**

* **Título de la Diapositiva:** Retorno de Inversión y Eficiencia de Microsoft Purview  
* **Diseño Visual Sugerido:** Gráfico de barras horizontales destacando las reducciones porcentuales de tiempo y riesgos obtenidas en el mercado real según informes independientes.2  
* **Contenido Clave (Métricas de Impacto de Forrester Consulting):**  
  * **Disminución de Brechas de Seguridad:** Reducción del **30%** en la probabilidad de sufrir incidentes de seguridad y fugas de datos.2  
  * **Ahorro de Tiempo en SecOps:** Reducción del **75%** en el tiempo de investigación de incidentes forenses y riesgos.2  
  * **Aumento de Productividad:** Los equipos de cumplimiento reducen en un **60%** el esfuerzo manual para auditar y gestionar el ciclo de vida de los datos.2  
  * **Eliminación de Costes de Licencias de Terceros:** Ahorros estimados de hasta **$500,000 en tres años** por consolidación de herramientas redundantes de TI.2  
* **Notas de Orador (Speaker Notes):**"Para justificar la inversión en Microsoft Purview ante la mesa directiva, disponemos de los resultados del estudio de Forrester de Impacto Económico Total.2 No estamos hablando únicamente de mayor seguridad teórica, sino de ahorros tangibles de costes.2 Un equipo de seguridad suele perder horas rastreando de dónde provino un archivo filtrado; Purview reduce ese tiempo de investigación en un 75% gracias al linaje integrado y los logs de auditoría centralizados.2 Además, evitamos la necesidad de comprar tres o cuatro licencias de software independientes de otros proveedores, simplificando drásticamente el coste total de propiedad.2"


### **Diapositiva 10: Caso de Uso Real 1 \- Firma de Servicios Profesionales**

* **Título de la Diapositiva:** Caso de Éxito: Blindaje de Propiedad Intelectual en Servicios Profesionales  
* **Diseño Visual Sugerido:** Estructura tipo ficha técnica de caso: Desafío, Solución e Impacto. Foto corporativa de oficina y flujo de datos.  
* **Detalles del Caso:**  
  * **Perfil del Cliente:** Firma de servicios profesionales de tamaño mediano (85 empleados) que gestiona documentación de clientes altamente sensible.5  
  * **Desafío:** Archivos confidenciales dispersos sin categorizar en SharePoint, OneDrive y bandejas de correo electrónico. Temor corporativo al uso de herramientas públicas de IA generativa por parte de consultores.5  
  * **Solución Purview Aplicada:** Despliegue estructurado de Purview Information Protection con una política jerárquica de etiquetas en cuatro niveles (Público, Interno, Confidencial y Altamente Confidencial).5 Restricciones estrictas para impedir compartir datos en portales de IA de terceros.  
  * **Resultados:** Clasificación automática de la información, protección continua de la propiedad intelectual de los clientes y un canal controlado y seguro para el uso seguro de tecnologías corporativas.  
* **Notas de Orador (Speaker Notes):**"Este primer caso real muestra la escalabilidad de Purview.5 En una organización de tamaño mediano, el descontrol documental puede ser crítico.5 Al implementar etiquetas estructuradas de sensibilidad, los propios empleados pasaron a ser custodios activos de la información, guiados por avisos automáticos en Word, Excel y PowerPoint.2 Además, se detuvo por completo el riesgo de que el personal cargara accidentalmente borradores confidenciales de contratos en motores web públicos de inteligencia artificial, evitando incumplimientos por revelación de secretos comerciales."


### **Diapositiva 11: Caso de Uso Real 2 \- Operador de Infraestructura Crítica**

* **Título de la Diapositiva:** Caso de Éxito: Seguridad en un Gran Grupo Portuario  
* **Diseño Visual Sugerido:** Ilustración de un muelle de contenedores marítimos o transporte de mercancías a gran escala con un candado digital sobrevolando el mapa de puertos.  
* **Detalles del Caso:**  
  * **Perfil del Cliente:** Uno de los operadores portuarios más grandes del Reino Unido, responsable de la gestión de decenas de millones de toneladas de carga.10  
  * **Desafío:** Necesidad de garantizar la confidencialidad de la información operativa de la cadena de suministro global y el cumplimiento estricto con las regulaciones de infraestructura nacional crítica sin mermar la agilidad de los flujos de trabajo diarios.10  
  * **Solución Purview Aplicada:** Configuración e implementación de una directiva de etiquetado automático persistente y por defecto sobre Exchange, Teams, OneDrive y sitios de SharePoint.10 Bloqueo preventivo de compartición externa en cuentas críticas y automatización del etiquetado de datos estructurados en reposo.10  
  * **Resultados:** Minimización total del riesgo operacional de fuga accidental en comunicaciones críticas, logrando un cumplimiento normativo transparente que no interfiere en las complejas tareas de logística portuaria diarias.10  
* **Notas de Orador (Speaker Notes):**"En sectores industriales o de infraestructuras críticas, los empleados no pueden lidiar con sistemas lentos que detengan sus operaciones en tiempo real.10 Este caso de éxito con un gran operador portuario demuestra cómo Purview trabaja de forma invisible en segundo plano.10 Mediante políticas de etiquetado por defecto automáticas e inmutabilidad temporal de datos en reposo, el operador portuario pudo blindar la información de su cadena de transporte e impedir el reenvío externo de correos o archivos con datos protegidos sin añadir fricción operativa a los operarios portuarios.10"


### **Diapositiva 12: Caso de Uso Real 3 \- Sector Salud y Farmacéutico**

* **Título de la Diapositiva:** Caso de Éxito: Confidencialidad y Cumplimiento de Datos Médicos  
* **Diseño Visual Sugerido:** Icono de un hospital o expediente médico con el sello de "Datos Protegidos \- GDPR Artículo 9 y HIPAA".4  
* **Detalles del Caso:**  
  * **Perfil del Cliente:** Red de hospitales y laboratorios clínicos que manejan datos biométricos, genéticos e historiales de salud altamente regulados.5  
  * **Desafío:** Garantizar la confidencialidad absoluta del paciente para cumplir con el Artículo 9 del GDPR y HIPAA, evitando filtraciones masivas de datos de salud, pero permitiendo que el personal médico acceda a la información necesaria para decisiones clínicas.5  
  * **Solución Purview Aplicada:** Clasificadores preentrenados específicos para el sector salud en el Data Map.7 Implementación de directivas estrictas de retención de registros de salud y auditoría completa de los flujos de acceso de los facultativos médicos.7  
  * **Resultados:** Protección activa de los datos sensibles de salud contra fugas o exfiltración externa de información personal sensible, y facilidad absoluta de cara a la presentación de pruebas documentales para auditorías.4  
* **Notas de Orador (Speaker Notes):**"Los datos médicos son la información más sensible que puede albergar una corporación.5 Bajo el Artículo 9 del GDPR, las multas por descuidos de datos de salud son devastadoras.5 Purview incluye clasificadores de datos médicos entrenados para reconocer de forma nativa recetas, números de la seguridad social e informes clínicos.7 El sistema identifica estos datos confidenciales allí donde residan y bloquea de manera inmediata cualquier intento de compartirlos por canales inseguros, asegurando que los médicos colaboren a través de entornos cifrados oficiales.4"


### **Diapositiva 13: Caso de Uso Real 4 \- Sector Industrial y Manufactura**

* **Título de la Diapositiva:** Caso de Éxito: Protección de Propiedad Intelectual y Linaje de Datos  
* **Diseño Visual Sugerido:** Ilustración de una línea de ensamblaje industrial moderna que se integra con una red de servidores locales y en la nube de Microsoft Fabric.6  
* **Detalles del Caso:**  
  * **Perfil del Cliente:** Empresa multinacional de manufactura avanzada con un ecosistema complejo de patentes, diseños y planos de producción distribuidos globalmente.6  
  * **Desafío:** Riesgo de pérdida o robo de propiedad intelectual (planos de ingeniería CAD, recetas de producción) y falta de visibilidad sobre la calidad y el linaje de los datos analíticos integrados para tomar decisiones comerciales estratégicas.6  
  * **Solución Purview Aplicada:** Integración nativa del catálogo con Microsoft Fabric, bases de datos locales y nubes públicas para extraer metadatos analíticos unificados.6 Monitoreo de linaje de datos de extremo a extremo para garantizar la precisión de los dashboards analíticos corporativos.6  
  * **Resultados:** Protección proactiva de la propiedad intelectual industrial ante accesos no autorizados y garantía de consistencia, origen y calidad en la información analítica de la cadena de producción global.4  
* **Notas de Orador (Speaker Notes):**"En manufactura avanzada, el valor del negocio reside en los planos de ingeniería y las patentes de productos.11 Con Microsoft Purview, podemos proteger archivos CAD o diseños de manera activa.6 Además, gracias al linaje completo proporcionado por el Data Map, los directores de planta y de finanzas que miran un panel de Power BI en Microsoft Fabric tienen la total certeza y trazabilidad de que los datos de producción provienen de sensores y bases de datos previamente validadas y con altos estándares de calidad de datos.6"


### **Diapositiva 14: Recomendaciones de Implementación y Hoja de Ruta**

* **Título de la Diapositiva:** Buenas Prácticas Técnicas para el Éxito del Proyecto  
* **Diseño Visual Sugerido:** Línea de tiempo o diagrama de flujo con cuatro hitos clave para la implementación de gobernanza.  
* **Contenido Clave:**  
  * **Estructurar Permisos mediante Colecciones:** Delegar responsabilidades organizativas de forma jerárquica a través de Colecciones en lugar de asociar accesos de escaneo a grupos de usuarios de Entra ID.7  
  * **Despliegues en Redes Privadas (Private Endpoints):** Utilizar enlaces de conexión privados para el rastreo y escaneo seguro de orígenes de datos altamente regulados.7  
  * **Gestión de Límites Técnicos (eDiscovery):** Segmentar de forma proactiva las exportaciones legales por periodos de tiempo o custodios para mitigar el límite de rendimiento de 2 TB diarios por inquilino.7  
  * **Control de Costes de Capacidad:** Monitorear de forma activa el uso y escalabilidad de las CUs en el portal de Azure para ajustar los procesos de escaneo recurrentes.7  
* **Notas de Orador (Speaker Notes):**"Para implementar Microsoft Purview con éxito y optimizar los recursos tecnológicos del proyecto, debemos seguir estas directrices técnicas clave de arquitectura.7 En primer lugar, la gobernanza segura debe delegarse mediante la jerarquía nativa de Colecciones en el Data Map, lo cual garantiza una administración limpia basada en roles RBAC sin sobreexponer credenciales.7 Segundo, si trabajamos en entornos regulados, debemos utilizar Private Endpoints para que el tráfico de metadatos no viaje a través de redes públicas.7 Por último, si nuestro departamento legal requiere realizar procesos masivos de eDiscovery forense, debemos estructurar las búsquedas de forma fraccionada debido a las limitaciones estándar de exportación por inquilino de Microsoft.7"


### **Diapositiva 15: Conclusiones y Cierre**

* **Título de la Diapositiva:** El Futuro de la Gobernanza con Microsoft Purview  
* **Diseño Visual Sugerido:** Imagen inspiracional y futurista de un profesional utilizando análisis de datos seguro con Microsoft Copilot.  
* **Contenido Clave:**  
  * **Convergencia Tecnológica:** Centralizar la gobernanza, seguridad y cumplimiento evita vacíos normativos y optimiza costes operativos.2  
  * **Habilitador del Crecimiento en IA:** Purview no actúa como un freno operativo; es el habilitador necesario para adoptar la Inteligencia Artificial con confianza organizativa total.1  
  * **Llamado a la Acción:** Iniciar con un proyecto piloto escalable enfocado en un Dominio prioritario (p. ej., Finanzas) utilizando el modelo de autoscale dinámico del Data Map.9  
* **Notas de Orador (Speaker Notes):**"En resumen, Microsoft Purview transforma la seguridad y gobernanza de la información, convirtiendo los procesos restrictivos de seguridad en un motor de resiliencia y confianza.2 Nos da las garantías técnicas para adoptar la IA Generativa sin poner en peligro los secretos de la organización.1 Les invito a dar el primer paso: definir un caso piloto limitado a un dominio estratégico de datos y comenzar a descubrir hoy mismo el valor de un patrimonio de datos verdaderamente unificado y seguro. Muchas gracias."


#### **Obras citadas**

1. Aprenda acerca de Microsoft Purview | Microsoft Learn, fecha de acceso: junio 3, 2026, [https://learn.microsoft.com/es-es/purview/purview](https://learn.microsoft.com/es-es/purview/purview)  
2. Microsoft Purview delivered 30% reduction in data breach likelihood ..., fecha de acceso: junio 3, 2026, [https://www.microsoft.com/en-us/security/blog/2025/09/23/microsoft-purview-delivered-30-reduction-in-data-breach-likelihood/](https://www.microsoft.com/en-us/security/blog/2025/09/23/microsoft-purview-delivered-30-reduction-in-data-breach-likelihood/)  
3. Empowering Data Governance with Microsoft Purview | by Swetha Mudunuri | Medium, fecha de acceso: junio 3, 2026, [https://iamswetha7.medium.com/empowering-data-governance-with-microsoft-purview-39098d5b34e7](https://iamswetha7.medium.com/empowering-data-governance-with-microsoft-purview-39098d5b34e7)  
4. Microsoft Purview: Data Governance & Compliance \- collana IT, fecha de acceso: junio 3, 2026, [https://www.collana.com/en/microsoft-purview/](https://www.collana.com/en/microsoft-purview/)  
5. The Microsoft 365 Built-In Security Feature: Microsoft Purview | AAG IT Support, fecha de acceso: junio 3, 2026, [https://aag-it.com/the-microsoft-365-built-in-security-feature-microsoft-purview/](https://aag-it.com/the-microsoft-365-built-in-security-feature-microsoft-purview/)  
6. Microsoft Purview Data Map: Everything you need to know \- Plain Concepts, fecha de acceso: junio 3, 2026, [https://www.plainconcepts.com/data-map-purview/](https://www.plainconcepts.com/data-map-purview/)  
7. How Microsoft Purview Works: Architecture, Data Governance, and Best Practices \- Intradyn, fecha de acceso: junio 3, 2026, [https://www.intradyn.com/microsoft-purview-architecture-data-governance/](https://www.intradyn.com/microsoft-purview-architecture-data-governance/)  
8. How to Design Data Access with Microsoft Purview | by René Bremer \- Medium, fecha de acceso: junio 3, 2026, [https://medium.com/data-science-collective/designing-data-access-with-microsoft-purview-c4f920785ef5](https://medium.com/data-science-collective/designing-data-access-with-microsoft-purview-c4f920785ef5)  
9. Learn about Microsoft Purview Data Map, fecha de acceso: junio 3, 2026, [https://learn.microsoft.com/en-us/purview/data-map](https://learn.microsoft.com/en-us/purview/data-map)  
10. Major Port Group Secures Data with Microsoft Purview \- Bridewell, fecha de acceso: junio 3, 2026, [https://www.bridewell.com/insights/case-studies/detail/major-port-group-secures-data-with-microsoft-purview](https://www.bridewell.com/insights/case-studies/detail/major-port-group-secures-data-with-microsoft-purview)  
11. Purview 101: Microsoft's ultimate data governance platform \- Cloud Direct, fecha de acceso: junio 3, 2026, [https://clouddirect.net/learning-hub/purview-101-microsofts-ultimate-data-governance-platform/](https://clouddirect.net/learning-hub/purview-101-microsofts-ultimate-data-governance-platform/)

[image1]: <data:image/png;base64,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>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAaCAYAAAC+aNwHAAABKklEQVR4Xu2TsUoDQRRFn0QLQQuJEBRsJE2wShErsRCxs7PzB9KnskuTwiaFCEIaSz8hkEqw006QFApio6CoHyCo5zoZnJ3ZhNSaA4fA3Je3s7NvzP48RdzBPaxgIRvnM4WbeIld3B/Yw1us/ZamzOAh3ltaqKyD71iNsh9UcIJvuB5lHr3GKx6b22mGOn4OfoexgFd4g4thUMZH7GMpDCJ8gwdcCoMmfmErXMxhFZ8sajCH5+a2v+0Xh6BcdRc47xfVSR11ODqkURyZ22kzXPQNkveKWDE3By+4FgY6TZ3qqAb6ZAfmnt6IMpvGM/zAjSjzaC40QBokzUuCJksFp5YWbOEztnE2yjJodO/M3QE//7oL1+aaJJOXh26bvoRu3y4u25h/nPC/+QYcoDPSDoMsgwAAAABJRU5ErkJggg==>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAaCAYAAACHD21cAAABG0lEQVR4Xu3TIUtDURjG8XeooEwUNmxahmVgUxDbkiytKDjQZhAMpo2hWEUEw5jBbLOY7DKMWzJYBEHBL7BgnPP/eO5113f3Ewwf+MF433POPfecO7OxyCxK2MR8VMtjIR7gM4VTvOIIh+jiEo8oDocOM4lr3CKbqOtJHbQt7GQkG3jHim+QE7R8Mc4ZPrDoG6SOii/GucEAx5hwvWXkXO03VQsTpY8H7GMuOSgtOtFzC5PiBeTJ0rc/Em1Tx36BnoXJB39GRNFAvUPGN0gZX2j4hlLAlYV79FnFJ3Z9Q9Ex32PaN8geXrDkG4ruT6uuu7q2r4PZcvWf6BO6Qw3P0W9dQRNv2LH0d7cZCysruo41bFv4Z6Rt/T9jlG+J/Ct4t2V5pAAAAABJRU5ErkJggg==>

[image4]: <data:image/png;base64,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>

[image5]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADgAAAAZCAYAAABkdu2NAAACqUlEQVR4Xu2WzYtPURjHnwlFRCiNIi+JJFFmY2xmIbIgRRJ/gBI7L8lmShZjOcuxkMWk7G2QJhbEQkkUSSSKYsOC8vL9OPeZOffec8/t96vZ3W99+v3uec4953zP233MOnXqlNB8MSIOi81iTlG+UKwr/s+a1oqj1cJIm8QVMSGOiQXlcFbLxFXxW0xZaOO6eCB2Fc/ni7orxEPxt8JH8bX4/1wcsZkJahSzeFLcs9A5naZ0SLwQ28UicUncEUviSg3aIF6Jlxb6i4Xx2xYG7QZdq8QHCxNCny5MXbDwDhMzL4rVRIcHxbCFxlIGV4vX4nhUtlQ8EaeispSYgPsWZh+jKW0RX6xucKV4Z3WDyPv/KXZWYkl5YymDGPshdkRlA2LS0p3HYgKY6fFqIBJtXbPeDPJMOW3vL4fSyhlkcFWDiLqfxPpKuSsexL5yqKYT1ptBdgO7gm3PVm5VziBlTQZT5S6MMwG5Oi5u16oJHxMXDoZ4Btp6Kh6LjdO1W9Rk0FchNcg2g5QTz9XJycfE+WQLc6H47cvKnRGLp2u3qMkg36e7lh5km8HcCg6I5TazKg5lxFBui66xcDO/F1srsaSaDKImI03lLl/9P2J3OfR/S561MHm/LJzTz+JiEUM5g4hzy3s3xNxKrKacwcuWNkJdPi25Q+63KG00icsl9R1sM8jtyXtTlo6XlDN4wEISEK8Cs3yrwGc8JbYcl0HuO9ivwVHrYwX5tvkZcPkgR6MyBsvq5VI7F8nEG0tnMmQhN603g4xvr/hm4QLaFsVqYlUYKCtEJ/BdPLPy4R0Sb8U5C4kyWcSYtaRJkQYtGPFclPQQHlnYxnC6qEsuSo7qZxN4j3H6WImR2+aOR8/iRt1jIbUjfetHrMSIhUniN7X1OnXq1KlTp9nWP9Kltl0dvz2YAAAAAElFTkSuQmCC>
