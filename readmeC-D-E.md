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


# Tarea E — Ventajas de la Cloud en sistemas conectados

1) Ventaja: Escalabilidad  
   Explicación: Permite aumentar o reducir recursos según la demanda sin infraestructura física adicional.  
   Ejemplo: Tienda online ajusta servidores en promociones.  

2) Ventaja: Acceso remoto  
   Explicación: Se puede acceder a los sistemas desde cualquier lugar con Internet.  
   Ejemplo: Supervisión de sensores industriales desde otra ciudad.  

3) Ventaja: Reducción de costos  
   Explicación: Minimiza gastos en hardware y mantenimiento pagando solo por lo usado.  
   Ejemplo: Startup de IoT usa servidores en la nube sin comprarlos.  

4) Ventaja: Seguridad y respaldo  
   Explicación: Cifrado, copias de seguridad y recuperación ante fallos protegen los datos.  
   Ejemplo: Clínica recupera información de pacientes tras un fallo local.  

5) Ventaja: Análisis centralizado de datos  
   Explicación: Facilita combinar información de múltiples dispositivos para tomar decisiones.  
   Ejemplo: Empresa de logística optimiza rutas usando datos de GPS.  

## Fuente oficial
- Microsoft Azure — https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/

## Fuentes (enlaces oficiales)
- https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/
- https://www.ibm.com/topics/edge-computing  
- https://azure.microsoft.com
- https://aws.amazon.com/what-is/edge-computing/





