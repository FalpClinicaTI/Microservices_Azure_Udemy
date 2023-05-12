# DevOps y Continuous Integration - Arquitectura de Microservicios en ASP.NET Core

Este repositorio contiene el código y la documentación relacionados con el curso de DevOps y Continuous Integration orientado a Microservicios ASP.NET Core. El curso está basado en un caso práctico de un conjunto de microservicios que necesitan desplegarse en un ambiente de producción en servidores AKS (Azure Kubernetes Service) y configurar los proyectos de microservicios en repositorios Git.

## Temas cubiertos en el curso

En este curso, exploraremos los siguientes temas:

- Arquitectura de microservicios en proyectos .NET 7
- Configuración de repositorios Git para nuestros proyectos
- Sincronización de Git en Visual Studio
- Creación de imágenes y contenedores Docker para cada microservicio
- Publicación y registro de cada imagen de microservicio en el Docker Hub
- Creación de un clúster Kubernetes
- Diseño de componentes YAML para el despliegue de servicios Kubernetes en el clúster
- Despliegue del clúster Kubernetes en AKS (Azure Kubernetes Service)
- Creación de pipelines en Azure DevOps para automatizar el proceso de despliegue
- Dockerización de las bases de datos MongoDB y SQL Server

## Herramientas utilizadas

Las siguientes herramientas son utilizadas en este proyecto:

- Docker: herramienta estándar para la creación y administración de contenedores.
- Kubernetes: sistema de orquestación de contenedores que permite el despliegue, escalamiento y administración de aplicaciones en contenedores.
- Azure DevOps: plataforma de desarrollo y entrega continua basada en la nube que proporciona herramientas para automatizar el ciclo de vida de desarrollo de software.
- .NET Core: framework de desarrollo de aplicaciones multiplataforma de código abierto desarrollado por Microsoft.
- SQL Server: sistema de gestión de bases de datos relacionales desarrollado por Microsoft.
- MongoDB: base de datos NoSQL de documentos de código abierto.

## Estructura del repositorio

El repositorio está organizado de la siguiente manera:

- **/microservicio1**: Contiene el código fuente y los archivos relacionados con el microservicio API Libreria.
- **/microservicio2**: Contiene el código fuente y los archivos relacionados con el microservicio API Seguridad y Autenticación.
- **/microservicio3**: Contiene el código fuente y los archivos relacionados con el microservicio  API Gateway.
- **/kubernetes**: Contiene los archivos YAML para el despliegue de los servicios en el clúster Kubernetes.
- **/pipeline**: Contiene los archivos de configuración de los pipelines en Azure DevOps.
- **/documentacion**: Contiene la documentación relacionada con el curso.

## Requisitos previos

Antes de comenzar con el curso, asegúrese de tener instaladas las siguientes herramientas:

- Docker: [Descargar e instalar Docker](https://www.docker.com/get-started)
- Kubernetes: [Configurar un clúster Kubernetes en Azure](https://azure.microsoft.com/services/kubernetes-service/)
- Azure DevOps: [Crear una cuenta en Azure DevOps](https://azure.microsoft.com/services/devops/)

## Documentación adicional

En la carpeta `/documentacion`, encontrará documentación adicional que lo guiará a lo largo del curso. Asegúrese de revisarla antes de comenzar.

## Contribución

Si desea contribuir a este proyecto, le invitamos a que envíe sus propuestas mediante pull requests. Agradecemos su colaboración.

## Equipo: 
- David Picero Virraroel
- Vicente de la Fuente González
- Fernando Valdés Herrera.

