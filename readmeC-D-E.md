# Tarea (c+d+e) · Edge, Fog, Mist y Cloud (DAW 1º)

# Tarea C — Edge Computing y relación con Cloud

## Definición
Edge Computing es un modelo de computación donde los datos se procesan cerca de su origen, como sensores o dispositivos IoT, en lugar de depender solo de centros de datos remotos. Esto permite reducir la latencia y mejorar la eficiencia en tiempo real.

## Relación Edge ↔ Cloud
Edge y Cloud son complementarios: el Edge procesa datos localmente para decisiones rápidas, mientras que la nube gestiona almacenamiento masivo, análisis profundo y respaldo. Los datos críticos se filtran en el Edge y luego se sincronizan con la nube para análisis históricos y escalabilidad.

## Ejemplo real
En ciudades inteligentes, los sensores de tráfico analizan información en tiempo real en nodos de Edge para controlar semáforos y alertar emergencias, mientras que la nube centraliza datos para planificación y optimización urbana. 

## Fuentes oficiales
- https://www.ibm.com/topics/edge-computing  
- https://azure.microsoft.com
- https://aws.amazon.com/what-is/edge-computing/



# Tarea D — Fog vs Mist (niveles y zonas de aplicación)

## Definición Fog
Fog Computing es un modelo de computación intermedio entre el Edge y la nube, que procesa y analiza datos cerca de los dispositivos, reduciendo la latencia y el tráfico hacia la nube, especialmente útil en redes distribuidas o IoT.

## Definición Mist
Mist Computing es la capa más cercana a los dispositivos finales, donde el procesamiento se realiza en microdispositivos o nodos muy pequeños. Permite respuestas inmediatas y eficiencia en tiempo real con recursos limitados.

## Esquema (Mermaid)
graph TD
    A[Dispositivos IoT] --> B[Mist]
    B --> C[Edge]
    C --> D[Fog]
    D --> E[Cloud]

## Zonas de aplicación
- Mist: Procesamiento inmediato en microdispositivos, decisiones rápidas y filtrado de datos locales.
- Edge: Procesamiento local más potente, coordinación de múltiples nodos y tareas de baja latencia.
- Fog: Agregación y análisis de datos a nivel regional, gestión de tráfico y optimización antes de enviar a la nube.
- Cloud: Almacenamiento masivo, análisis profundo, entrenamiento de modelos y coordinación global.


## 🅴 Tarea E — Ventajas de la Cloud en sistemas conectados
Incluye mínimo 3 ventajas (recomendado 5), con explicación + ejemplo.

1) Ventaja: ...
   Explicación: ...
   Ejemplo: ...

2) Ventaja: ...
   Explicación: ...
   Ejemplo: ...

3) Ventaja: ...
   Explicación: ...
   Ejemplo: ...

**Fuente oficial (mín. 1):**
- ...

## 📚 Fuentes (enlaces oficiales)
(Recopila aquí todos los enlaces oficiales usados)


