# # Tarea (a+b) · Cloud: niveles y funciones (DAW 1º)

## 🅰️ Tarea A — Niveles de cloud (IaaS/PaaS/SaaS)

Crea una tabla con 10 servicios reales. Incluye enlace oficial y justifica responsabilidades.

| Servicio | Proveedor | Nivel (IaaS/PaaS/SaaS) | Enlace oficial | ¿Qué gestiona el proveedor? | ¿Qué gestiona el equipo/usuario? |
|---------|----------|-------------------------|----------------|-----------------------------|----------------------------------|
| Amazon EC2 | AWS | IaaS | https://aws.amazon.com/ec2/ | Hardware, red, hipervisores, seguridad física. | Sistema operativo, aplicaciones, configuración. |
| Google Compute Engine | Google Cloud | IaaS | https://cloud.google.com/compute | Infraestructura física y virtualización. | SO, aplicaciones, seguridad lógica. |
| Azure Virtual Machines | Microsoft | IaaS | https://azure.microsoft.com/services/virtual-machines/ | Data center, hardware, hypervisor. | SO, middleware, aplicaciones. |
| Heroku | Salesforce | PaaS | https://www.heroku.com/ | Plataforma, contenedores, escalado. | Código de la aplicación y configuración. |
| Google App Engine | Google Cloud | PaaS | https://cloud.google.com/appengine | Runtime, balanceo, escalado automático. | Código de la aplicación. |
| AWS Elastic Beanstalk | AWS | PaaS | https://aws.amazon.com/elasticbeanstalk/ | Orquestación de recursos y despliegue. | Código y parámetros de configuración. |
| Azure App Service | Microsoft | PaaS | https://azure.microsoft.com/services/app-service/ | Plataforma web, seguridad base, escalado. | Aplicación y ajustes de despliegue. |
| Google Workspace | Google | SaaS | https://workspace.google.com/ | Aplicaciones, infraestructura, actualizaciones. | Gestión de usuarios y datos. |
| Salesforce CRM | Salesforce | SaaS | https://www.salesforce.com/ | Software CRM completo y mantenimiento. | Configuración y datos de clientes. |
| Microsoft 365 | Microsoft | SaaS | https://www.microsoft.com/microsoft-365 | Aplicaciones ofimáticas y servicios cloud. | Uso del software y gestión de datos. |


## 🅱️ Tarea B — Funciones principales de cloud (arquitectura)
Incluye un diagrama (ASCII/Mermaid/imagen) y una explicación breve.

### Diagrama
<img width="1148" height="654" alt="image" src="https://github.com/user-attachments/assets/98c6f4bd-ee1a-48ae-99e2-fa361b9873e0" />


### Explicación (8–12 líneas)
(Describe el flujo front → API → BBDD/storage y dónde entra la cloud)
El usuario accede a la aplicación desde el navegador web.
El frontend se encarga de mostrar la interfaz y enviar peticiones HTTP al backend.
El backend se ejecuta en la cloud (en un servicio PaaS) y procesa la lógica de negocio.
La API recibe las peticiones del frontend y decide qué datos necesita.
Para datos estructurados, el backend consulta la base de datos en la nube.
Para archivos como imágenes, usa un servicio de almacenamiento cloud.
La cloud permite escalado automático según la carga de usuarios.
También se encarga de la alta disponibilidad y la seguridad básica de la infraestructura.

### Mapeo de funciones cloud a componentes (mínimo 3)
- Procesamiento → …
- Ejecución → …
- Almacenamiento → …
- Intercambio → … (opcional si ya tienes 3)

## 📚 Fuentes (enlaces oficiales)
(Enlaces oficiales usados en la tabla A y en la B)
