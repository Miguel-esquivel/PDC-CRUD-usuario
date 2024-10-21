
# 🧰 Colección de Postman para Pruebas de API

### 📝 Descripción

Esta colección de Postman está diseñada para realizar pruebas exhaustivas de la **API de gestión de usuarios** del portal. Proporciona una serie de solicitudes que permiten:

- 👤 Crear usuarios
- 🔍 Buscar usuarios
- 🔒 Restablecer contraseñas
- 🗑️ Eliminar usuarios

También incluye funcionalidades para gestionar la **autenticación** y otros aspectos clave de la API.

---

### 🗂️ Estructura de la Colección

La colección está organizada en diferentes secciones, cada una con casos de éxito y error, para garantizar una cobertura completa en las pruebas:

1. 🔐 **Autenticación**
2. 👥 **Gestión de Usuarios**
   - ➕ Crear Usuario
   - 🔎 Buscar Usuario
   - 🔄 Actualizar Contraseña
   - ❌ Eliminar Usuario

---

### 🚀 Cómo Usar la Colección

Sigue los siguientes pasos para realizar pruebas sobre la API:

1. **Importar la colección y el environment**:
   - Importa la colección `COLLECTION_CRUD_API` y el entorno `ENV_API_CRUD` en Postman.

2. **Ejecutar las solicitudes**:
   - Selecciona las solicitudes dentro de la colección según lo que desees probar (creación, búsqueda, eliminación, etc.).
   - Verifica las respuestas devueltas para validar los diferentes escenarios.

---

### ✅ Requisitos

Para ejecutar esta colección necesitas:

- 🛠️ Postman instalado en tu máquina.
- 🔑 Acceso a la API correspondiente con las credenciales o permisos adecuados.

🌐 **API URL**: [API Management](http://a28e9d3596b5a4cddbd8ae2d2c0eb6ce-600686809.sa-east-1.elb.amazonaws.com)

---

### 📝 Notas Adicionales

- Asegúrate de haber configurado correctamente las **variables de entorno** 🌍, como las URL de la API y los **tokens de autenticación** 🔑.
- Puedes modificar los casos de error para simular diferentes situaciones según sea necesario en tus pruebas.

---

¡Gracias por usar esta colección para pruebas de API! 🎯

---
