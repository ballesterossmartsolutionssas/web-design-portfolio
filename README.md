# Web Design Portfolio — Ballesteros Smart Solutions S.A.S

Portafolio de landing pages (demos) listas para GitHub Pages. Cada demo es personalizable (logo, colores, copy, secciones y contacto) y puede escalarse a un sitio completo con SEO, analítica y formularios reales.

## Objetivo del repositorio
Crear una mini-suite de demos profesionales para presentar a clientes y vender servicios web sin frameworks (solo HTML/CSS/JS estático).

## Demos incluidos
- **Paris Boutique** — Landing premium estilo boutique (moda femenina)
- **RefriLavadoras (Dark Theme)** — Servicio técnico, estilo oscuro premium
- **RefriLavadoras (Light Theme)** — Servicio técnico, estilo claro corporativo
- **Bistro & Café** — Restaurante elegante con menú y reservas
- **Estudio Jurídico** — Demo corporativa para servicios legales
- **Inmobiliaria Aurora** — Landing moderna para propiedades destacadas

## Estructura del repo
- `/index.html` → Portafolio principal
- `/paris-boutique/` → Demo de moda
- `/appliance-repair-dark/` → Demo servicio técnico (dark)
- `/appliance-repair-light/` → Demo servicio técnico (light)
- `/restaurant-bistro/` → Demo restaurante
- `/law-firm/` → Demo legal
- `/real-estate/` → Demo inmobiliaria

## Cómo abrir localmente
1. Clona el repo.
2. Abre `index.html` en el navegador o usa un servidor local:
   ```bash
   python -m http.server 8000
   ```
3. Visita `http://localhost:8000`.

## Publicación (GitHub Pages)
1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / Folder: `/ (root)`
4. Guardar

## Cómo personalizar un demo para un cliente
Cambios rápidos por demo (cada `index.html` dentro de la carpeta):
- **WhatsApp**: busca `https://wa.me/573023877799` y reemplaza por el número del cliente.
- **Correo**: reemplaza `ballesterossmartsolutionssas@gmail.com` por el email del cliente.
- **Nombre del negocio**: actualiza el `<title>` y los encabezados principales.
- **Textos**: reemplaza descripciones, servicios y testimonios.
- **Colores**: ajusta las variables CSS en `:root` (ej: `--accent`, `--bg`, `--text`).
- **CTA**: edita el texto y el destino de los botones principales.

## Contacto
📧 ballesterossmartsolutionssas@gmail.com
