# Validador de Etiquetas Hreflang y SEO Internacional

[![Validador Hreflang](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/mx/validador-etiquetas-hreflang/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria de reciprocidad internacional, orientacion geografica y anotaciones x-default en Mexico.

Desarrollado y mantenido por la division de ingenieria de busqueda y comercio transfronterizo de **TAVARDT**.

***

## Capacidades de Auditoria de Hreflang y SEO Internacional

* **Validacion de Reciprocidad de Enlaces**: Asegura que cada version regional contenga la liga reciproca correspondiente hacia la URL evaluada.
* **Auditoria de Codigos ISO**: Revision de claves de idioma ISO 639-1 y pais ISO 3166-1 (ej: `es-MX`, `en-US`), eliminando inconsistencias.
* **Etiqueta de Reserva x-default**: Comprobacion de pagina de aterrizaje global predeterminada.
* **Prevencion de Conflictos Canonicos**: Revision de congruencia entre la etiqueta canonical y las rutas hreflang autorreferenciales.
* **Calificacion de Calidad Internacional**: Evaluacion de 0 a 100 con recomendaciones tecnicas priorizadas.

***

## Instalacion y Ejecucion

Requiere Python 3.8 o superior sobre librerias nativas de Python.

```bash
git clone https://github.com/TAVARDT/hreflang-validator-mx.git
cd hreflang-validator-mx
python hreflang_validator.py https://empresa.com.mx
```

Para generar salida estructurada JSON:

```bash
python hreflang_validator.py https://empresa.com.mx -json
```

***

## Diagnostico Completo en la Web

Para analisis integral de posicionamiento internacional:

* **Validador de Etiquetas Hreflang Oficial**
* **[Portal Corporativo TAVARDT](https://ag.tavardt.com/mx/)**

***

## Consultoria en SEO Internacional y Comercio Digital

Para crecimiento digital transfronterizo y cumplimiento de Estandares W3C y Mejores Practicas Regionales, consulte al equipo de **TAVARDT**.

***

## Enlaces Útiles

* **Portal Corporativo:** https://ag.tavardt.com/mx/
* **Suite de Diagnósticos:** https://tools.tavardt.com/mx/
* **Contacto Técnico:** https://ag.tavardt.com/mx/contacto/

***

© 2026 TAVARDT. Todos los derechos reservados.
