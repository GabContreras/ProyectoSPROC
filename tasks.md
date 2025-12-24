# TAREAS DEL PROYECTO SPROC - E-COMMERCE MERN

## FASE 1: CONFIGURACIÓN INICIAL (Semanas 1-2) - 31 horas totales

### Setup del Proyecto
- [ ] **SETUP-001**: Inicializar repositorio Git y estructura de carpetas (1h)
- [ ] **SETUP-002**: Configurar MongoDB Atlas y base de datos (1h)
- [ ] **SETUP-003**: Setup inicial del backend con Express.js (2h)
- [ ] **SETUP-004**: Setup inicial del frontend con React + Vite (2h)
- [ ] **SETUP-005**: Configurar variables de entorno (.env) (2h)

### Diseño y Arquitectura
- [✔] **DESIGN-001**: Crear mockups en Figma - Página principal (5h)
- [✔] **DESIGN-002**: Crear mockups en Figma - Panel admin (5h)
- [✔] **DESIGN-003**: Definir arquitectura del sistema (2h)
- [✔] **DESIGN-004**: Definir estructura de API REST (1h)
- [ ] **DESIGN-005**: Diseñar esquemas de base de datos (4h)

### Documentación Inicial
- [ ] **DOC-001**: Crear README.md principal (2h)
- [ ] **DOC-002**: Documentar guía de instalación (en readme) (2h)
- [ ] **DOC-003**: Documentar convenciones de código (2h)

---

## FASE 2: BACKEND - AUTENTICACIÓN Y USUARIOS (Semanas 3-4) - 70 horas

### Modelos de Datos
- [ ] **MODEL-001**: Crear modelo de Usuario (User) (3h)
- [ ] **MODEL-002**: Crear modelo de Rol (Role) (2h)
- [ ] **MODEL-003**: Crear modelo de Sesión (Session) (2h)
- [ ] **MODEL-004**: Implementar validaciones de modelos (2h)

### Autenticación
- [ ] **AUTH-001**: Implementar registro de usuarios (5h)
- [ ] **AUTH-002**: Implementar login con JWT (5h)
- [ ] **AUTH-003**: Implementar logout (2h)
- [ ] **AUTH-004**: Crear middleware de autenticación (3h)
- [ ] **AUTH-005**: Implementar hash de contraseñas con bcrypt (2h)
- [ ] **AUTH-006**: Crear endpoint para recuperar contraseña (4h)
- [ ] **AUTH-007**: Implementar refresh tokens (4h)

### Sistema de Roles y Permisos
- [ ] **ROLE-001**: Crear middleware de autorización por roles (4h)
- [ ] **ROLE-002**: Definir permisos para Admin (2h)
- [ ] **ROLE-003**: Definir permisos para Empleado (2h)
- [ ] **ROLE-004**: Definir permisos para Cliente (2h)
- [ ] **ROLE-005**: Implementar verificación de permisos (3h)

### API de Usuarios
- [ ] **USER-API-001**: Endpoint GET /api/users (obtener usuarios) (3h)
- [ ] **USER-API-002**: Endpoint GET /api/users/:id (obtener usuario por ID) (2h)
- [ ] **USER-API-003**: Endpoint PUT /api/users/:id (actualizar usuario) (3h)
- [ ] **USER-API-004**: Endpoint DELETE /api/users/:id (eliminar usuario) (2h)
- [ ] **USER-API-005**: Endpoint GET /api/users/profile (perfil actual) (3h)

### Testing
- [ ] **TEST-AUTH-001**: Tests unitarios para autenticación (5h)
- [ ] **TEST-AUTH-002**: Tests de integración para usuarios (4h)

---

## FASE 3: BACKEND - PRODUCTOS Y CATEGORÍAS (Semanas 5-6) - 73 horas

### Modelos
- [ ] **MODEL-005**: Crear modelo de Producto (Product) (4h)
- [ ] **MODEL-006**: Crear modelo de Categoría (Category) (3h)
- [ ] **MODEL-007**: Crear modelo de Marca (Brand) (2h)

### API de Productos
- [ ] **PROD-API-001**: Endpoint POST /api/products (crear producto) (5h)
- [ ] **PROD-API-002**: Endpoint GET /api/products (listar con paginación) (5h)
- [ ] **PROD-API-003**: Endpoint GET /api/products/:id (detalle producto) (4h)
- [ ] **PROD-API-004**: Endpoint PUT /api/products/:id (actualizar) (5h)
- [ ] **PROD-API-005**: Endpoint DELETE /api/products/:id (eliminar) (3h)
- [ ] **PROD-API-006**: Endpoint GET /api/products/search (búsqueda) (6h)
- [ ] **PROD-API-007**: Endpoint GET /api/products/filter (filtros avanzados) (6h)

### API de Categorías
- [ ] **CAT-API-001**: Endpoint POST /api/categories (crear categoría) (3h)
- [ ] **CAT-API-002**: Endpoint GET /api/categories (listar) (3h)
- [ ] **CAT-API-003**: Endpoint PUT /api/categories/:id (actualizar) (3h)
- [ ] **CAT-API-004**: Endpoint DELETE /api/categories/:id (eliminar) (2h)
- [ ] **CAT-API-005**: Implementar subcategorías (4h)

### Testing
- [ ] **TEST-PROD-001**: Tests para CRUD de productos (6h)
- [ ] **TEST-PROD-002**: Tests para búsqueda y filtros (5h)

---

## FASE 4: BACKEND - PEDIDOS Y PAGOS (Semanas 7-8) - 85 horas

### Modelos
- [ ] **MODEL-008**: Crear modelo de Pedido (Order) (4h)
- [ ] **MODEL-009**: Crear LocalStorage de CarritoCompra (Cart) (3h)
- [ ] **MODEL-010**: Implementar modelo de Pago (Payment) (3h)

### API de Carrito
- [ ] **CART-API-001**: agregar producto (2h)
- [ ] **CART-API-002**: actualizar cantidad (2h)
- [ ] **CART-API-003**: eliminar item (2h)
- [ ] **CART-API-004**: vaciar carrito (2h)

### API de Pedidos
- [ ] **ORDER-API-001**: Endpoint POST /api/orders (crear pedido) (6h)
- [ ] **ORDER-API-002**: Endpoint GET /api/orders (listar pedidos) (4h)
- [ ] **ORDER-API-003**: Endpoint GET /api/orders/:id (detalle pedido) (4h)
- [ ] **ORDER-API-004**: Endpoint PUT /api/orders/:id/status (actualizar estado) (4h)
- [ ] **ORDER-API-005**: Endpoint GET /api/orders/user/:userId (pedidos por usuario) (4h)

### Integración Wompi
- [ ] **PAYMENT-001**: Configurar credenciales de Wompi (3h)
- [ ] **PAYMENT-002**: Endpoint POST /api/payments/create (iniciar pago) (8h)
- [ ] **PAYMENT-003**: Webhook para confirmación de pago (7h)
- [ ] **PAYMENT-004**: Endpoint GET /api/payments/:id (estado de pago) (4h)
- [ ] **PAYMENT-005**: Manejo de errores de pago (4h)
- [ ] **PAYMENT-006**: Implementar reembolsos (5h)

### Notificaciones
- [ ] **NOTIF-001**: Configurar servicio de email (Smtp) (4h)
- [ ] **NOTIF-002**: Template email confirmación de pedido (3h)
- [ ] **NOTIF-003**: Notificación de cambio de estado (3h)

### Testing
- [ ] **TEST-ORDER-001**: Tests para carrito de compras (5h)
- [ ] **TEST-ORDER-002**: Tests para pedidos (4h)

---

## FASE 5: BACKEND - CHAT Y EMPLEADOS (Semanas 9-10) - 95 horas 

### Sistema de Chat
- [ ] **CHAT-001**: Configurar Socket.io en el servidor (4h)
- [ ] **CHAT-002**: Crear modelo de Conversación (Conversation) (3h)
- [ ] **CHAT-003**: Crear modelo de Mensaje (Message) (3h)
- [ ] **CHAT-004**: Evento 'send_message' (enviar mensaje) (5h)
- [ ] **CHAT-005**: Evento 'join_conversation' (unirse a conversación) (4h)
- [ ] **CHAT-006**: Evento 'typing' (indicador escribiendo) (3h)
- [ ] **CHAT-007**: Evento 'message_read' (marcar como leído) (3h)
- [ ] **CHAT-008**: Endpoint GET /api/conversations (listar conversaciones) (4h)
- [ ] **CHAT-009**: Endpoint GET /api/conversations/:id/messages (mensajes) (4h)
- [ ] **CHAT-010**: Sistema de notificaciones en tiempo real (5h)
- [ ] **CHAT-011**: Almacenar historial en MongoDB (4h)

### API de Empleados
- [ ] **EMP-API-001**: Endpoint POST /api/employees (crear empleado) (4h)
- [ ] **EMP-API-002**: Endpoint GET /api/employees (listar empleados) (3h)
- [ ] **EMP-API-003**: Endpoint PUT /api/employees/:id (actualizar) (3h)
- [ ] **EMP-API-004**: Endpoint DELETE /api/employees/:id (eliminar) (3h)
- [ ] **EMP-API-005**: Endpoint PUT /api/employees/:id/role (cambiar rol) (3h)
- [ ] **EMP-API-006**: Endpoint GET /api/employees/:id/activity (logs de actividad) (4h)

### Integración con Mapas
- [ ] **MAP-001**: Configurar API de Google Maps (3h)
- [ ] **MAP-002**: Endpoint GET /api/locations (sucursales) (4h)
- [ ] **MAP-003**: Implementar geocodificación de direcciones (4h)

### Dashboard Estadísticas
- [ ] **STATS-001**: Endpoint GET /api/stats/sales (estadísticas ventas) (5h)
- [ ] **STATS-002**: Endpoint GET /api/stats/products (productos más vendidos) (4h)
- [ ] **STATS-003**: Endpoint GET /api/stats/users (nuevos usuarios) (3h)
- [ ] **STATS-004**: Endpoint GET /api/stats/revenue (ingresos) (4h)

### Testing
- [ ] **TEST-CHAT-001**: Tests para sistema de chat (5h)
- [ ] **TEST-EMP-001**: Tests para gestión de empleados (4h)

---

## FASE 6: FRONTEND - COMPONENTES BASE (Semanas 3-4) - 75 horas

### Configuración
- [ ] **FE-SETUP-001**: Configurar React Router (3h)
- [ ] **FE-SETUP-002**: Usar Fetch API (fetch nativo) para llamadas a la API (3h)
- [ ] **FE-SETUP-003**: Configurar Context API (5h)
- [ ] **FE-SETUP-004**: Configurar Tailwind CSS (3h)
- [ ] **FE-SETUP-005**: Crear sistema de themes (4h)

### Componentes Reutilizables
- [ ] **COMP-001**: Componente Button (2h)
- [ ] **COMP-002**: Componente Input (3h)
- [ ] **COMP-003**: Componente Card (2h)
- [ ] **COMP-004**: Componente Modal (4h)
- [ ] **COMP-005**: Componente Navbar (5h)
- [ ] **COMP-006**: Componente Footer (3h)
- [ ] **COMP-007**: Componente Loader/Spinner (2h)
- [ ] **COMP-008**: Componente Toast/Notification (3h)
- [ ] **COMP-009**: Componente Pagination (4h)
- [ ] **COMP-010**: Componente SearchBar (4h)
- [ ] **COMP-011**: Componente Dropdown (3h)
- [ ] **COMP-012**: Componente Badge (2h)

### Layout
- [ ] **LAYOUT-001**: Crear MainLayout (página pública) (4h)
- [ ] **LAYOUT-002**: Crear AdminLayout (panel admin) (4h)
- [ ] **LAYOUT-003**: Crear AuthLayout (login/registro) (3h)
- [ ] **LAYOUT-004**: Implementar Sidebar para admin (5h)

### Autenticación Frontend
- [ ] **FE-AUTH-001**: Página de Login (5h)
- [ ] **FE-AUTH-002**: Página de Registro (5h)
- [ ] **FE-AUTH-003**: Contexto de autenticación (4h)
- [ ] **FE-AUTH-004**: ProtectedRoute component (3h)
- [ ] **FE-AUTH-005**: Página de recuperar contraseña (4h)

---

## FASE 7: FRONTEND - E-COMMERCE PÚBLICO (Semanas 5-6) - 90 horas

### Página Principal
- [ ] **HOME-001**: Hero section con banner principal (4h)
- [ ] **HOME-002**: Sección de categorías destacadas (3h)
- [ ] **HOME-003**: Sección "Lo más reciente" (3h)
- [ ] **HOME-004**: Sección de promociones (3h)
- [ ] **HOME-005**: Cards informativas (envío, garantía, pago) (3h)
- [ ] **HOME-006**: Newsletter signup (3h)

### Catálogo de Productos
- [ ] **CATALOG-001**: Página de listado de productos (5h)
- [ ] **CATALOG-002**: Implementar filtros laterales (6h)
- [ ] **CATALOG-003**: Implementar ordenamiento (3h)
- [ ] **CATALOG-004**: Grid responsive de productos (4h)
- [ ] **CATALOG-005**: Componente ProductCard (3h)
- [ ] **CATALOG-006**: Paginación de resultados (3h)

### Detalle de Producto
- [ ] **DETAIL-001**: Página de detalle de producto (5h)
- [ ] **DETAIL-002**: Galería de imágenes con zoom (5h)
- [ ] **DETAIL-003**: Selector de cantidad (2h)
- [ ] **DETAIL-004**: Botón "Agregar al carrito" (3h)
- [ ] **DETAIL-005**: Sección de información del producto (3h)
- [ ] **DETAIL-006**: Productos relacionados (4h)

### Buscador
- [ ] **SEARCH-001**: Barra de búsqueda global (4h)
- [ ] **SEARCH-002**: Página de resultados de búsqueda (4h)
- [ ] **SEARCH-003**: Autocompletado de búsqueda (5h)
- [ ] **SEARCH-004**: Búsqueda por categoría (3h)

### Carrito de Compras
- [ ] **CART-001**: Componente de carrito (dropdown) (4h)
- [ ] **CART-002**: Página completa del carrito (5h)
- [ ] **CART-003**: Actualizar cantidad de productos (3h)
- [ ] **CART-004**: Eliminar productos del carrito (2h)
- [ ] **CART-005**: Cálculo de totales (2h)

---

## FASE 8: FRONTEND - CHECKOUT Y PERFIL (Semanas 7-8) - 75 horas

### Proceso de Checkout
- [ ] **CHECKOUT-001**: Página de checkout - Paso 1: Información (5h)
- [ ] **CHECKOUT-002**: Formulario de dirección de envío (4h)
- [ ] **CHECKOUT-003**: Página de checkout - Paso 2: Método de pago (5h)
- [ ] **CHECKOUT-004**: Integración con Wompi frontend (8h)
- [ ] **CHECKOUT-005**: Página de checkout - Paso 3: Resumen (4h)
- [ ] **CHECKOUT-006**: Página de confirmación de pedido (4h)
- [ ] **CHECKOUT-007**: Manejo de errores de pago (3h)

### Perfil de Usuario
- [ ] **PROFILE-001**: Página de perfil de usuario (5h)
- [ ] **PROFILE-002**: Editar información personal (4h)
- [ ] **PROFILE-003**: Cambiar contraseña (3h)
- [ ] **PROFILE-004**: Historial de pedidos (5h)
- [ ] **PROFILE-005**: Detalle de pedido individual (4h)
- [ ] **PROFILE-006**: Direcciones guardadas (4h)

### Integración de Mapas
- [ ] **MAP-FE-001**: Componente de mapa con Google Maps (5h)
- [ ] **MAP-FE-002**: Página de ubicaciones/sucursales (4h)
- [ ] **MAP-FE-003**: Selector de dirección en mapa (4h)

### Responsive Design
- [ ] **RESP-001**: Optimizar home para móvil (3h)
- [ ] **RESP-002**: Optimizar catálogo para móvil (3h)
- [ ] **RESP-003**: Optimizar checkout para móvil (3h)

---

## FASE 9: FRONTEND - PANEL ADMINISTRATIVO (Semanas 9-10) - 95 horas

### Dashboard
- [ ] **ADMIN-DASH-001**: Dashboard principal con estadísticas (6h)
- [ ] **ADMIN-DASH-002**: Gráficos de ventas (Chart.js) (5h)
- [ ] **ADMIN-DASH-003**: Widget de productos más vendidos (4h)
- [ ] **ADMIN-DASH-004**: Widget de usuarios nuevos (3h)
- [ ] **ADMIN-DASH-005**: Lista de pedidos pendientes (4h)
- [ ] **ADMIN-DASH-006**: Indicadores de rendimiento (KPIs) (4h)

### Gestión de Productos
- [ ] **ADMIN-PROD-001**: Página de lista de productos (5h)
- [ ] **ADMIN-PROD-002**: Formulario crear producto (6h)
- [ ] **ADMIN-PROD-003**: Formulario editar producto (5h)
- [ ] **ADMIN-PROD-004**: Subir múltiples imágenes (5h)
- [ ] **ADMIN-PROD-005**: Eliminar producto con confirmación (2h)
- [ ] **ADMIN-PROD-006**: Búsqueda y filtros en admin (4h)
- [ ] **ADMIN-PROD-007**: Gestión de categorías (4h)

### Gestión de Pedidos
- [ ] **ADMIN-ORDER-001**: Lista de todos los pedidos (5h)
- [ ] **ADMIN-ORDER-002**: Detalle de pedido (4h)
- [ ] **ADMIN-ORDER-003**: Actualizar estado de pedido (4h)
- [ ] **ADMIN-ORDER-004**: Filtros por estado/fecha (4h)
- [ ] **ADMIN-ORDER-005**: Exportar pedidos a CSV (3h)
- [ ] **ADMIN-ORDER-006**: Modal de edición de pedido (3h)

### Gestión de Empleados
- [ ] **ADMIN-EMP-001**: Lista de empleados (4h)
- [ ] **ADMIN-EMP-002**: Formulario crear empleado (4h)
- [ ] **ADMIN-EMP-003**: Editar empleado (3h)
- [ ] **ADMIN-EMP-004**: Eliminar empleado (2h)
- [ ] **ADMIN-EMP-005**: Asignar/cambiar roles (3h)

### Editor de Promociones
- [ ] **ADMIN-PROMO-001**: Página de gestión de banners (4h)
- [ ] **ADMIN-PROMO-002**: Subir imagen de banner (3h)
- [ ] **ADMIN-PROMO-003**: Editar texto y enlaces del banner (3h)
- [ ] **ADMIN-PROMO-004**: Programar fechas de promoción (4h)

---

## FASE 10: FRONTEND - SISTEMA DE CHAT (Semanas 9-10) - 55 horas

### Configuración Socket.io
- [ ] **CHAT-FE-001**: Configurar cliente de Socket.io (3h)
- [ ] **CHAT-FE-002**: Crear contexto de chat (3h)
- [ ] **CHAT-FE-003**: Manejo de conexión/desconexión (2h)

### Chat para Clientes
- [ ] **CHAT-CLIENT-001**: Botón flotante de chat (3h)
- [ ] **CHAT-CLIENT-002**: Ventana de chat (widget) (7h)
- [ ] **CHAT-CLIENT-003**: Input de mensaje (3h)
- [ ] **CHAT-CLIENT-004**: Lista de mensajes (4h)
- [ ] **CHAT-CLIENT-005**: Indicador "escribiendo..." (3h)
- [ ] **CHAT-CLIENT-006**: Notificaciones de mensaje nuevo (3h)

### Chat para Admin
- [ ] **CHAT-ADMIN-001**: Página de conversaciones (5h)
- [ ] **CHAT-ADMIN-002**: Lista de conversaciones activas (4h)
- [ ] **CHAT-ADMIN-003**: Ventana de chat completa (5h)
- [ ] **CHAT-ADMIN-004**: Marcar mensajes como leídos (3h)
- [ ] **CHAT-ADMIN-005**: Badge de mensajes no leídos (3h)

### Funcionalidades Adicionales
- [ ] **CHAT-FEAT-001**: Historial de mensajes (3h)
- [ ] **CHAT-FEAT-002**: Scroll automático a último mensaje (2h)
- [ ] **CHAT-FEAT-003**: Timestamp de mensajes (2h)

---

## FASE 11: TESTING Y OPTIMIZACIÓN (Semana 11) - 60 horas

### Testing Frontend
- [ ] **TEST-FE-001**: Tests unitarios componentes clave (8h)
- [ ] **TEST-FE-002**: Tests de integración páginas principales (6h)
- [ ] **TEST-FE-003**: Tests E2E con Cypress (flujo de compra) (6h)
- [ ] **TEST-FE-004**: Tests de accesibilidad (4h)

### Testing Backend
- [ ] **TEST-BE-001**: Aumentar cobertura de tests unitarios (6h)
- [ ] **TEST-BE-002**: Tests de integración completos (6h)
- [ ] **TEST-BE-003**: Tests de carga (stress testing) (5h)

### Optimización
- [ ] **OPT-001**: Optimizar queries de MongoDB (4h)
- [ ] **OPT-002**: Implementar caché con Redis (5h)
- [ ] **OPT-003**: Optimizar carga de imágenes (lazy loading) (3h)
- [ ] **OPT-004**: Code splitting en React (4h)
- [ ] **OPT-005**: Minificación y compresión de assets (3h)

---

## FASE 12: DEPLOYMENT Y DOCUMENTACIÓN (Semana 12-13) - 55 horas

### Deployment
- [ ] **DEPLOY-001**: Configurar Railway para backend (4h)
- [ ] **DEPLOY-002**: Configurar variables de entorno producción (2h)
- [ ] **DEPLOY-003**: Deploy del frontend en Vercel/Netlify (3h)
- [ ] **DEPLOY-004**: Configurar dominio personalizado (2h)
- [ ] **DEPLOY-005**: Configurar SSL/HTTPS (2h)
- [ ] **DEPLOY-006**: Setup de MongoDB Atlas producción (3h)
- [ ] **DEPLOY-007**: Configurar Cloudinary producción (2h)
- [ ] **DEPLOY-008**: Configurar backups automáticos (3h)

### Monitoreo
- [ ] **MONITOR-001**: Configurar logs de errores (3h)
- [ ] **MONITOR-002**: Implementar health checks (2h)
- [ ] **MONITOR-003**: Setup de alertas (2h)

### Documentación Final
- [ ] **DOC-FINAL-001**: Documentación de API completa (5h)
- [ ] **DOC-FINAL-002**: Manual de usuario del panel admin (4h)
- [ ] **DOC-FINAL-003**: Guía de deployment (3h)
- [ ] **DOC-FINAL-004**: Documentación técnica del código (4h)
- [ ] **DOC-FINAL-005**: Video tutorial de capacitación (3h)

### Entrega
- [ ] **DELIVERY-001**: Revisión final de calidad (3h)
- [ ] **DELIVERY-002**: Sesión de capacitación con cliente (2h)
- [ ] **DELIVERY-003**: Transferencia de credenciales (1h)
- [ ] **DELIVERY-004**: Entrega de documentación (1h)

---

## RESUMEN DE HORAS POR FASE

| Fase | Descripción | Horas |
|------|-------------|-------|
| 1 | Configuración Inicial | 31h |
| 2 | Backend - Autenticación | 70h |
| 3 | Backend - Productos | 73h |
| 4 | Backend - Pedidos y Pagos | 85h |
| 5 | Backend - Chat y Empleados | 95h |
| 6 | Frontend - Componentes Base | 75h |
| 7 | Frontend - E-commerce Público | 90h |
| 8 | Frontend - Checkout y Perfil | 75h |
| 9 | Frontend - Panel Admin | 95h |
| 10 | Frontend - Sistema de Chat | 55h |
| 11 | Testing y Optimización | 60h |
| 12 | Deployment y Documentación | 55h |
| **TOTAL** | | **~800h** |

---

## DISTRIBUCIÓN POR PERSONA (3 desarrolladores)

- **Total horas:** ~800h
- **Por persona:** ~267h
- **Duración:** 12-13 semanas
- **Horas/semana por persona:** ~21h

---

## PRIORIDADES

### 🔴 Crítico (MVP)
- Autenticación y usuarios
- CRUD de productos
- Carrito y checkout
- Integración de pagos
- Panel admin básico

### 🟡 Importante
- Sistema de chat
- Gestión de empleados
- Estadísticas del dashboard
- Búsqueda avanzada

### 🟢 Nice to Have
- Integración de mapas
- Newsletter
- Productos relacionados
- Exportación de datos

---

## NOTAS PARA GITHUB PROJECTS

- Usar **labels**: `backend`, `frontend`, `bug`, `feature`, `documentation`, `testing`
- Usar **milestones** para cada fase
- Asignar **story points** (1-5) según complejidad
- Crear **pull requests** vinculados a issues
- Requerir **code review** antes de merge