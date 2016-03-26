# Crear Cluster ECS en AWS con CloudFormation

-----

## Requisitos Previos

- Conocimientos en Estructura JSON
- Conocimientos en Productos de Red AWS

## Tabla de Contenido

### 1. Introducción
- ¿Qué es ECS?
- ¿Qué es CloudFormation?

### 2. Componentes de ECS
 - Cluster
 - Instancia Contenedor
 - Definición de Tareas
 - Programador de Tareas
 - Servicios
 - Tareas
 - Contenedor

### 3. Template
 - [Template CloudFormation ***JSON***](https://github.com/ccuellar14/CloudFormation/blob/master/ECS/Cluster_ECS.json"Cluster_ECS.json")
 -

-----

### 1. Introducción

#### ¿Qué es ECS?
El EC2 Servicio de contenedor de Amazon **(Amazon ECS)** es un servicio altamente escalable, de rápida gestión de contenedores que hace que sea fácil de ejecutar, detener y manejar contenedores acoplables en un clúster de instancias de Amazon EC2. Amazon ECS le permite iniciar y detener aplicaciones de contenedores habilitados con simples llamadas a la API, le permite obtener el estado de su clúster de un servicio centralizado,  el Amazon EC2 le da acceso a muchas características familiares.

Puede utilizar Amazon ECS para programar la colocación de contenedores en base a su necesidades de recursos a través de su grupo, las políticas de aislamiento, y los requisitos de disponibilidad. Amazon ECS elimina la necesidad de hacer funcionar sus propios sistemas de gestión de cluster y de gestión de configuración o preocupación acerca de la expansión de su infraestructura de gestión.

#### ¿Qué CloudFormation?
CloudFormation es un producto de AWS que ofrece a desarrolladores y administradores de sistemas un método sencillo de crear una colección de recursos de AWS relacionados entre sí para ofrecerlos de una manera ordenada y predecible.


### 2. Componentes de ECS
#### Cluster
Es una agrupación lógica de instancias del contenedor de EC2 en las que se puede colocar tareas y configuraciones especificas y personalizadas.

#### Instancia Contenedor
Son instancias de EC2 que ejecutan el Agente de ECS y se registran al Cluster.

#### Definición de Tareas
Descripción de una aplicación que contiene una o más definiciones dentro contenedor.

#### Programador de Tareas
El método utilizado para la colocación de tareas en instancias dentro de los contenedores.

#### Servicios
Un servicio de Amazon ECS le permite ejecutar y mantener un determinado número de instancias de forma simultanea.

#### Tareas
Una instancia de una definición de la tarea que se está ejecutando en una instancia del contenedor.

#### Contenedor
Un contenedor de Linux que se creó como parte de una tarea.


### 3. Template
Es un archivo de texto con formato JSON (Javascript Object Notation) que describe la infraestructura de AWS necesaria para ejecutar una aplicación o un servicio, junto con las interconexiones que existan entre ellos.
