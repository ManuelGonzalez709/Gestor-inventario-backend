# Gestor de Inventario Backend

![Java](https://img.shields.io/badge/language-Java-blue)
![Spring Boot](https://img.shields.io/badge/framework-SpringBoot-green)
![License](https://img.shields.io/github/license/SantanaDV/Gestor-inventario-backend)
![Build](https://img.shields.io/github/workflow/status/SantanaDV/Gestor-inventario-backend/CI?label=build)

---

**Gestor de Inventario Backend** es el corazón de una solución multiplataforma para la gestión eficiente de inventario y tareas en almacenes, desarrollado en **Spring Boot**. Este backend soporta aplicaciones móviles (Android) y de escritorio, facilitando el control de stock, la administración de tareas y la colaboración en equipo a través de integración con Git.

## 🚀 Características

- **Gestión de Inventario:** Control total de productos, entradas, salidas y movimientos.
- **Administración de Tareas:** Asignación y seguimiento eficiente de tareas para el personal.
- **Autenticación y Seguridad:** Sistema robusto de usuarios y roles, con protección JWT.
- **API RESTful:** Endpoints claros y bien documentados para interactuar desde cualquier cliente.
- **Notificaciones:** Soporte para alertar sobre movimientos críticos o tareas pendientes.
- **Historial y Auditoría:** Registro detallado de cambios y operaciones.
- **Integración con Git:** Facilita la colaboración y el versionado del proyecto.
- **Soporte Multiplataforma:** Pensado para integrarse con apps Android y clientes de escritorio.

## 📦 Estructura del Proyecto

```
src/
 └── main/
     ├── java/
     │    └── com/
     │         └── santanadv/
     │              └── gestorinventario/
     └── resources/
          ├── application.properties
          └── static/
```

## ⚙️ Instalación y Ejecución

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/SantanaDV/Gestor-inventario-backend.git
   cd Gestor-inventario-backend
   ```

2. **Configura la base de datos**  
   Edita `src/main/resources/application.properties` con los detalles de tu base de datos (MySQL recomendado).

3. **Construye y ejecuta el proyecto**
   ```bash
   ./mvnw spring-boot:run
   ```
   El backend estará disponible en `http://localhost:8080`.

## 🛠️ Tecnologías Utilizadas

- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **MySQL / PostgreSQL**
- **JWT Security**
- **Lombok**
- **Swagger/OpenAPI** *(Documentación de la API)*

## 📲 Integración con el Cliente

Consulta la [documentación de la API](http://localhost:8080/swagger-ui/) para conocer los endpoints disponibles y cómo conectar clientes Android o de escritorio.

## 🧑‍💻 Contribuciones

¡Las contribuciones son bienvenidas!  
1. Haz un fork del repositorio.
2. Crea una rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y commitea (`git commit -am 'Agrega nueva funcionalidad'`).
4. Haz push a tu rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## 🐞 Reporte de Errores y Solicitudes

Por favor, utiliza la sección de [Issues](https://github.com/SantanaDV/Gestor-inventario-backend/issues) para reportar bugs o solicitar nuevas características.

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

---

**Hecho con ❤️ por Manuelgonzalez709**

```
