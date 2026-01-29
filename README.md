# SUPABASE #

## Entorno de Edición (IDE)
Gracias a su naturaleza Open Source y sus archivos de configuración en GitHub, sabemos exactamente qué prefieren:
<img width="1101" height="798" alt="Captura de pantalla 2026-01-28 184426" src="https://github.com/user-attachments/assets/441389eb-9a79-4083-b5e2-ac826cfabf8f" />
<img width="953" height="237" alt="Captura de pantalla 2026-01-28 184556" src="https://github.com/user-attachments/assets/d0a5f2c7-6d44-451e-8425-a45a3c188073" />
* Editor: VS Code. Es el estándar interno, especialmente por su integración con TypeScript.
* Extensiones y Configuración: Utilizan un set estricto de ESLint y Prettier para mantener la consistencia en su monorepo. También recomiendan la extensión de Tailwind CSS y, curiosamente, extensiones de SQL para gestionar sus migraciones directamente desde el editor.
## Ecosistema de Navegación
<img width="1820" height="920" alt="Captura de pantalla 2026-01-28 184833" src="https://github.com/user-attachments/assets/8b1f815e-c05e-42e2-adb7-cf360ddd9644" />
<img width="1839" height="863" alt="Captura de pantalla 2026-01-28 184915" src="https://github.com/user-attachments/assets/10df4394-12a3-49c3-9792-e695843d3f4f" />
<img width="1840" height="813" alt="Captura de pantalla 2026-01-28 184953" src="https://github.com/user-attachments/assets/d6ad978e-a50b-431e-9063-43a5d77250e2" />

* Principal: Google Chrome. Sus ingenieros de frontend utilizan las herramientas de inspección de red de Chrome para monitorizar las llamadas a la API de Postgrest.
* Pruebas de Renderizado: Según su documentación de testing, utilizan Playwright. Esto les permite emular múltiples navegadores (Chromium, Firefox, WebKit) de forma automatizada para asegurar que el Dashboard de Supabase sea impecable en cualquier entorno.
## Gestión de Versiones
<img width="625" height="677" alt="Captura de pantalla 2026-01-28 185920" src="https://github.com/user-attachments/assets/a098304f-69b1-435f-914b-c335a9d95467" />
<img width="620" height="674" alt="Captura de pantalla 2026-01-28 185942" src="https://github.com/user-attachments/assets/24c1fdd7-5b27-498d-9c0e-eacac5c1a334" />

* Sistema: Git.
* Plataforma: GitHub. Supabase es una empresa "Build in Public". Todo su código, desde el Dashboard hasta los servicios de autenticación, está alojado en GitHub, lo que permite que la comunidad contribuya mediante Pull Requests y reporte issues de forma abierta.
## Diseño UI/UX
<img width="1836" height="922" alt="Captura de pantalla 2026-01-28 191802" src="https://github.com/user-attachments/assets/e6dd524e-d45e-4aa2-bd00-4b9f51c2a618" />

* Herramienta: Figma.
* Dato de investigación: Si exploras su blog de ingeniería, verás que tienen un sistema de diseño propio llamado "Supa". Utilizan Figma para el prototipado de componentes complejos como sus tablas de base de datos (que se sienten como una hoja de cálculo) antes de codificarlas con Radix UI.
## Lenguajes y Herramientas Base
<img width="1427" height="905" alt="Captura de pantalla 2026-01-28 191929" src="https://github.com/user-attachments/assets/62bb3e3d-9a46-4dae-8c86-6fa11c42f31b" />
<img width="1414" height="902" alt="Captura de pantalla 2026-01-28 191949" src="https://github.com/user-attachments/assets/0a7ff025-1a38-458f-afdc-add4ab5769ee" />
<img width="1415" height="353" alt="Captura de pantalla 2026-01-28 192004" src="https://github.com/user-attachments/assets/ed96ac26-5499-477e-8701-8109ab517dc5" />

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
