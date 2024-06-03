## EJERCICIO 1. Automatización de Procesos

#### **Propuesta Dos:**

[![Lambdas](https://github.com/roodrigoroot69/exchanges-exercises/blob/main/Propuesta%20dos/lambdas.png?raw=true "Lambdas")](https://github.com/roodrigoroot69/exchanges-exercises/blob/main/Propuesta%20dos/lambdas.png?raw=true "Lambdas")

Tendremos una lambda que se ejecutará cada día de las 18:00hrs a 18:05 hrs, lo que hará es cambiar el **rate limit** y puedan recibir los datos del websocket y después cambiar su valor a 0 y ya no recibir datos.

**Componentes/Servicios Utilizados:**
- Lambda
- S3
- RDS
- Docker
- API Gateway

**Ventajas**:
* Facil Gestión y Administración del Proyecto
* Despliegue sencillo ya sea manualmente o con un Pipeline
* División del problema en funciones
* Se cobra por uso
* Actualicación, parches de seguridad y gestion de Hardware se hace cargo AWS
* Hay frameworks que se enfocan en Serverless, lo cual ayuda a manejar con IaC desde el inicio

**Desventajas**:
* La configuración inicial puede ser más tardada, ya que se usaran varias funciones y se tienen que repetir para cada una
* Los despligues usando Pipelines, pueden llegar a ser más complejos ya sea usando Frameworks o bien si se hace usando aws cli
* Al usar varios servicios el tiempo de pruebas puede ser un poco más tardado
