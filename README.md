# TAREAS DEL PROYECTO SPROC - E-COMMERCE MERN

## FASE 1: CONFIGURACIÓN INICIAL (Semanas 1-2) - 45 horas totales

### Setup del Proyecto
- [ ] **SETUP-001**: Inicializar repositorio Git y estructura de carpetas (2h)
- [ ] **SETUP-002**: Configurar MongoDB Atlas y base de datos (3h)
- [ ] **SETUP-003**: Setup inicial del backend con Express.js (4h)
- [ ] **SETUP-004**: Setup inicial del frontend con React + Vite (4h)
- [ ] **SETUP-005**: Configurar variables de entorno (.env) (2h)

### Diseño y Arquitectura
- [ ] **DESIGN-001**: Crear mockups en Figma - Página principal (5h)
- [ ] **DESIGN-002**: Crear mockups en Figma - Panel admin (5h)
- [ ] **DESIGN-003**: Diseñar esquemas de base de datos (4h)
- [ ] **DESIGN-004**: Definir estructura de API REST (3h)
- [ ] **DESIGN-005**: Documentar arquitectura del sistema (3h)

### Documentación Inicial
- [ ] **DOC-001**: Crear README.md principal (2h)
- [ ] **DOC-002**: Documentar guía de instalación (2h)
- [ ] **DOC-003**: Crear CONTRIBUTING.md (2h)
- [ ] **DOC-004**: Documentar convenciones de código (2h)
- [ ] **DOC-005**: Setup de ESLint y Prettier (2h)

---

## FASE 2: BACKEND - AUTENTICACIÓN Y USUARIOS (Semanas 3-4) - 75 horas

### Modelos de Datos
- [ ] **MODEL-001**: Crear modelo de Usuario (User) (4h)
- [ ] **MODEL-002**: Crear modelo de Rol (Role) (3h)
- [ ] **MODEL-003**: Crear modelo de Sesión (Session) (2h)
- [ ] **MODEL-004**: Implementar validaciones de modelos (3h)

### Autenticación
- [ ] **AUTH-001**: Implementar registro de usuarios (6h)
- [ ] **AUTH-002**: Implementar login con JWT (6h)
- [ ] **AUTH-003**: Implementar logout (2h)
- [ ] **AUTH-004**: Crear middleware de autenticación (4h)
- [ ] **AUTH-005**: Implementar hash de contraseñas con bcrypt (3h)
- [ ] **AUTH-006**: Crear endpoint para recuperar contraseña (5h)
- [ ] **AUTH-007**: Implementar refresh tokens (5h)

### Sistema de Roles y Permisos
- [ ] **ROLE-001**: Crear middleware de autorización por roles (5h)
- [ ] **ROLE-002**: Definir permisos para Admin (3h)
- [ ] **ROLE-003**: Definir permisos para Empleado (3h)
- [ ] **ROLE-004**: Definir permisos para Cliente (3h)
- [ ] **ROLE-005**: Implementar verificación de permisos (4h)

### API de Usuarios
- [ ] **USER-API-001**: Endpoint GET /api/users (obtener usuarios) (4h)
- [ ] **USER-API-002**: Endpoint GET /api/users/:id (obtener usuario por ID) (3h)
- [ ] **USER-API-003**: Endpoint PUT /api/users/:id (actualizar usuario) (4h)
- [ ] **USER-API-004**: Endpoint DELETE /api/users/:id (eliminar usuario) (3h)
- [ ] **USER-API-005**: Endpoint GET /api/users/profile (perfil actual) (3h)

### Testing
- [ ] **TEST-AUTH-001**: Tests unitarios para autenticación (5h)
- [ ] **TEST-AUTH-002**: Tests de integración para usuarios (4h)

---

## FASE 3: BACKEND - PRODUCTOS Y CATEGORÍAS (Semanas 5-6) - 85 horas

### Modelos
- [ ] **MODEL-005**: Crear modelo de Producto (Product) (5h)
- [ ] **MODEL-006**: Crear modelo de Categoría (Category) (4h)
- [ ] **MODEL-007**: Crear modelo de Marca (Brand) (3h)
- [ ] **MODEL-008**: Crear modelo de Imagen (ProductImage) (3h)

### API de Productos
- [ ] **PROD-API-001**: Endpoint POST /api/products (crear producto) (6h)
- [ ] **PROD-API-002**: Endpoint GET /api/products (listar con paginación) (6h)
- [ ] **PROD-API-003**: Endpoint GET /api/products/:id (detalle producto) (4h)
- [ ] **PROD-API-004**: Endpoint PUT /api/products/:id (actualizar) (5h)
- [ ] **PROD-API-005**: Endpoint DELETE /api/products/:id (eliminar) (4h)
- [ ] **PROD-API-006**: Endpoint GET /api/products/search (búsqueda) (6h)
- [ ] **PROD-API-007**: Endpoint GET /api/products/filter (filtros avanzados) (7h)

### API de Categorías
- [ ] **CAT-API-001**: Endpoint POST /api/categories (crear categoría) (4h)
- [ ] **CAT-API-002**: Endpoint GET /api/categories (listar) (3h)
- [ ] **CAT-API-003**: Endpoint PUT /api/categories/:id (actualizar) (3h)
- [ ] **CAT-API-004**: Endpoint DELETE /api/categories/:id (eliminar) (3h)
- [ ] **CAT-API-005**: Implementar subcategorías (5h)

### Gestión de Imágenes
- [ ] **IMG-001**: Configurar Cloudinary para almacenamiento (4h)
- [ ] **IMG-002**: Endpoint POST /api/upload (subir imágenes) (5h)
- [ ] **IMG-003**: Implementar compresión de imágenes (4h)
- [ ] **IMG-004**: Endpoint DELETE /api/upload/:id (eliminar imagen) (3h)
- [ ] **IMG-005**: Galería múltiple de imágenes por producto (5h)

### Testing
- [ ] **TEST-PROD-001**: Tests para CRUD de productos (6h)
- [ ] **TEST-PROD-002**: Tests para búsqueda y filtros (5h)

---

## FASE 4: BACKEND - PEDIDOS Y PAGOS (Semanas 7-8) - 90 horas

### Modelos
- [ ] **MODEL-009**: Crear modelo de Pedido (Order) (5h)
- [ ] **MODEL-010**: Crear modelo de ItemPedido (OrderItem) (4h)
- [ ] **MODEL-011**: Crear modelo de CarritoCompra (Cart) (4h)
- [ ] **MODEL-012**: Crear modelo de Pago (Payment) (4h)

### API de Carrito
- [ ] **CART-API-001**: Endpoint POST /api/cart/add (agregar producto) (5h)
- [ ] **CART-API-002**: Endpoint GET /api/cart (obtener carrito) (4h)
- [ ] **CART-API-003**: Endpoint PUT /api/cart/:itemId (actualizar cantidad) (4h)
- [ ] **CART-API-004**: Endpoint DELETE /api/cart/:itemId (eliminar item) (3h)
- [ ] **CART-API-005**: Endpoint DELETE /api/cart (vaciar carrito) (2h)

### API de Pedidos
- [ ] **ORDER-API-001**: Endpoint POST /api/orders (crear pedido) (7h)
- [ ] **ORDER-API-002**: Endpoint GET /api/orders (listar pedidos) (5h)
- [ ] **ORDER-API-003**: Endpoint GET /api/orders/:id (detalle pedido) (4h)
- [ ] **ORDER-API-004**: Endpoint PUT /api/orders/:id/status (actualizar estado) (5h)
- [ ] **ORDER-API-005**: Endpoint GET /api/orders/user/:userId (pedidos por usuario) (4h)

### Integración Wompi
- [ ] **PAYMENT-001**: Configurar credenciales de Wompi (3h)
- [ ] **PAYMENT-002**: Endpoint POST /api/payments/create (iniciar pago) (8h)
- [ ] **PAYMENT-003**: Webhook para confirmación de pago (7h)
- [ ] **PAYMENT-004**: Endpoint GET /api/payments/:id (estado de pago) (4h)
- [ ] **PAYMENT-005**: Manejo de errores de pago (5h)
- [ ] **PAYMENT-006**: Implementar reembolsos (6h)

### Notificaciones
- [ ] **NOTIF-001**: Configurar servicio de email (Nodemailer) (4h)
- [ ] **NOTIF-002**: Template email confirmación de pedido (3h)
- [ ] **NOTIF-003**: Notificación de cambio de estado (3h)

### Testing
- [ ] **TEST-ORDER-001**: Tests para carrito de compras (5h)
- [ ] **TEST-ORDER-002**: Tests para pedidos (5h)

---

## FASE 5: BACKEND - CHAT Y EMPLEADOS (Semanas 9-10) - 100 horas

### Sistema de Chat
- [ ] **CHAT-001**: Configurar Socket.io en el servidor (5h)
- [ ] **CHAT-002**: Crear modelo de Conversación (Conversation) (4h)
- [ ] **CHAT-003**: Crear modelo de Mensaje (Message) (4h)
- [ ] **CHAT-004**: Evento 'send_message' (enviar mensaje) (6h)
- [ ] **CHAT-005**: Evento 'join_conversation' (unirse a conversación) (4h)
- [ ] **CHAT-006**: Evento 'typing' (indicador escribiendo) (3h)
- [ ] **CHAT-007**: Evento 'message_read' (marcar como leído) (4h)
- [ ] **CHAT-008**: Endpoint GET /api/conversations (listar conversaciones) (5h)
- [ ] **CHAT-009**: Endpoint GET /api/conversations/:id/messages (mensajes) (5h)
- [ ] **CHAT-010**: Sistema de notificaciones en tiempo real (6h)
- [ ] **CHAT-011**: Almacenar historial en MongoDB (5h)

### API de Empleados
- [ ] **EMP-API-001**: Endpoint POST /api/employees (crear empleado) (5h)
- [ ] **EMP-API-002**: Endpoint GET /api/employees (listar empleados) (4h)
- [ ] **EMP-API-003**: Endpoint PUT /api/employees/:id (actualizar) (4h)
- [ ] **EMP-API-004**: Endpoint DELETE /api/employees/:id (eliminar) (4h)
- [ ] **EMP-API-005**: Endpoint PUT /api/employees/:id/role (cambiar rol) (4h)
- [ ] **EMP-API-006**: Endpoint GET /api/employees/:id/activity (logs de actividad) (5h)

### Integración con Mapas
- [ ] **MAP-001**: Configurar API de Google Maps (3h)
- [ ] **MAP-002**: Endpoint GET /api/locations (sucursales) (4h)
- [ ] **MAP-003**: Implementar geocodificación de direcciones (5h)

### Dashboard Estadísticas
- [ ] **STATS-001**: Endpoint GET /api/stats/sales (estadísticas ventas) (6h)
- [ ] **STATS-002**: Endpoint GET /api/stats/products (productos más vendidos) (5h)
- [ ] **STATS-003**: Endpoint GET /api/stats/users (nuevos usuarios) (4h)
- [ ] **STATS-004**: Endpoint GET /api/stats/revenue (ingresos) (5h)

### Testing
- [ ] **TEST-CHAT-001**: Tests para sistema de chat (6h)
- [ ] **TEST-EMP-001**: Tests para gestión de empleados (4h)

---

## FASE 6: FRONTEND - COMPONENTES BASE (Semanas 3-4) - 75 horas

### Configuración
- [ ] **FE-SETUP-001**: Configurar React Router (3h)
- [ ] **FE-SETUP-002**: Configurar Axios para API (3h)
- [ ] **FE-SETUP-003**: Configurar Context API / Redux (5h)
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

## FASE 7: FRONTEND - E-COMMERCE PÚBLICO (Semanas 5-6) - 95 horas

### Página Principal
- [ ] **HOME-001**: Hero section con banner principal (5h)
- [ ] **HOME-002**: Sección de categorías destacadas (4h)
- [ ] **HOME-003**: Sección "Lo más reciente" (4h)
- [ ] **HOME-004**: Sección de promociones (4h)
- [ ] **HOME-005**: Cards informativas (envío, garantía, pago) (3h)
- [ ] **HOME-006**: Newsletter signup (3h)

### Catálogo de Productos
- [ ] **CATALOG-001**: Página de listado de productos (6h)
- [ ] **CATALOG-002**: Implementar filtros laterales (7h)
- [ ] **CATALOG-003**: Implementar ordenamiento (4h)
- [ ] **CATALOG-004**: Grid responsive de productos (5h)
- [ ] **CATALOG-005**: Componente ProductCard (4h)
- [ ] **CATALOG-006**: Paginación de resultados (4h)

### Detalle de Producto
- [ ] **DETAIL-001**: Página de detalle de producto (6h)
- [ ] **DETAIL-002**: Galería de imágenes con zoom (6h)
- [ ] **DETAIL-003**: Selector de cantidad (3h)
- [ ] **DETAIL-004**: Botón "Agregar al carrito" (4h)
- [ ] **DETAIL-005**: Sección de información del producto (4h)
- [ ] **DETAIL-006**: Productos relacionados (5h)

### Buscador
- [ ] **SEARCH-001**: Barra de búsqueda global (5h)
- [ ] **SEARCH-002**: Página de resultados de búsqueda (5h)
- [ ] **SEARCH-003**: Autocompletado de búsqueda (6h)
- [ ] **SEARCH-004**: Búsqueda por categoría (4h)

### Carrito de Compras
- [ ] **CART-001**: Componente de carrito (dropdown) (5h)
- [ ] **CART-002**: Página completa del carrito (6h)
- [ ] **CART-003**: Actualizar cantidad de productos (4h)
- [ ] **CART-004**: Eliminar productos del carrito (3h)
- [ ] **CART-005**: Cálculo de totales (3h)

---

## FASE 8: FRONTEND - CHECKOUT Y PERFIL (Semanas 7-8) - 80 horas

### Proceso de Checkout
- [ ] **CHECKOUT-001**: Página de checkout - Paso 1: Información (6h)
- [ ] **CHECKOUT-002**: Formulario de dirección de envío (5h)
- [ ] **CHECKOUT-003**: Página de checkout - Paso 2: Método de pago (6h)
- [ ] **CHECKOUT-004**: Integración con Wompi frontend (8h)
- [ ] **CHECKOUT-005**: Página de checkout - Paso 3: Resumen (5h)
- [ ] **CHECKOUT-006**: Página de confirmación de pedido (5h)
- [ ] **CHECKOUT-007**: Manejo de errores de pago (4h)

### Perfil de Usuario
- [ ] **PROFILE-001**: Página de perfil de usuario (6h)
- [ ] **PROFILE-002**: Editar información personal (5h)
- [ ] **PROFILE-003**: Cambiar contraseña (4h)
- [ ] **PROFILE-004**: Historial de pedidos (6h)
- [ ] **PROFILE-005**: Detalle de pedido individual (5h)
- [ ] **PROFILE-006**: Direcciones guardadas (5h)

### Integración de Mapas
- [ ] **MAP-FE-001**: Componente de mapa con Google Maps (6h)
- [ ] **MAP-FE-002**: Página de ubicaciones/sucursales (5h)
- [ ] **MAP-FE-003**: Selector de dirección en mapa (5h)

### Responsive Design
- [ ] **RESP-001**: Optimizar home para móvil (4h)
- [ ] **RESP-002**: Optimizar catálogo para móvil (4h)
- [ ] **RESP-003**: Optimizar checkout para móvil (4h)

---

## FASE 9: FRONTEND - PANEL ADMINISTRATIVO (Semanas 9-10) - 110 horas

### Dashboard
- [ ] **ADMIN-DASH-001**: Dashboard principal con estadísticas (8h)
- [ ] **ADMIN-DASH-002**: Gráficos de ventas (Chart.js) (6h)
- [ ] **ADMIN-DASH-003**: Widget de productos más vendidos (5h)
- [ ] **ADMIN-DASH-004**: Widget de usuarios nuevos (4h)
- [ ] **ADMIN-DASH-005**: Lista de pedidos pendientes (5h)
- [ ] **ADMIN-DASH-006**: Indicadores de rendimiento (KPIs) (5h)

### Gestión de Productos
- [ ] **ADMIN-PROD-001**: Página de lista de productos (6h)
- [ ] **ADMIN-PROD-002**: Formulario crear producto (8h)
- [ ] **ADMIN-PROD-003**: Formulario editar producto (6h)
- [ ] **ADMIN-PROD-004**: Subir múltiples imágenes (6h)
- [ ] **ADMIN-PROD-005**: Eliminar producto con confirmación (3h)
- [ ] **ADMIN-PROD-006**: Búsqueda y filtros en admin (5h)
- [ ] **ADMIN-PROD-007**: Gestión de categorías (5h)

### Gestión de Pedidos
- [ ] **ADMIN-ORDER-001**: Lista de todos los pedidos (6h)
- [ ] **ADMIN-ORDER-002**: Detalle de pedido (5h)
- [ ] **ADMIN-ORDER-003**: Actualizar estado de pedido (5h)
- [ ] **ADMIN-ORDER-004**: Filtros por estado/fecha (5h)
- [ ] **ADMIN-ORDER-005**: Exportar pedidos a CSV (4h)
- [ ] **ADMIN-ORDER-006**: Modal de edición de pedido (4h)

### Gestión de Empleados
- [ ] **ADMIN-EMP-001**: Lista de empleados (5h)
- [ ] **ADMIN-EMP-002**: Formulario crear empleado (5h)
- [ ] **ADMIN-EMP-003**: Editar empleado (4h)
- [ ] **ADMIN-EMP-004**: Eliminar empleado (3h)
- [ ] **ADMIN-EMP-005**: Asignar/cambiar roles (4h)

### Editor de Promociones
- [ ] **ADMIN-PROMO-001**: Página de gestión de banners (5h)
- [ ] **ADMIN-PROMO-002**: Subir imagen de banner (4h)
- [ ] **ADMIN-PROMO-003**: Editar texto y enlaces del banner (4h)
- [ ] **ADMIN-PROMO-004**: Programar fechas de promoción (5h)

---

## FASE 10: FRONTEND - SISTEMA DE CHAT (Semanas 9-10) - 60 horas

### Configuración Socket.io
- [ ] **CHAT-FE-001**: Configurar cliente de Socket.io (4h)
- [ ] **CHAT-FE-002**: Crear contexto de chat (4h)
- [ ] **CHAT-FE-003**: Manejo de conexión/desconexión (3h)

### Chat para Clientes
- [ ] **CHAT-CLIENT-001**: Botón flotante de chat (4h)
- [ ] **CHAT-CLIENT-002**: Ventana de chat (widget) (8h)
- [ ] **CHAT-CLIENT-003**: Input de mensaje (3h)
- [ ] **CHAT-CLIENT-004**: Lista de mensajes (5h)
- [ ] **CHAT-CLIENT-005**: Indicador "escribiendo..." (3h)
- [ ] **CHAT-CLIENT-006**: Notificaciones de mensaje nuevo (4h)

### Chat para Admin
- [ ] **CHAT-ADMIN-001**: Página de conversaciones (6h)
- [ ] **CHAT-ADMIN-002**: Lista de conversaciones activas (5h)
- [ ] **CHAT-ADMIN-003**: Ventana de chat completa (6h)
- [ ] **CHAT-ADMIN-004**: Marcar mensajes como leídos (3h)
- [ ] **CHAT-ADMIN-005**: Badge de mensajes no leídos (3h)

### Funcionalidades Adicionales
- [ ] **CHAT-FEAT-001**: Historial de mensajes (4h)
- [ ] **CHAT-FEAT-002**: Scroll automático a último mensaje (2h)
- [ ] **CHAT-FEAT-003**: Timestamp de mensajes (2h)

---

## FASE 11: TESTING Y OPTIMIZACIÓN (Semana 11) - 75 horas

### Testing Frontend
- [ ] **TEST-FE-001**: Tests unitarios componentes clave (10h)
- [ ] **TEST-FE-002**: Tests de integración páginas principales (8h)
- [ ] **TEST-FE-003**: Tests E2E con Cypress (flujo de compra) (8h)
- [ ] **TEST-FE-004**: Tests de accesibilidad (5h)

### Testing Backend
- [ ] **TEST-BE-001**: Aumentar cobertura de tests unitarios (8h)
- [ ] **TEST-BE-002**: Tests de integración completos (8h)
- [ ] **TEST-BE-003**: Tests de carga (stress testing) (6h)

### Optimización
- [ ] **OPT-001**: Optimizar queries de MongoDB (5h)
- [ ] **OPT-002**: Implementar caché con Redis (6h)
- [ ] **OPT-003**: Optimizar carga de imágenes (lazy loading) (4h)
- [ ] **OPT-004**: Code splitting en React (4h)
- [ ] **OPT-005**: Minificación y compresión de assets (3h)

---

## FASE 12: DEPLOYMENT Y DOCUMENTACIÓN (Semana 12-13) - 60 horas

### Deployment
- [ ] **DEPLOY-001**: Configurar Railway para backend (5h)
- [ ] **DEPLOY-002**: Configurar variables de entorno producción (3h)
- [ ] **DEPLOY-003**: Deploy del frontend en Vercel/Netlify (4h)
- [ ] **DEPLOY-004**: Configurar dominio personalizado (3h)
- [ ] **DEPLOY-005**: Configurar SSL/HTTPS (2h)
- [ ] **DEPLOY-006**: Setup de MongoDB Atlas producción (3h)
- [ ] **DEPLOY-007**: Configurar Cloudinary producción (2h)
- [ ] **DEPLOY-008**: Configurar backups automáticos (4h)

### Monitoreo
- [ ] **MONITOR-001**: Configurar logs de errores (4h)
- [ ] **MONITOR-002**: Implementar health checks (3h)
- [ ] **MONITOR-003**: Setup de alertas (3h)

### Documentación Final
- [ ] **DOC-FINAL-001**: Documentación de API completa (6h)
- [ ] **DOC-FINAL-002**: Manual de usuario del panel admin (5h)
- [ ] **DOC-FINAL-003**: Guía de deployment (4h)
- [ ] **DOC-FINAL-004**: Documentación técnica del código (5h)
- [ ] **DOC-FINAL-005**: Video tutorial de capacitación (4h)

### Entrega
- [ ] **DELIVERY-001**: Revisión final de calidad (4h)
- [ ] **DELIVERY-002**: Sesión de capacitación con cliente (2h)
- [ ] **DELIVERY-003**: Transferencia de credenciales (2h)
- [ ] **DELIVERY-004**: Entrega de documentación (2h)

---

## RESUMEN DE HORAS POR FASE

| Fase | Descripción | Horas |
|------|-------------|-------|
| 1 | Configuración Inicial | 45h |
| 2 | Backend - Autenticación | 75h |
| 3 | Backend - Productos | 85h |
| 4 | Backend - Pedidos y Pagos | 90h |
| 5 | Backend - Chat y Empleados | 100h |
| 6 | Frontend - Componentes Base | 75h |
| 7 | Frontend - E-commerce Público | 95h |
| 8 | Frontend - Checkout y Perfil | 80h |
| 9 | Frontend - Panel Admin | 110h |
| 10 | Frontend - Sistema de Chat | 60h |
| 11 | Testing y Optimización | 75h |
| 12 | Deployment y Documentación | 60h |
| **TOTAL** | | **950h** |

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
