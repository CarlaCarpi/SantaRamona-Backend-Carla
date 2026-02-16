# Santa Ramona – Backend API (.NET)

Backend Web API desarrollado en **.NET**, encargado de la lógica de negocio, acceso a datos y autenticación del sistema.

## Tecnologías utilizadas

- .NET Web API
- Entity Framework Core
- SQL Server
- JWT Authentication
- Swagger

## Autenticación y Seguridad

El sistema implementa autenticación basada en **JWT (JSON Web Token)**.

Funcionalidades:

✔ Login de usuarios  
✔ Generación de token  
✔ Validación de permisos  
✔ Control de acceso por roles  

## Manejo de Roles

La API soporta control de acceso según rol del usuario.

Ejemplo de comportamiento:

- **Administrador** → Acceso total
- **Operador** → Acceso parcial
- **Consulta** → Solo lectura

Las restricciones se aplican desde los controladores mediante autorización.

## Base de Datos

Motor: **SQL Server**

Acceso a datos mediante **Entity Framework Core**.

Se implementan:

✔ Entidades  
✔ Relaciones  
✔ Migraciones  
✔ Validaciones  

## Endpoints

La API expone endpoints RESTful para:

- Autenticación
- Gestión de entidades
- Operaciones CRUD

Documentación disponible en **Swagger** al ejecutar el proyecto.

## Importante

Por motivos de seguridad:

✔ Las credenciales reales NO se encuentran en el repositorio  
✔ Se utiliza archivo de ejemplo para configuración  

---

Proyecto desarrollado con fines de práctica y portfolio profesional.
