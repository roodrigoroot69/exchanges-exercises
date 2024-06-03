## EJERCICIO 1. Automatización de Procesos

#### **Propuesta uno:**

[![EC2](https://github.com/roodrigoroot69/exchanges-exercises/blob/main/Propuesta%20uno/ec2.png?raw=true "EC2")](https://github.com/roodrigoroot69/exchanges-exercises/blob/main/Propuesta%20uno/ec2.png?raw=true "EC2")


**Componentes/Servicios Utilizados:**
- EC2
- Internet Gateway
- VPC
- S3
- RDS
- Docker

**Ventajas**:
* Facil Gestión y Administración del Proyecto
* Despliegue sencillo ya sea manualmente o con un Pipeline
* Configuración Rápida inicial
* Opcional, se le podrías agregar un LoadBalancer, para crear más instancias para soportar una mayor carga

**Desventajas**:
* EC2 siempre se mantiene encendido, por lo que se hará cobro incluso si no se llega a utilizar
* Si se necesitan agregar más configuración se tiene que ser muy especifico en lo que se requiere, y no como en otros servicios que algunas cosas se hacen por defecto.
* La configuración de CronJob en la instancia puede ser más compleja que usando alguna otra herramienta.
