# API de Inventario

## Descripción
Esta API permite la gestión de un inventario y las compras realizadas por clientes. Los usuarios pueden tener roles de Administrador o Cliente, con funcionalidades específicas para cada rol.

### Funcionalidades Principales

#### Autenticación
- **Registro y Login de Usuarios:** Permite a los usuarios registrarse y autenticarse en el sistema.
- **Roles de Usuario:** Los usuarios pueden tener roles de Administrador o Cliente.

#### Funcionalidades del Administrador
- **CRUD de Productos:** Los administradores pueden crear, leer, actualizar y eliminar productos del inventario.
- **Visualización de Compras:** Los administradores pueden ver las compras realizadas por los clientes.

#### Funcionalidades del Cliente
- **Realización de Compras:** Los clientes pueden realizar compras de productos disponibles en el inventario.
- **Historial de Compras:** Los clientes pueden ver su historial de compras.

## Configuración del Proyecto

### Requisitos
- Node.js
- MySQL

### Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone <URL del repositorio>
   cd inventario-api
