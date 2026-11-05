# 🏡 SIGUA Inmobiliaria — Plataforma Web & Panel de Control CRM VIP

Plataforma inmobiliaria integral desarrollada a la medida para **SIGUA Inmobiliaria** ([siguainmobiliaria.com](https://siguainmobiliaria.com/)), agencia líder con más de 17 años de experiencia y trayectoria en **Carretera a El Salvador**, Santa Catarina Pinula, Fraijanes, San José Pinula y Ciudad de Guatemala.

---

## 🌟 Componentes del Proyecto

### 1. Portal Web Público (`index.html`)
- **Diseño Luxury & Responsive:** Interfaz moderna y minimalista con arquitectura limpia, tipografía contemporánea y modo claro/oscuro.
- **Catálogo Exclusivo en Carretera a El Salvador:** Propiedades residenciales, condominios cerrados (Terravista, Arrazola, Arrazola Panorama, Campo Grande, Villas Bizantinas) y terrenos.
- **Mapa Interactivo (Leaflet):** Ubicación geográfica de cada inmueble con pines y fichas dinámicas.
- **Directorio del Equipo:** Fichas de los fundadores y directores (**Juan Carlos Aguirre**, **Marjorie Valdez de Aguirre**) y asesores seniors con acceso directo a WhatsApp.
- **Dock de Navegación Flotante:** Acceso rápido a mapa, catálogo, opiniones de clientes y acceso directo al **Panel CRM**.

### 2. Panel Ejecutivo CRM & Gestión Inmobiliaria (`panel.html`)
- **Estética Dark Luxury:** Acabado profesional en negro y grafito (`#0A0A0A`, `#0D0D0D`, `#141414`) con tipografías *Outfit*, *DM Sans* y *Montserrat*.
- **Dashboard Ejecutivo:**
  - Métricas clave en tiempo real: Total Portafolio, En Venta, En Renta, Vendidas (SOLD), Valor Total de Cartera y Asesores.
  - Gráfico Donut de composición comercial y barra segmentada interactiva.
  - Desglose territorial enfocado en Carretera a El Salvador, Fraijanes y Santa Catarina Pinula.
  - **Centro de Productividad:** Meta mensual de ventas con barra de avance, leads recientes con enlace directo a WhatsApp, checklist diario de tareas y bloc de notas privado con autoguardado en `localStorage`.
- **Gestión de Propiedades:**
  - Modo dual de visualización (Tabla ejecutiva y Tarjetas / Grid).
  - Alternador de disponibilidad en 1 clic (*Disponible* $\leftrightarrow$ *En Renta* $\leftrightarrow$ *Vendida*).
  - Buscador global y filtros rápidos por categoría y por asesor asignado.
  - Ficha modal de detalle de propiedad con galería, especificaciones y contacto directo del asesor vía WhatsApp.
  - Modales de edición, eliminación y formulario completo para registrar nuevas propiedades con compresión de fotos.
- **Directorio de Asesores:**
  - Perfiles de Juan Carlos Aguirre, Marjorie Valdez de Aguirre, Rodrigo Mendoza, Valeria Morales, Esteban Fuentes, Camila Samayoa y Alejandro Paz.
  - Métricas individuales de cartera, ventas cerradas y botón para filtrar el inventario por asesor.
- **Calendario & Visitas VIP:**
  - Agenda mensual y semanal de citas a propiedades.
  - Programación de recorridos y exportación a formato estándar `.ICS` compatible con Google Calendar, Apple Calendar y Outlook.
- **Sincronización con Google Sheets:**
  - Conexión con hojas de cálculo públicas en Google Sheets (formato CSV).
  - Previsualización de datos en tabla embebida y exportador descargable a CSV.
- **Configuración & Personalización Multi-Inmobiliaria:**
  - Panel de control de marca, eslogan, moneda (USD $, GTQ Q, MXN $, EUR €), teléfonos, comisiones y logotipos con actualización reactiva en vivo.

### 3. Autenticación y Seguridad RBAC (`auth.js` & `login.html`)
- Módulo de autenticación con criptografía PBKDF2.
- Protección contra ataques de fuerza bruta y monitor de inactividad.
- Acceso directo sin fricción como Administrador para pruebas inmediatas.

---

## 📞 Datos de Contacto Oficiales de SIGUA Inmobiliaria
- **Ubicación:** Km 15.8 Carretera a El Salvador, Finca San José, Lote 9 Apto 9, Santa Catarina Pinula, Guatemala.
- **Teléfonos / WhatsApp:** +502 5651-3625 / +502 5632-5705
- **Correo Electrónico:** [siguainmobiliaria@gmail.com](mailto:siguainmobiliaria@gmail.com)
- **Sitio Web Oficial:** [https://siguainmobiliaria.com/](https://siguainmobiliaria.com/)

---

## 💻 Ejecución Local
1. Clona el repositorio o abre la carpeta en tu editor preferido (VS Code).
2. Abre [index.html](index.html) para explorar el portal web público.
3. Abre [panel.html](panel.html) para ingresar directamente al panel CRM como Administrador General.
