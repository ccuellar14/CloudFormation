# Crear Cluster ECS en AWS con CloudFormation

-----

## Requisitos Previos

- Conocimientos en Estructura JSON
- Conocimientos en Productos de Red AWS

## Tabla de Contenido

### 1. Introducción
- ¿Qué es ECS?
- ¿Qué es CloudFormation?

### 2. Infraestructura de Cluster ECS
- Network
  - VPC
  - Subnet
  - LoadBalancer
- Computo
  - Instancias EC2
  - Imagenes Automatizadas AMI
- ALmacenamiento
  - Volumenes EBS

### 3. Componentes de ECS
 - Cluster
 - Instancia Contenedor
 - Definición de Tareas
 - Programador de Tareas
 - Servicios
 - Tareas
 - Contenedor

### 4. Descomponiendo JSON
 - Template CloudFormation ***JSON***
 -

-----

### 1. Introducción

#### ¿Qué es ECS?
El EC2 Servicio de contenedor de Amazon **(Amazon ECS)** es un servicio altamente escalable, de rápida gestión de contenedores que hace que sea fácil de ejecutar, detener y manejar contenedores acoplables en un clúster de instancias de Amazon EC2. Amazon ECS le permite iniciar y detener aplicaciones de contenedores habilitados con simples llamadas a la API, le permite obtener el estado de su clúster de un servicio centralizado,  el Amazon EC2 le da acceso a muchas características familiares.

Puede utilizar Amazon ECS para programar la colocación de contenedores en base a su necesidades de recursos a través de su grupo, las políticas de aislamiento, y los requisitos de disponibilidad. Amazon ECS elimina la necesidad de hacer funcionar sus propios sistemas de gestión de cluster y de gestión de configuración o preocupación acerca de la expansión de su infraestructura de gestión.

#### ¿Qué CloudFormation?
