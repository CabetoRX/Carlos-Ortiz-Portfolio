# Carlos Ortiz Portfolio

Landing page estática preparada para producción y despliegue desde GitHub.

## Estructura

```text
.
├── index.html
├── assets
│   ├── css
│   │   └── styles.css
│   ├── images
│   └── js
│       └── main.js
├── .gitignore
└── README.md
```

## Desarrollo local

Puedes abrir `index.html` directamente o usar un servidor local:

```bash
npx serve .
```

## Despliegue

Proyecto estático: no requiere `npm install`, build ni servidor Node.js.

Configura el hosting para servir el contenido desde la raíz pública del sitio.

## Recomendaciones pendientes

- Descargar y alojar localmente la fotografía que todavía usa `assets.zyrosite.com`.
- Dominio público canónico: `https://carlosalbertoortizloaiza.com/`.
- En Hostinger, ambos dominios deben servir el mismo `public_html`; conservar el alias y los certificados de ambos dominios.
- `.htaccess` redirige el dominio antiguo y `www` mediante 301, conservando ruta y parámetros. Mantener activo `carlosortiz.site` para conservar las redirecciones.
- `robots.txt` publica el sitemap del dominio canónico.
- Añadir `og:image` local.
- Añadir favicon e iconos.
- Validar HTML y Lighthouse después del despliegue.
