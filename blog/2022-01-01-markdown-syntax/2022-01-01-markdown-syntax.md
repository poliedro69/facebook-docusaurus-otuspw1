---
slug: markdown-basic-syntax
title: Markdown Basic Syntax
authors: poliedro
tags: [markdown, marcado, sintaxis, syntax]
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

## ¿Qué es el lenguaje Markdown?


### Encabezados
Para crear un encabezado, agregue signos de número (#) delante de una palabra o frase. El número de signos numéricos que utilice debe corresponder al nivel del encabezado. Por ejemplo, para crear un encabezado de nivel tres (), use tres signos numéricos (por ejemplo, ### Mi encabezado).

<Tabs>

  <TabItem value="md" label="Markdown">

  ```md
  # Esto es un encabezado de Nivel 1, equivale en html a <h1></h1>
  ## Esto es un encabezado de Nivel 2, equivale en html a <h2></h2>
  ### Esto es un encabezado de Nivel 3, equivale en html a <h3></h3>
  #### Esto es un encabezado de Nivel 4, equivale en html a <h4></h4>
  ##### Esto es un encabezado de Nivel 5, equivale en html a <h5></h5>
  ```

  </TabItem>

  <TabItem value="html" label="HTML">

  # Esto es un encabezado de Nivel 1
  ## Esto es un encabezado de Nivel 2
  ### Esto es un encabezado de Nivel 3
  #### Esto es un encabezado de Nivel 4
  ##### Esto es un encabezado de Nivel 5

  </TabItem>

</Tabs>

### Párrafos
Para crear párrafos, use una línea en blanco  
para separar una o más líneas de texto.

```md
Esto es un simple párrafo
```