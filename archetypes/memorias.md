---
date: {{ .Date | dateFormat "2006-01-02" }}
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---
Descripción corta de la charla.

## Ponente

Nombres y apellidos.
[@usuario](https://github.com/)

## Presentación

[Descargar presentación]()

## Enlaces útiles

- [Enlace 1]()
- [Enlace 2]()
- [Enlace 3]()
