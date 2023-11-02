---
layout: post
title: Terraform with clouds
subtitle: Notas de aprendizaje de Terraform
tags: [test]
comments: true
author: nilofe
---

**Notas**

## Commands Terraform 

~~~bash
terraform graph | dot -Tsvg > image.svg
~~~
La opción ```graph``` sé utiliza para mostrar un gráfico de ejecución visual de los recursos
de terraform según la configuración actual o un plan de ejecución.
El comando ```dot``` es parte de una visualización parar generar representaciones visuales de gráficos
descritos en el lenguaje ```dot```.

#### Ejemplo

[image.svg](https://surf-fern-778.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fe46e3d46-3628-4d76-bc7e-57e47e4f8f7a%2F0749f9ee-93ff-40fd-a656-de8f41a87439%2FUntitled.svg?table=block&id=b032b2e2-e525-45c7-adb2-9a85b3dca489&spaceId=e46e3d46-3628-4d76-bc7e-57e47e4f8f7a&userId=&cache=v2)

```bash
dot -Tsvg input.dot -o outoput.svg
```
Este es un comando que forma el ```input.dot``` archivo. Lo convierte a formato SVG y guarda la 
salida como ```output.svg```. El ```-Tsvg``` especifica el formato de salida como SVG y el ```-o output.svg```
especifica el nombre del archivo de salida como ```output.svg```. Asegure tener instalado ```Graphviz``` en su sisteman.

