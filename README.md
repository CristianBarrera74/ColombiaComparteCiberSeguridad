HTTrack Security Lab
Descripción

Este laboratorio está enfocado en la clonación de sitios web y el análisis de exposición de información utilizando HTTrack.

El objetivo principal es generar una réplica local del sitio latinoamericacomparte.com para identificar recursos públicos, endpoints, dependencias externas y posibles datos sensibles visibles en el código fuente.

Objetivos
Clonar sitios web mediante HTTrack
Analizar recursos HTML, CSS y JavaScript
Identificar endpoints y dependencias externas
Evaluar exposición de información pública
Analizar llamadas HTTP y formularios web
Detectar posibles configuraciones inseguras
Documentar hallazgos y evidencias
Realizar reconocimiento pasivo (OSINT)
Herramientas Utilizadas
HTTrack Website Copier
Kali Linux
Python 3 HTTP Server
grep
Navegador Web
Técnicas OSINT
Sitio Analizado
https://latinoamericacomparte.com/
Elementos Analizados
Archivos HTML, CSS y JS
Formularios web
Endpoints externos
Dependencias CDN
APIs públicas
Llamadas fetch()
Claves visibles en formularios
Recursos multimedia
Vulnerabilidades Evaluadas
Information Disclosure
Endpoint Exposure
Header Misconfiguration
Public Resource Enumeration
Input Validation
Exposición de APIs públicas
Procedimiento Realizado
Verificación de instalación de HTTrack
Clonación del sitio objetivo
Análisis de estructura descargada
Levantamiento de servidor local con Python
Búsqueda de APIs y endpoints mediante grep
Identificación de dependencias externas
Documentación de hallazgos técnicos
Resultados Obtenidos
Identificación del endpoint:
https://api.web3forms.com/submit
Detección de llamadas fetch() en código JavaScript
Identificación de CDN externos y Google Fonts
Enumeración de dominios relacionados
Análisis de formularios de contacto
No se encontraron tokens sensibles expuestos
Identificación de pasarela de pago externa (Bold)
Resultados Esperados
Comprensión del uso de HTTrack en reconocimiento web
Identificación de recursos públicos y endpoints
Análisis de exposición de información
Documentación técnica de hallazgos
Fortalecimiento de habilidades en OSINT y Pentesting pasivo
