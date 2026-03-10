# 🚀 ForoHub API

Proyecto desarrollado como parte del reto "ForoHub" del programa Oracle Next Education (ONE) en Alura LATAM. Esta API REST permite la gestión de un foro de discusión, facilitando operaciones CRUD sobre tópicos.

## 🛠 Tecnologías

* **Java 17**
* **Spring Boot 3.3.9**
* **Spring Data JPA**
* **PostgreSQL**
* **Flyway** (Gestión de migraciones)
* **Maven**

## 📂 Arquitectura

El proyecto sigue una estructura de **dominio** para organizar la lógica de negocio, los controladores y la infraestructura de seguridad.



## 📋 Requisitos Previos

* JDK 17 o superior instalado.
* PostgreSQL instalado y configurado.
* Maven instalado.

## ⚙️ Configuración

1. **Base de datos**: Crea una base de datos en PostgreSQL:
   ```sql
   CREATE DATABASE foro;
