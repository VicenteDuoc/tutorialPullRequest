# 🚗 **Rent-A-Car Express API - v1.0**

Este es un microservicio desarrollado en **Java con Spring Boot** para la gestión de una flota de vehículos. El proyecto aplica una arquitectura de **3 capas** (Controller, Service, Repository) y utiliza una lista en memoria para la persistencia de datos (Simulación de Base de Datos).

---

## 🛠️ **Tecnologías Utilizadas**

* **Java 21** o superior.
* **Spring Boot 4.x** (Spring Web).
* **Lombok**: Para la reducción de código boilerplate (Getters/Setters).
* **Jakarta Validation**: Para asegurar la integridad de los datos de entrada.
* **Maven**: Gestor de dependencias.

---

## 🏗️ **Arquitectura del Proyecto**

El proyecto sigue el flujo de responsabilidad única para facilitar el mantenimiento y la escalabilidad:

1. **Model**: Define la estructura del objeto `Auto` y sus validaciones.
2. **Repository**: Gestiona el acceso a los datos (Lista `ArrayList`).
3. **Service**: Contiene las reglas de negocio (Validación de patentes, lógica de arriendo).
4. **Controller**: Expone los endpoints REST para el consumo externo.

---

## 🚀 **Instalación y Ejecución**

1. **Clonar el repositorio:**
   
   ```bash
   
   git clone [https://github.com/tu-usuario/rentacar-v1.git](https://github.com/tu-usuario/rentacar-v1.git)

   ```