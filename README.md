# Hacklab Oriente – Sitio Web

Sitio web de [Hacklab Oriente](https://hacklaboriente.org/), un espacio colaborativo de tecnología, ciberseguridad y proyectos libres.

Construido con [Hugo](https://gohugo.io/) y el tema [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

## Desarrollo local

**Requisitos:** Hugo extended v0.147+

```bash
git clone --recurse-submodules https://github.com/hacklab-oriente/hacklab-oriente.github.io.git
cd hacklab-oriente.github.io
hugo server -D
```

El sitio estará disponible en `http://localhost:1313`.

## Contribuir

El contenido está en `content/`. Los borradores se publican agregando `draft: false` al front matter.

Para agregar un evento a la agenda:

```bash
hugo new agenda/nombre-del-evento.md
```

## Despliegue

Cada push a `main` dispara un workflow de GitHub Actions que construye el sitio y lo despliega en GitHub Pages. El dominio `hacklaboriente.org` está gestionado en Cloudflare.
