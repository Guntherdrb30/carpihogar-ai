# Carpihogar.com

**La tienda inteligente de Venezuela para muebles, carpinteria, diseno de interiores y comercio omnicanal.**

[carpihogar.com](https://carpihogar.com) es una plataforma de e-commerce, ERP operativo e inteligencia artificial construida para la industria del hogar, mobiliario, carpinteria y diseno de interiores en Venezuela. El sistema combina tienda online, backoffice administrativo, inventario, ventas, compras, delivery, aliados comerciales, inversionistas, proyectos de diseno, marketing con IA e integraciones reales con OpenAI, Meta, WhatsApp y Vercel.

Este repositorio corresponde a una plataforma funcional orientada a produccion, no a una demo aislada. El objetivo del proyecto es demostrar que una empresa tradicional de muebles puede operar con una infraestructura digital propia, escalable y preparada para convertirse en un producto SaaS white-label para otras empresas de Latinoamerica.

---

## Resumen para concurso

Carpihogar.com es un ecosistema de comercio inteligente que digitaliza el ciclo completo de venta de muebles y productos para el hogar: descubrimiento, asesoramiento, cotizacion, checkout, pago, inventario, despacho, postventa, reportes y marketing. La plataforma une una experiencia de tienda moderna con un ERP interno y agentes de IA capaces de apoyar ventas, reportes, marketing, catalogos, manuales y atencion al cliente.

El proyecto fue construido con Next.js, React, TypeScript, Prisma, PostgreSQL, Vercel, OpenAI, Meta Graph API y WhatsApp Cloud API. Incluye modulos de e-commerce, POS, inventario, compras, contabilidad, delivery, aliados, inversionistas, PWA, notificaciones, configuradores visuales, moodboards, diseno de cocinas, personalizacion 3D y dashboards por rol.

La propuesta diferencial es que Carpihogar no solo vende productos online: organiza la operacion completa de una empresa real, conecta actores comerciales externos y usa IA para mejorar decisiones, automatizar marketing y aumentar la eficiencia operativa.

---

## Resumen para inversionistas

Carpihogar.com es una plataforma vertical de comercio y gestion empresarial para el sector hogar. A diferencia de una tienda online tradicional, integra en un solo sistema los procesos que normalmente viven separados: catalogo, inventario, presupuestos, compras, ventas, pagos, contabilidad, delivery, aliados, inversionistas, proyectos de diseno y marketing digital.

La vision del producto es convertir la operacion de Carpihogar en la base tecnologica de **LUNA by Trends172Tech**, un sistema SaaS/ERP white-label que pueda implementarse en otras empresas cambiando marca, colores, modulos, configuracion comercial y permisos desde un panel administrativo.

El valor del proyecto esta en tres capas:

1. **Operacion real:** resuelve necesidades diarias de una empresa que vende productos fisicos, gestiona inventario, coordina entregas y atiende clientes.
2. **Escalabilidad comercial:** permite incorporar aliados, inversionistas, gestores de marca, repartidores y equipos internos sin perder control administrativo.
3. **IA aplicada al negocio:** usa modelos de OpenAI y agentes internos para marketing, reportes, catalogos, asistentes, analisis y automatizacion de flujos.

---

## Problema

Las empresas de muebles, ferreteria, carpinteria y hogar en Latinoamerica suelen operar con procesos fragmentados:

- catalogos manuales en redes sociales;
- inventarios separados por hojas de calculo;
- ventas por WhatsApp sin trazabilidad;
- pagos manuales sin conciliacion clara;
- delivery coordinado por mensajes;
- comisiones calculadas a mano;
- falta de reportes comerciales confiables;
- dependencia de marketplaces externos;
- poco uso real de IA en procesos operativos.

Esto limita el crecimiento, reduce la confianza del cliente, hace dificil controlar margenes y complica abrir nuevos canales de venta.

---

## Solucion

Carpihogar centraliza el flujo comercial y operativo en una sola plataforma:

- tienda online con catalogo, busqueda, carrito y checkout;
- backoffice con ventas, inventario, compras, proveedores y reportes;
- dashboards por rol para administradores, vendedores, aliados, clientes, delivery, arquitectos, gestores de marca e inversionistas;
- IA para marketing, recomendaciones, reportes, asistentes y generacion de contenido;
- integracion con WhatsApp Cloud API para mensajeria operativa;
- integracion con Meta Graph API para marketing, catalogos y campanas;
- PWA con notificaciones push;
- herramientas visuales como moodboard, diseno de cocinas y personalizacion 3D;
- estructura preparada para evolucionar a SaaS white-label.

---

## Estado del proyecto

| Area | Estado |
|---|---|
| Tienda publica | Implementada |
| Catalogo y productos | Implementado |
| Carrito y checkout | Implementado |
| Backoffice administrativo | Implementado |
| Roles y permisos | Implementado |
| Prisma + PostgreSQL | Implementado |
| NextAuth + Google OAuth | Implementado |
| Vercel deployment | Configurado |
| Vercel Blob | Integrado |
| OpenAI API | Integrada |
| Meta / WhatsApp Cloud API | Integrada |
| PWA y Web Push | Implementado |
| Delivery y tracking | Implementado |
| Inventario, compras y reportes | Implementado |
| Aliados e inversionistas | Implementado |
| Marketing IA | Implementado en fases |
| Moodboard / cocinas / 3D | Implementado |
| SaaS white-label | En evolucion sobre la base actual |

---

## Built with

TypeScript, JavaScript, SQL, CSS, Next.js, React, React Server Components, Next.js App Router, Server Actions, API Routes, Tailwind CSS, HeroUI, Prisma ORM, PostgreSQL, Neon, NextAuth.js, Google OAuth, Credentials Auth, JWT Sessions, bcrypt, Zod, Zustand, Vercel, Vercel Blob, Vercel Cron, Vercel Web Analytics, OpenAI API, OpenAI Agents SDK, OpenAI Responses API, OpenAI Chat Completions, OpenAI Image Edits, Meta Graph API, Meta Ads API, Meta Pixel, WhatsApp Cloud API, Cloudflare Turnstile, Web Push, PWA, Nodemailer, SMTP, Three.js, React Three Fiber, Drei, Leaflet, Recharts, Framer Motion, Sharp, PDFKit, pdf-parse, QRCode, XLSX, Swiper, E-commerce, ERP, Inventory Management, POS, Checkout, Order Management, Quotes, Procurement, Accounting, Receivables, Payables, Delivery Tracking, Investor Portal, Ally Portal, Role-Based Access Control, Modular Monolith, Serverless Architecture, Webhooks, Cron Jobs, Audit Logging, AI Assistant, AI Marketing, Product Catalog, Moodboard, 3D Furniture Configurator, Vercel Deployment

---

## Stack tecnologico

| Capa | Tecnologia |
|---|---|
| Framework principal | Next.js 15 con App Router |
| Frontend | React 19, TypeScript, Tailwind CSS, HeroUI |
| Backend | Next.js Route Handlers, Server Actions, servicios en `server/` y `lib/` |
| Base de datos | PostgreSQL |
| Plataforma de base de datos | Neon |
| ORM | Prisma 6 |
| Autenticacion | NextAuth 4, credenciales, Google OAuth, sesiones JWT |
| Seguridad | bcrypt, Cloudflare Turnstile, headers de seguridad, audit logs, validaciones por rol |
| Storage | Vercel Blob y almacenamiento local de assets publicos |
| Deploy | Vercel |
| Jobs programados | Vercel Cron |
| IA | OpenAI API, Responses API, Chat Completions, Image Edits, `@openai/agents` |
| Marketing | Meta Graph API, Meta Ads, Meta Pixel |
| Mensajeria | WhatsApp Cloud API, webhooks, outbox y plantillas |
| Email | Nodemailer SMTP |
| PWA | Manifest, service worker, Web Push VAPID |
| 3D | Three.js, React Three Fiber, Drei |
| Mapas | Leaflet |
| Reportes | Recharts, PDFKit, XLSX, CSV |
| Imagenes | Sharp, optimizador interno, Vercel Blob |
| Estado cliente | Zustand |
| Validacion | Zod y validaciones internas |

---

## Arquitectura

La aplicacion sigue una arquitectura modular sobre Next.js App Router:

```text
app/
  Rutas publicas, dashboards por rol y API routes

components/
  Componentes reutilizables de UI, tienda, dashboards, asistentes y modulos

server/
  Logica de negocio, acciones de dominio, integraciones, servicios y orquestadores

lib/
  Utilidades compartidas: auth, prisma, OpenAI, WhatsApp, seguridad, reportes, pricing

prisma/
  Schema, migraciones, seeds y scripts de base de datos

agents/
  Definiciones y herramientas para agentes IA y MCP

public/
  Assets publicos, PWA, uploads y recursos optimizados

docs/
  Documentacion tecnica y funcional por modulo
```

Patrones usados:

- **Modular monolith:** un solo repositorio con dominios de negocio separados por carpetas.
- **Server-first architecture:** operaciones criticas en Server Actions y Route Handlers.
- **Role-based access control:** dashboards y acciones protegidas segun rol.
- **Service layer:** integraciones y reglas de negocio centralizadas en `server/` y `lib/`.
- **Event and audit logging:** eventos criticos registrados para seguridad y trazabilidad.
- **Serverless deployment:** preparado para Vercel Functions, Vercel Cron y Neon.
- **API-first integrations:** integraciones externas encapsuladas en servicios propios.

---

## Modelo de roles

El sistema contempla multiples perfiles reales de operacion:

| Rol | Uso principal |
|---|---|
| Cliente | Compra, pedidos, favoritos, direcciones y seguimiento |
| Admin | Operacion general, productos, ventas, reportes y configuracion |
| Vendedor | Ventas, pedidos, cotizaciones y atencion comercial |
| Aliado | Promocion, comisiones, mini tienda y presupuestos |
| Delivery | Entregas, evidencias, tracking y ganancias |
| Despacho / Logistica | Coordinacion de envios y estados |
| Arquitecto | Proyectos de diseno, renders, tareas y seguimiento |
| Supervisor de proyectos | Control de avance de diseno y produccion |
| Inversionista | Inventario asignado, ventas, finanzas y retiros |
| Gestor de marcas | Gestion de marcas, productos, comisiones y solicitudes |

---

## Modulos principales

### Tienda publica

- Home comercial con productos destacados y descubrimiento inteligente.
- Catalogo con categorias, marcas, busqueda y filtros.
- Detalle de producto con galeria, precios, disponibilidad y acciones.
- Carrito de compras.
- Checkout con flujo de ordenes y confirmacion.
- Productos nuevos, mas vendidos y relacionados.
- Mini-tiendas para aliados.
- Cursos y novedades.
- Politicas legales, cookies y privacidad.

### Backoffice administrativo

- Dashboard administrativo.
- Gestion de productos, categorias y marcas.
- Ventas, pedidos y documentos imprimibles.
- Caja / POS para ventas presenciales.
- Presupuestos y conversion a venta.
- Promociones y campanas.
- Comisiones de vendedores y aliados.
- Gestion de usuarios y roles.
- Configuracion del sistema.
- Seguridad, auditoria y diagnosticos.

### Inventario y compras

- Stock por producto.
- Movimientos de inventario.
- Alertas de bajo stock.
- Valuacion de inventario.
- Productos por proveedor.
- Compras y ordenes de compra.
- Recepcion de mercancia.
- Consumo interno.
- Reportes de inventario y proveedores.

### Finanzas y contabilidad

- Cuentas por cobrar.
- Cuentas por pagar.
- Bancos y configuracion de pagos.
- Caja y sesiones de POS.
- Balance general.
- Estado de resultados.
- Libro diario.
- Mayor general.
- Conciliacion bancaria.
- Tesoreria.
- Exportaciones CSV, PDF y Excel.

### Delivery y logistica

- Dashboard de delivery.
- Asignacion de pedidos.
- Tracking de envios.
- Evidencias de entrega.
- Estados de despacho.
- Ganancias de repartidores.
- Liquidaciones.
- Contratos y documentos PDF.
- Notificaciones por WhatsApp y push.
- Mapa de entregas con Leaflet.

### Aliados comerciales

- Portal de aliado.
- Mini tienda publica por aliado.
- Productos promovidos.
- Comisiones y retiros.
- Presupuestos para clientes.
- Perfil publico.
- Seguridad de cuenta.
- Ranking de aliados.
- Programa de referidos.

### Inversionistas

- Portal de inversionista.
- Inventario asignado.
- Ledger de ventas.
- Solicitudes de retiro.
- Solicitudes de pago.
- Reportes financieros.
- Control de entregas e integridad.
- Campanas Meta asociadas.
- Notificaciones push.

### Gestor de marcas

- Gestion de marcas asignadas.
- Solicitudes de marca, proveedor o inversion.
- Productos sometidos por gestor.
- Comisiones.
- Retiros.
- Dashboard especializado.

### Diseno, arquitectura y produccion

- Proyectos de diseno.
- Tareas y actualizaciones.
- Pagos por proyecto.
- Renders y archivos.
- Reportes PDF semanales.
- Cocinas y modulos.
- Configurador de espacios.
- Personalizacion de muebles.
- Moodboard interactivo.
- Archivos 3D y visualizacion con Three.js.

### Marketing IA

- Perfil de marca.
- Conexion con Meta.
- OAuth de Meta.
- Activos Meta persistidos.
- Borradores de campanas.
- Generacion de copy y estrategia con OpenAI.
- Publicaciones preparadas para Meta Ads.
- Sincronizacion de catalogo.
- Metricas de campanas.
- Actividad y trazabilidad.

### Mensajeria y WhatsApp

- Integracion con WhatsApp Cloud API.
- Webhook oficial de WhatsApp.
- Outbox de mensajes.
- Plantillas sincronizadas.
- Conversaciones.
- SLA y escalaciones.
- Envio de texto, media, audio y documentos.
- Clasificacion de mensajes con OpenAI.

### IA y agentes

- Asistente IA de tienda.
- Flujo de compra asistida.
- Voz a texto y texto a voz.
- Generacion de campanas.
- Reportes con IA.
- Catalogos asistidos.
- Manuales IA.
- Recomendaciones y prediccion.
- Herramientas MCP para acciones de negocio.

---

## Integraciones externas

| Integracion | Uso |
|---|---|
| OpenAI API | Asistentes, reportes, marketing, catalogos, clasificacion y generacion de contenido |
| OpenAI Agents SDK | Agentes y flujos de IA especializados |
| Meta Graph API | OAuth, activos de negocio, catalogo, campanas y metricas |
| Meta Ads API | Preparacion y publicacion de campanas |
| Meta Pixel | Tracking de eventos comerciales |
| WhatsApp Cloud API | Mensajeria, plantillas, soporte y notificaciones |
| Google OAuth | Inicio de sesion con cuenta Google |
| Vercel Blob | Imagenes, PDFs, renders y archivos |
| Vercel Cron | Jobs de sincronizacion y automatizacion |
| Vercel Web Analytics | Analitica web y drain para reportes internos |
| Cloudflare Turnstile | Anti-bot en formularios publicos |
| SMTP / Nodemailer | Correos transaccionales |
| Web Push | Notificaciones PWA |

---

## Vercel Cron

El archivo `vercel.json` define jobs programados para tareas operativas:

- actualizacion de tasa BCV;
- rotacion de catalogo;
- rotacion de mini tiendas;
- procesamiento de outbox de mensajeria;
- escalaciones de conversaciones;
- sincronizacion de plantillas WhatsApp;
- envio de notificaciones;
- despacho de promociones;
- integridad de fulfillment de inversionistas;
- sincronizacion de catalogo Meta.

---

## Seguridad

Medidas implementadas o contempladas en el codigo:

- autenticacion con NextAuth;
- sesiones JWT;
- credenciales con bcrypt;
- soporte de Google OAuth;
- verificacion opcional de email;
- control por roles;
- headers de seguridad en Next.js;
- Content Security Policy;
- Cloudflare Turnstile para formularios publicos;
- audit log de acciones criticas;
- proteccion de cron jobs mediante cabeceras de Vercel y secretos;
- validacion de webhooks externos;
- cifrado de tokens sensibles de Meta;
- variables de entorno para secretos;
- separacion entre datos publicos y administrativos.

---

## Base de datos

La base de datos usa PostgreSQL con Prisma. El schema contiene modelos para:

- usuarios y roles;
- productos, categorias y marcas;
- ordenes, items y documentos;
- inventario, movimientos y proveedores;
- compras y ordenes de compra;
- caja, POS y movimientos;
- cuentas por cobrar y pagar;
- delivery, shipping y eventos;
- aliados, comisiones y retiros;
- inversionistas, ledger, inventario y pagos;
- proyectos de diseno, tareas, renders y pagos;
- moodboards, cocinas y configuradores;
- conversaciones, notas y mensajeria;
- notificaciones y push subscriptions;
- marketing IA, Meta connections, assets, catalog sync y metricas;
- auditoria y seguridad.

---

## PWA

El proyecto incluye capacidades PWA:

- `manifest.ts`;
- service worker en `public/sw.js`;
- iconos PWA;
- pagina offline;
- notificaciones push con Web Push;
- endpoints para suscripcion de clientes, delivery e inversionistas;
- puente publico PWA y escaneo QR de productos.

---

## Documentos y reportes

El sistema genera y exporta documentos para operacion real:

- PDFs de ordenes;
- PDFs de envios;
- estados de cuenta;
- reportes de inventario;
- catalogos PDF;
- reportes de proyectos de diseno;
- documentos de caja;
- documentos de inversionistas;
- CSV y Excel para contabilidad, productos y reportes.

Librerias usadas: PDFKit, XLSX, pdf-parse, QRCode y utilidades internas.

---

## Diferenciadores

- Plataforma construida para una empresa real, no solo para una demo.
- Une e-commerce, ERP, IA y canales comerciales en una sola operacion.
- Integracion directa con WhatsApp Cloud API y Meta Graph API.
- Modulos para aliados e inversionistas, no solo clientes finales.
- Capacidades visuales: moodboard, cocinas y personalizacion 3D.
- Arquitectura lista para evolucionar a SaaS white-label.
- Backoffice completo para roles no tecnicos.
- Uso de IA en procesos concretos de negocio: marketing, reportes, soporte y catalogo.

---

## Alcance honesto

Este README describe lo que se observa en el codigo fuente, la arquitectura del repositorio y la documentacion interna existente. No incluye cifras comerciales, ingresos, usuarios activos, GMV, CAC, LTV o metricas financieras porque esos datos deben confirmarse con la operacion real antes de presentarse ante inversionistas o jurados.

Algunas integraciones dependen de variables de entorno, credenciales aprobadas y configuraciones externas:

- OpenAI requiere `OPENAI_API_KEY`.
- Meta Ads y catalogo requieren app, permisos y activos aprobados en Meta.
- WhatsApp Cloud API requiere token, phone number id y webhook configurado.
- Vercel Blob requiere `BLOB_READ_WRITE_TOKEN`.
- Push PWA requiere llaves VAPID.
- SMTP requiere proveedor de correo configurado.

Esta separacion evita afirmar que una integracion externa esta activa en un entorno especifico si no se verificaron sus credenciales de produccion.

---

## Modelo de negocio potencial

Carpihogar puede monetizarse de varias formas:

- venta directa de productos;
- comisiones por aliados comerciales;
- margen sobre productos de proveedores;
- servicios de diseno y proyectos;
- participacion de inversionistas en inventario;
- marketing administrado para marcas;
- implementacion SaaS white-label para otras empresas;
- soporte, configuracion y automatizacion empresarial con Trends172Tech.

---

## Roadmap

### Corto plazo

- Endurecer validaciones y permisos en modulos criticos.
- Consolidar panel root/superadmin para configuracion white-label.
- Mejorar pruebas automatizadas en flujos de ventas, inventario y pagos.
- Completar documentacion funcional por rol.
- Optimizar onboarding de nuevos aliados e inversionistas.

### Mediano plazo

- Conversion formal de la base actual en LUNA white-label.
- Panel de instalacion para nuevas empresas.
- Multi-tenant por empresa, dominio, marca y configuracion.
- Integracion mas profunda con pagos, facturacion y conciliacion.
- Analitica predictiva para stock, ventas, margen y demanda.

### Largo plazo

- Marketplace B2B/B2C para hogar y mobiliario en Latinoamerica.
- Red de proveedores, aliados, arquitectos, delivery e inversionistas.
- Agentes IA especializados por departamento.
- Automatizacion completa de marketing y operaciones comerciales.

---

## Instalacion local

> Nota: este proyecto maneja integraciones reales y variables sensibles. No se deben commitear secretos ni credenciales.

### Requisitos

- Node.js compatible con Next.js 15.
- PostgreSQL o una base Neon.
- Cuenta de Vercel para deployment.
- Variables de entorno configuradas.

### Comandos principales

```bash
npm install
npx prisma generate
npx prisma migrate deploy
npm run dev
```

### Scripts utiles

```bash
npm run dev
npm run build
npm run start
npm run lint
npm run seed
npm run root:create
npm run prisma:deploy
npm run images:scan
npm run images:optimize
npm run investor:healthcheck
```

---

## Variables de entorno principales

Ver `.env.example` para la lista completa.

```bash
DATABASE_URL=
DIRECT_DATABASE_URL=

NEXTAUTH_SECRET=
NEXTAUTH_URL=
NEXT_PUBLIC_URL=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

OPENAI_API_KEY=

BLOB_READ_WRITE_TOKEN=

WHATSAPP_CLOUD_API_TOKEN=
WHATSAPP_PHONE_NUMBER_ID=
WHATSAPP_API_VERSION=
WHATSAPP_GRAPH_BASE_URL=
WHATSAPP_WEBHOOK_VERIFY_TOKEN=
WHATSAPP_APP_SECRET=

META_APP_ID=
META_APP_SECRET=
META_REDIRECT_URI=
META_GRAPH_API_VERSION=
META_GRAPH_BASE_URL=
META_OAUTH_SCOPES=
MARKETING_META_TOKEN_ENCRYPTION_KEY=

WEB_PUSH_PUBLIC_KEY=
NEXT_PUBLIC_WEB_PUSH_PUBLIC_KEY=
WEB_PUSH_PRIVATE_KEY=
WEB_PUSH_SUBJECT=

SMTP_HOST=
SMTP_PORT=
SMTP_USER=
SMTP_PASS=
SMTP_FROM=
EMAIL_ENABLED=

NEXT_PUBLIC_TURNSTILE_SITE_KEY=
TURNSTILE_SECRET_KEY=

VERCEL_ANALYTICS_DRAIN_SIGNATURE_SECRET=
```

---

## Estructura de carpetas

```text
app/                 Next.js App Router, paginas, dashboards y API routes
components/          Componentes React reutilizables
server/              Logica de negocio e integraciones server-side
lib/                 Utilidades compartidas y clientes de servicios
prisma/              Schema, migraciones y seeds
agents/              Configuracion de agentes IA y herramientas
docs/                Documentacion tecnica y funcional
public/              Assets, uploads, PWA y archivos optimizados
scripts/             Automatizaciones, workers, QA y tareas operativas
types/               Tipos globales y shims
store/               Estado cliente
```

---

## Guia rapida para demo

Para una presentacion a concurso o inversionista, se recomienda mostrar:

1. Home y catalogo publico.
2. Producto con galeria, precio y acciones.
3. Carrito y flujo de checkout.
4. Dashboard administrativo.
5. Gestion de ventas y documentos.
6. Inventario y alertas.
7. Delivery y tracking.
8. Portal de aliado o inversionista.
9. Marketing IA con Meta.
10. Asistente IA / flujo de compra asistida.
11. Moodboard o configurador visual.
12. Reportes y exportaciones.

---

## Descripcion corta

Carpihogar.com es una plataforma full-stack de comercio inteligente para muebles y hogar en Venezuela. Combina tienda online, ERP, inventario, delivery, aliados, inversionistas, marketing con IA, WhatsApp, Meta Ads, PWA y dashboards por rol en una sola aplicacion construida con Next.js, React, TypeScript, Prisma, PostgreSQL, Vercel y OpenAI.

---

## Descripcion larga

Carpihogar.com digitaliza la operacion completa de una empresa de muebles y diseno de interiores. El sistema permite vender productos online, administrar inventario, procesar pedidos, generar presupuestos, coordinar entregas, gestionar cuentas por cobrar y pagar, trabajar con aliados comerciales, recibir inversionistas, crear campanas de marketing con IA y conectar la operacion con WhatsApp y Meta.

La plataforma fue disenada para usuarios reales no tecnicos: clientes, vendedores, administradores, arquitectos, repartidores, aliados, gestores de marca e inversionistas. Cada rol tiene su propio dashboard y sus propias acciones. La arquitectura esta pensada para escalar desde una tienda real hacia un SaaS white-label que Trends172Tech pueda implementar en otras empresas de la region.

---

## Datos de empresa

| Campo | Valor |
|---|---|
| Producto | Carpihogar.com |
| Empresa / razon social | Trends172, C.A. |
| RIF | J-31758009-5 |
| Pais | Venezuela |
| Ubicacion | Barinas, Estado Barinas, Venezuela |
| Direccion comercial | Av. Industrial, Edificio Teca, Barinas, Estado Barinas |
| Sector | E-commerce, ERP, muebles, hogar, diseno de interiores |
| Sitio | [carpihogar.com](https://carpihogar.com) |
| Contacto | root@carpihogar.com |
| Telefono | +58 424 526 2306 |

---

## Licencia y propiedad intelectual

Copyright 2025-2026 Carpihogar.com / Trends172, C.A.

Este repositorio contiene codigo fuente, arquitectura, flujos de negocio, documentacion y activos propietarios. Su uso, copia, distribucion o explotacion comercial requiere autorizacion escrita de Trends172, C.A.
