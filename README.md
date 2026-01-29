# SUPABASE #

## Entorno de Edición (IDE)
Gracias a su naturaleza Open Source y sus archivos de configuración en GitHub, sabemos exactamente qué prefieren:
* Editor: VS Code. Es el estándar interno, especialmente por su integración con TypeScript.
* Extensiones y Configuración: Utilizan un set estricto de ESLint y Prettier para mantener la consistencia en su monorepo. También recomiendan la extensión de Tailwind CSS y, curiosamente, extensiones de SQL para gestionar sus migraciones directamente desde el editor.
## Ecosistema de Navegación
* Principal: Google Chrome. Sus ingenieros de frontend utilizan las herramientas de inspección de red de Chrome para monitorizar las llamadas a la API de Postgrest.
* Pruebas de Renderizado: Según su documentación de testing, utilizan Playwright. Esto les permite emular múltiples navegadores (Chromium, Firefox, WebKit) de forma automatizada para asegurar que el Dashboard de Supabase sea impecable en cualquier entorno.
## Gestión de Versiones
* Sistema: Git.
* Plataforma: GitHub. Supabase es una empresa "Build in Public". Todo su código, desde el Dashboard hasta los servicios de autenticación, está alojado en GitHub, lo que permite que la comunidad contribuya mediante Pull Requests y reporte issues de forma abierta.
## Diseño UI/UX
* Herramienta: Figma.
* Dato de investigación: Si exploras su blog de ingeniería, verás que tienen un sistema de diseño propio llamado "Supa". Utilizan Figma para el prototipado de componentes complejos como sus tablas de base de datos (que se sienten como una hoja de cálculo) antes de codificarlas con Radix UI.
## Lenguajes y Herramientas Base
El stack de Supabase es una mezcla fascinante de confiabilidad clásica y herramientas de vanguardia:
* Lenguajes: TypeScript (Frontend/Dashboard), Go y Elixir (para la capa de tiempo real), y por supuesto, SQL (PostgreSQL es el corazón de todo).
* Herramienta "Moderna": Deno. Supabase utiliza Deno para sus Edge Functions, permitiendo que los desarrolladores ejecuten código TypeScript en servidores distribuidos globalmente con una latencia mínima.

## Resumen de Hallazgos
| Paso del Manual | Hallazgo Clave |
| :--- | :--- |
| **1. Ofertas de Empleo** | Encontré vacantes de "Cloud Engineer" que exigen dominio de **Go** y **Docker**. |
| **2. StackShare** | Confirmado el uso de **Next.js** para su sitio principal y **PostgreSQL** como base de datos. |
| **3. Wappalyzer** | Detectó el uso de **Tailwind CSS** y **Stripe** para la gestión de pagos. |
| **4. Engineering Blog** | Un artículo detalla cómo migraron de una infraestructura vieja a **Deno** para mejorar la velocidad. |
| **5. GitHub** | Revisé su `package.json` principal: usan **Turbo** para gestionar su monorepo de forma ultra rápida. |
