# 🛍️ Sistema de Ventas

<div align="center">

# 🚀 Sistema Web de Gestión de Ventas

### Plataforma Empresarial desarrollada con Spring Boot, Java y MySQL

<p align="center">

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=for-the-badge&logo=springboot)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

</p>

</div>

---

# 📌 Descripción

**Sistema de Ventas** es una aplicación web desarrollada con **Spring Boot**, diseñada para administrar de manera eficiente las operaciones comerciales de una empresa o negocio.

La plataforma permite gestionar productos, clientes, ventas, compras, inventario, proveedores, usuarios y reportes desde un panel administrativo moderno, ofreciendo una arquitectura escalable basada en Java y el ecosistema Spring.

---

# 🚀 Características Principales

## 🔐 Autenticación

- Inicio de sesión seguro.
- Registro de usuarios.
- Recuperación de contraseña.
- Control de sesiones.
- Roles y permisos.
- Administración de usuarios.

---

## 📦 Gestión de Productos

- Registro de productos.
- Edición de productos.
- Eliminación lógica.
- Control de existencias.
- Categorías.
- Marcas.
- Códigos de barras.
- Imágenes de productos.
- Consulta rápida.
- Búsqueda avanzada.

---

## 👥 Gestión de Clientes

- Alta de clientes.
- Actualización de información.
- Historial de compras.
- Consulta por nombre.
- Consulta por correo.
- Clientes frecuentes.

---

## 🚚 Gestión de Proveedores

- Registro de proveedores.
- Información de contacto.
- Compras realizadas.
- Gestión de pedidos.

---

## 🛒 Gestión de Ventas

- Nueva venta.
- Venta rápida.
- Carrito de compras.
- Cálculo automático del total.
- Descuentos.
- Impuestos.
- Generación de factura.
- Cancelación de ventas.
- Historial completo.

---

## 📥 Gestión de Compras

- Registro de compras.
- Entrada de mercancía.
- Actualización automática del inventario.
- Historial de compras.
- Facturas de proveedores.

---

## 📊 Reportes

- Ventas por día.
- Ventas por mes.
- Ventas por año.
- Productos más vendidos.
- Clientes frecuentes.
- Ganancias.
- Compras realizadas.
- Inventario disponible.
- Productos agotados.

---

## 📈 Dashboard

- Total de ventas.
- Total de clientes.
- Total de productos.
- Productos con bajo stock.
- Ventas recientes.
- Gráficas estadísticas.
- Indicadores del negocio.

---

## 🔔 Notificaciones

- Stock bajo.
- Nuevas ventas.
- Compras registradas.
- Alertas administrativas.

---

# 🏗️ Arquitectura

El proyecto sigue una arquitectura por capas basada en Spring Boot.

- Controller
- Service
- Repository
- Entity
- DTO
- Configuration
- Security
- Exception Handler

---

# 🛠️ Tecnologías Utilizadas

## Backend

- Java 21
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- Spring Security
- Maven
- Lombok
- JWT

## Base de Datos

- MySQL
- PostgreSQL (Compatible)

## Frontend (Opcional)

- Thymeleaf
- Bootstrap
- HTML5
- CSS3
- JavaScript

## Herramientas

- IntelliJ IDEA
- Visual Studio Code
- Postman
- Git
- GitHub

---

# 📂 Estructura del Proyecto

```text
SisVentas/
│
├── src/
│   ├── main/
│   │
│   ├── java/
│   │   └── com/
│   │       └── ventas/
│   │
│   │           ├── config/
│   │           ├── controller/
│   │           ├── dto/
│   │           ├── entity/
│   │           ├── repository/
│   │           ├── service/
│   │           ├── security/
│   │           ├── exception/
│   │           └── SistemaVentasApplication.java
│   │
│   └── resources/
│       ├── static/
│       ├── templates/
│       ├── application.properties
│       └── data.sql
│
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md
```

---

# ⚙️ Instalación

## 1. Clonar el repositorio

```bash
git clone https://github.com/isaireyesp1/SisVentas.git
```

Entrar al proyecto

```bash
cd SisVentas
```

---

## 2. Configurar la Base de Datos

Crear una base de datos llamada:

```sql
ventasdb
```

---

## 3. Configurar application.properties

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ventasdb

spring.datasource.username=root

spring.datasource.password=tu_password

spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update

spring.jpa.show-sql=true

spring.jpa.properties.hibernate.format_sql=true
```

---

## 4. Instalar dependencias

```bash
mvn clean install
```

---

## 5. Ejecutar la aplicación

```bash
mvn spring-boot:run
```

o bien

```bash
./mvnw spring-boot:run
```

---

## 6. Abrir en el navegador

```text
http://localhost:8080
```

---

# 🔒 Seguridad

- Autenticación mediante Spring Security.
- Contraseñas cifradas con BCrypt.
- Tokens JWT.
- Protección CSRF.
- Validación de formularios.
- Control de acceso basado en roles.
- Manejo centralizado de excepciones.

---

# 📊 Módulos

| Módulo | Estado |
|---------|:------:|
| Dashboard | ✅ |
| Usuarios | ✅ |
| Roles | ✅ |
| Clientes | ✅ |
| Productos | ✅ |
| Categorías | ✅ |
| Proveedores | ✅ |
| Compras | ✅ |
| Ventas | ✅ |
| Inventario | ✅ |
| Reportes | ✅ |
| Configuración | ✅ |

---

# 📈 Funcionalidades Futuras

- 📱 Aplicación móvil.
- ☁️ Despliegue en la nube.
- 📄 Facturación electrónica.
- 📧 Envío automático de facturas.
- 📷 Escaneo de códigos QR.
- 📦 Gestión de múltiples sucursales.
- 📊 Business Intelligence.
- 🤖 Predicción de ventas mediante IA.
- 🌙 Modo oscuro.
- 🌍 Multiidioma.
- 📉 Reportes avanzados en PDF y Excel.
- 🔔 Notificaciones en tiempo real mediante WebSocket.

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas.

1. Haz un **Fork** del proyecto.

2. Crea una nueva rama.

```bash
git checkout -b feature/nueva-funcionalidad
```

3. Realiza tus cambios.

```bash
git commit -m "Nueva funcionalidad"
```

4. Envía los cambios.

```bash
git push origin feature/nueva-funcionalidad
```

5. Abre un **Pull Request**.

---

# 📜 Licencia

Este proyecto se distribuye bajo la licencia **MIT**, permitiendo su uso, modificación y distribución para proyectos personales, educativos y comerciales.

---

# 👨‍💻 Desarrollador

**Isai Reyes - FullStack Developer**

Desarrollado como un **Sistema Web de Gestión de Ventas** utilizando **Spring Boot**, **Spring Security**, **Spring Data JPA**, **Hibernate** y **MySQL**, siguiendo una arquitectura limpia y escalable basada en buenas prácticas de desarrollo empresarial.

---

<div align="center">

# 🛍️ Sistema de Ventas

### Administración Inteligente para Empresas Modernas

**Ventas • Inventario • Clientes • Compras • Reportes • Seguridad**

⭐ Si este proyecto te resulta útil, no olvides dejar una estrella en GitHub.

</div>
