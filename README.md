# Validador de Etiquetas Hreflang y SEO Internacional

[![Validador Hreflang](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/mx/validador-etiquetas-hreflang/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Auditoria de reciprocidad de enlaces alternativos, segmentacion regional de idioma ISO, y arquitectura de fallback x-default.

Desarrollado y mantenido por la division de ingenieria de busqueda internacional e infraestructura web de **TAVARDT**.

***

## Vectores de Riesgo e Impacto Operativo en SEO Internacional

Los errores de etiquetado hreflang provocan canibalizacion organica y desindexacion involuntaria de audiencias internacionales. Cuando los enlaces alternativos carecen de confirmacion reciproca, los motores de busqueda descartan la orientacion geografica.

Esta falla expone a las plataformas mexicanas a trafico mal redirigido y perdida de visibilidad regional en las paginas de resultados. El diagnostico continuo garantiza que los usuarios de cada pais alcancen la variante local adecuada.

***

## Capacidades Centrales de Auditoria Tecnica

* **Verificacion de Enlace Autorreferencial**: Auditoria automatica para asegurar que la URL actual este declarada en el conjunto de enlaces alternativos.
* **Inspeccion de Fallback x-default**: Comprobacion de enrutamiento predeterminado para usuarios fuera de las areas geograficas segmentadas.
* **Validacion de Estandares ISO 639-1 e ISO 3166-1**: Verificacion estricta de combinaciones de idioma y pais para prevenir errores de indexacion regional.
* **Deteccion de Conflictos con Etiqueta Canonica**: Alerta temprana ante discordancias criticas entre el enlace canonical y las anotaciones de idioma.
* **Extraccion en Doble Formato**: Captura directa de directivas en elementos HTML `<head>` y encabezados de respuesta HTTP Link.
* **Puntuacion de Desempeno Internacional**: Metrica tecnica de 0 a 100 categorizada en COMPLIANT, WARNING o CRITICAL con recomendaciones claras.

***

## Instalacion y Ejecucion

Requiere Python 3.8 o superior sin librerias adicionales.

```bash
git clone https://github.com/TAVARDT-Mexico/hreflang-validator-mx.git
cd hreflang-validator-mx
python hreflang_validator.py https://empresa.com.mx
```

Para generar la salida en formato JSON estructurado en flujos de integracion continua:

```bash
python hreflang_validator.py https://empresa.com.mx -j
```

***

## Preguntas Frecuentes (FAQ Tecnico)

### 1. Por que los motores de busqueda ignoran las etiquetas hreflang implementadas?
La falta de reciprocidad en los enlaces de retorno y la ausencia de autorreferencia invalidan la agrupacion de etiquetas ante Google. Esta herramienta audita la simetria completa para evitar la degradacion de la visibilidad internacional.

### 2. Que funcion desempena la etiqueta x-default en portales multirregionales?
La anotacion x-default establece la pagina de destino predeterminada para usuarios ubicados fuera de las zonas linguisticas segmentadas. Su omision obliga a los buscadores a realizar conjeturas que reducen las tasas de conversion.

### 3. Como detecta el auditor las discrepancias entre canonical y hreflang?
El analizador compara los destinos declarados en la etiqueta canonical y en los enlaces alternativos para asegurar coherencia total. Cualquier desalineacion activa una alerta critica y deduce 20 puntos de la calificacion.

### 4. El analizador examina cabeceras HTTP Link ademas de etiquetas HTML?
Si, el motor de analisis inspecciona simultaneamente el encabezado HTML head y las cabeceras HTTP Link devueltas por el servidor. Esto permite auditar recursos no basados en HTML como documentos PDF y respuestas API.

### 5. Que estandares regulan la validacion de codigos de idioma y territorio?
Se exige el cumplimiento de ISO 639-1 para codigos de idioma de dos letras y de ISO 3166-1 alpha-2 para regiones de destino. Las combinaciones incorrectas o invertidas generan deducciones directas en la evaluacion tecnica.

***

## Consultoria en SEO Internacional y Despliegue Multirregional

Para diseno de portales globales y cumplimiento de estandares W3C, consulte al equipo tecnico de **TAVARDT**.

***

## Enlaces Utiles

* **Portal Corporativo:** https://ag.tavardt.com/mx/
* **Suite de Diagnosticos:** https://tools.tavardt.com/mx/
* **Contacto Tecnico:** https://ag.tavardt.com/mx/contacto/

***

### Licencia
Distribuido bajo la Licencia MIT. Consulte el archivo LICENSE para conocer los terminos completos.

***

© 2026 TAVARDT. Todos los derechos reservados.
