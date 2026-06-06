# Análisis Forense — Extracción iOS (iPhone 4S)

**Tipo:** Análisis forense digital móvil  
**Dispositivo analizado:** Apple iPhone 4S  
**Herramienta principal:** Cellebrite Reader  
**Fecha:** Abril 2026  
**Contexto:** Práctica académica — Grado en Ciberseguridad · Universidad EUNEIZ

---

## Descripción

Análisis forense sobre una extracción lógica de un iPhone 4S, simulando un escenario real de investigación criminal. A partir de los datos extraídos del dispositivo, se da respuesta a un conjunto de preguntas de investigación planteadas por los investigadores del caso.

El análisis abarca múltiples fuentes de evidencia digital: contactos, mensajes (SMS, WhatsApp, Kik), imágenes, calendario, sistema de archivos y el informe preliminar del dispositivo generado por Cellebrite.

---

## Áreas analizadas

- Identificación del propietario del dispositivo
- Verificación de identidad real vs alias mediante billetes de avión
- Localización de un PO Box a través de la agenda de contactos
- Identificación de vehículo mediante análisis de imágenes (herramienta Grasp)
- Geolocalización de reuniones a partir de metadatos de fotos y mensajes
- Análisis de conversaciones para determinar contactos clave (Owen Cash, John Wells)
- Análisis del ICCID para identificar operadora de la última SIM (AT&T)
- Detección de cuenta iCloud y otros dispositivos a recuperar

---

## Metodología

1. Revisión del informe preliminar generado por Cellebrite Reader
2. Análisis de fuentes de datos del dispositivo (contactos, mensajes, imágenes, calendario)
3. Correlación cruzada de evidencias entre distintas fuentes
4. Uso de herramientas auxiliares (Google Lens, Grasp) para análisis de imágenes
5. Elaboración de hipótesis final sobre el caso

---

## Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| Cellebrite Reader | Análisis de la extracción lógica del dispositivo |
| Grasp | Identificación del vehículo mediante imagen |
| Google Lens | Geolocalización de fotografías |
| Google Maps / Earth | Verificación de ubicaciones |

---

## Resultados destacados

- Confirmación de la identidad real del sospechoso mediante billetes de avión
- Localización del mail drop en Miami (13727 SW 152 Street)
- Identificación del vehículo: BMW Z4 (E89), 2013–2016
- Reunión confirmada en Anaheim Marriott, California (enero 2016)
- Contacto clave identificado: Owen Cash
- Operadora SIM: AT&T (EE. UU.) — determinado mediante análisis del ICCID

---

## Documento

📄📄 [Ver informe completo](./Informe%20analisis%20forense%20extraccion%20ios.pdf)

