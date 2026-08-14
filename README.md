<h1>Hola, soy José 👋</h1>

Desarrollo software a medida y producto propio desde **[Hada Consulting](https://hadaconsulting.com)**
(Madrid, España). Trabajo casi siempre con datos que a alguien le importan de
verdad, así que las reglas no cambian de proyecto a proyecto: **infraestructura
en la UE, control de acceso en la base de datos —no ocultando botones— y todo
documentado, explicado y auditable.**

## En qué trabajo ahora

Tres repos, un mismo proyecto. Son **privados** (software propietario), así que
enlazo a lo que sí es público.

| Repo | Qué es | Stack |
|---|---|---|
| `app-hadakids` 🔒 | Panel de gestión de **Hada Kids**: pacientes, tutores, citas y cuadrante, facturación en PDF, lista de espera y auditoría. Al manejar datos de salud de menores (categoría especial RGPD), el aislamiento por organización se aplica con **RLS en Postgres**, con tres roles y alta solo por invitación mediante token de un uso y caducable. | Next.js · TypeScript · Tailwind · Supabase (Postgres + Auth + RLS) · Resend · Playwright |
| `hada-kids` 🔒 | Web pública del producto ([hadakids.com](https://hadakids.com), en construcción): capta **centros** que quieren probar la plataforma. Frontend aparte, **la misma** base de datos que el panel. | Next.js · TypeScript · Supabase · Resend |
| `hadaconsulting` 🔒 | Web corporativa ([hadaconsulting.com](https://hadaconsulting.com)) y **fuente única de identidad legal**: los demás productos la consumen por API en vez de duplicarla. Incluye el design system y la marca. | Next.js · TypeScript · design system propio · Playwright · Lighthouse CI |

Y, en paralelo, `hada-ledger` 🔒 — un **laboratorio de DevOps**, no un producto:
un banco simulado (Spring Boot + Postgres + Next.js) para recorrer el ciclo
CI/CD completo sobre Kubernetes. La invariante que lo gobierna es que *la suma
de todos los saldos del sistema es constante*: si se rompe bajo carga
concurrente, el pipeline no promociona el artefacto.

## Lo que viene

**Hada Kids** es el primer producto, no el único. La hoja de ruta de
[hadaconsulting.com](https://hadaconsulting.com) marca seis líneas, y cada una
acabará teniendo su producto o su servicio:

- 🤖 **IA aplicada** — modelos y agentes adaptados al ecosistema de cada negocio
- 📊 **Big Data y BI** — visualización, análisis y predicción sobre datos reales
- ⚙️ **Automatización** — quitar de en medio la tarea repetitiva y periódica
- 🛡️ **Ciberseguridad** — protección frente a ataques reales, no frente a titulares
- ☁️ **DevOps y cloud** — infraestructura moderna, segura y escalable
- 🧩 **Desarrollo full-stack** — software a medida, de la idea a la implantación

## Stack y principios

- 🔭 **Día a día** · Next.js (App Router) · TypeScript · Tailwind · Supabase (PostgreSQL + Auth + RLS) · Vercel (Frankfurt) · Cloudflare R2 · Playwright · GitHub Actions
- 🌱 **Aprendiendo** · arquitectura multi-tenant · Kubernetes y CI/CD · Java/Spring Boot
- 🔐 **Innegociable** · RGPD desde el diseño, datos en la UE, cifrado, roles y registro de actividad desde el primer commit
- 📦 **Portabilidad** · el código y los datos del cliente son suyos, documentados y exportables

## Contacto

- 🌐 [hadaconsulting.com](https://hadaconsulting.com)
- 📫 [info@hadaconsulting.com](mailto:info@hadaconsulting.com)

<br>

<a href="https://app.daily.dev/h4rd3xt">
  <img src="./devcard.png" width="356" alt="DevCard de José en daily.dev" />
</a>
