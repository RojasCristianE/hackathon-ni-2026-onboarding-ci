# 🚀 Team Fritinder

## 📌 Datos del Proyecto
- **Nombre del Proyecto:** Fritinder
- **Descripción:** Plataforma de descubrimiento gastronómico hiper-local y logística compartida para PYMES en Nicaragua. Utiliza una interfaz gamificada de "Swipe" para conectar los antojos de los usuarios con productos frescos de pequeños negocios (fritangas, reposterías, comedores), optimizando los tiempos de entrega y reduciendo el desperdicio alimentario mediante un algoritmo de frescura en tiempo real.
- **Integrantes:**
  - [Junior Antonio Cortez Ramirez] — [Rol: Frontend / UX-UI /]
  - [Perfecto Tadeo Castillo] — [Rol: Backend / UX-UI / Negocios]
  - [Jason Alejandro Calero Sanchez] — [Rol: / UX-UI / Negocios]
  - [Adriana Paola Cortez Ramirez] — [Rol: / UX-UI / Negocios]
- **Stack Tecnológico:** Astro / React Native, Python (Django), PostgreSQL + PostGIS, Firebase (Geofencing).
- **Repositorio del Proyecto:** https://github.com/[usuario]/fritinder-hackathon

---

## 🎯 El Problema
1. **Fatiga de Decisión:** Los usuarios pierden tiempo buscando qué comer en menús PDF estáticos o apps de delivery saturadas por grandes cadenas franquiciadas.
2. **Invisibilidad de las PYMES:** Fritangas, comedores y reposterías artesanales carecen de presupuesto de marketing y herramientas para gestionar catálogos dinámicos.
3. **Logística Ineficiente y Desconfianza:** Alta tasa de productos perecederos que pierden su calidad en horas y la falta de un sistema de entregas confiable, seguro y de bajo costo para el sector informal.

## 💡 La Solución
**Fritinder** transforma la manera de pedir comida local a través de un ecosistema de tres pilares:

* **UX Interactiva (El Swipe):** Desliza a la derecha (Like) para guardar en tu lista de antojos o a la izquierda (Next) para ver otro platillo. Al hacer "Match", se concreta el pedido de forma inmediata y automática vía WhatsApp.
* **Algoritmo de Frescura (Freshness Score):** Los productos cuentan con un ciclo de vida útil automatizado en la base de datos (horas para fritangas, días para reposterías). La app prioriza platos recién hechos y activa ofertas relámpago automáticas para mitigar pérdidas económicas en los negocios.
* **Logística Autónoma y Silenciosa:** Implementación de entregas compartidas (Delivery Pooling) para abaratar costos de envío, validación biométrica diaria de repartidores y confirmación de entrega segura mediante códigos dinámicos de un solo uso (OTP) coordinados por Geofencing (GPS).

## 🛠️ Stack Tecnológico Detallado
* **Frontend:** `Astro` / `React Native` + `Tailwind CSS` + `Framer Motion` (Lógica y físicas del Swipe).
* **Backend:** `Python (Django REST Framework)` (Manejo de estados de expiración y algoritmos).
* **Base de Datos:** `PostgreSQL` con extensión `PostGIS` (Geolocalización por radio de proximidad de 5-7 km).
* **Infraestructura y Tiempo Real:** `Firebase` o `Supabase` (Notificaciones push, geofencing y tracking pasivo).

## 📊 Modelo de Negocio (Monetización)
1. **Suscripción Premium (B2B SaaS):** Acceso para las PYMES a analíticas predictivas de mercado y mapas de calor sobre los gustos de los consumidores.
2. **Comisión por Match Exitoso:** Cobro por volumen de ventas canalizado hacia el negocio.
3. **Publicidad Nativa:** Espacios patrocinados en el mazo de cartas para grandes marcas distribuidoras de insumos (bebidas, harinas, carnes).

## 🏆 Impacto Social
Fritinder impulsa la **digitalización de la economía popular nicaragüense**. Al dotar a las fritangas de barrio y pequeños emprendedores de garage con herramientas avanzadas de analítica de datos y logística, democratizamos el comercio electrónico y reducimos la brecha tecnológica del sector informal.