# Hacklab Oriente – Sitio Web

Sitio web de [Hacklab Oriente](https://hacklaboriente.org/), un espacio colaborativo de tecnología,
ciberseguridad y proyectos libres.

Construido con [Hugo](https://gohugo.io/) y el tema [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

## Desarrollo local

**Requisitos:** Hugo extended v0.147+

```shell
git clone --recurse-submodules https://github.com/hacklab-oriente/hacklab-oriente.github.io.git
cd hacklab-oriente.github.io
hugo server -D
```

El sitio estará disponible en `http://localhost:1313`.

## Contribuir

Todos los archivos de contenido se generan en formato _MarkDown_, puede consultar
una referencia rápida de dicho formato [aquí](https://www.markdownguide.org/cheat-sheet/)

El contenido está en `content/`. Los borradores se publican agregando `draft: false`
al front matter.

### Agregar un evento a la agenda:

```shell
hugo new agenda/nombre-del-evento.md
```

### Agregar una memoria de charla pasada:

```shell
hugo new memorias/nombre-charla.md
```

Esto generará una plantilla en la ruta `/content/memorias/nombre-charla.md`. En
dicho archivo por favor especifique la fecha en el campo `date` del frontmatter.

De igual forma, ponga una descripción corta, el nombre del ponenete o ponentes,
el enlace de descarga a la presentación y algunos enlaces de interés que complementen
la charla.

## Despliegue

Cada push a `main` dispara un workflow de GitHub Actions que construye el sitio
y lo despliega en GitHub Pages. El dominio `hacklaboriente.org` está gestionado
en Cloudflare.
