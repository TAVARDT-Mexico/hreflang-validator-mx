# Validador de Etiquetas Hreflang y SEO Internacional

[![Validador Hreflang](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/mx/validador-etiquetas-hreflang/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Auditoria de reciprocidad de enlaces alternativos, segmentacion regional de idioma ISO, y arquitectura de fallback x-default.

Desarrollado y mantenido por la division de ingenieria de busqueda internacional e infraestructura web de **TAVARDT**.

***

## Capacidades de Auditoria de Hreflang y SEO Internacional

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

## Diagnostico Completo en la Web

Para pruebas interactivas y verificacion visual de marcado internacional:

* [Validador Hreflang](https://tools.tavardt.com/mx/validador-etiquetas-hreflang/)
* [Portal Corporativo](https://ag.tavardt.com/mx/)

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
