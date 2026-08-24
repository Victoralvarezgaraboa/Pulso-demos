# Pulso · en vivo — Showroom público (completo)

El escaparate de todas tus herramientas: el visitante **elige sector**, entra con
**Demo / Demo** y prueba la herramienta real, tal cual, con **datos de ejemplo**.
Este es el enlace que va en la bio de Instagram y en los reels.

## Archivos (TODOS en la raíz del repo)

| Archivo          | Sector / función                                        |
|------------------|---------------------------------------------------------|
| `index.html`     | El hub: selector de sector + acceso Demo + marco.       |
| `generador.html` | Electricidad · presupuestos (mano de obra + material).  |
| `taller.html`    | Taller · buscador de precios de recambios.              |
| `reformas.html`  | Reformas · presupuestos por capítulos de obra.          |
| `clima.html`     | Clima · presupuestos con catálogo de equipos.           |
| `eventos.html`   | Música y eventos · panel de rentabilidad por bolo.      |
| `fitness.html`   | Fitness · semáforo de bajas y cuotas.                   |
| `medicion.html`  | Nutrición y entreno · ficha del paciente.               |

Los 7 sectores están **en vivo**. Todos con proveedores, precios, socios y eventos
**de ejemplo** — ningún dato real de ningún cliente.

## Cómo ponerlo online (sitio estático, gratis)

1. Sube los **archivos** a un repositorio de GitHub (en la raíz).
2. En **render.com** → **New → Static Site** (no Blueprint).
3. Conecta el repositorio.
4. **Build Command**: vacío · **Publish Directory**: `.`
5. **Create Static Site**. Tendrás una URL tipo `https://pulso-en-vivo.onrender.com`.
6. Esa URL va en el **enlace de la bio** de Instagram.

> Al ser Static Site no "duerme": carga siempre rápido, ideal para reels.

## Acceso de demostración

Usuario **Demo** · Contraseña **Demo**. Es un acceso de experiencia (da sensación de
producto real); por eso dentro solo hay datos de ejemplo. El producto real de cada
cliente sigue siendo su instancia con login de verdad.

## Nota importante al subir desde el móvil

Cuidado con la traducción automática de nombres: los archivos deben quedar **exactamente**
como arriba (`index.html`, `taller.html`, etc.), en minúsculas y en inglés donde toca.
Si el móvil renombra alguno, corrígelo con el lápiz de GitHub antes de desplegar.
