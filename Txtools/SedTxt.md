---
author: Der Franz
title: Procesamiento de texto con Sed 
description: linux power txt tools
pubDate: "Feb 22 2024"
tags:
    - sed
    - Linux
---

#### Insertar lineas en otro txt
- literalmente
    - sed -i -e '1iHere is my new top line\' filename
* de otro txt
    * sed -i -e '1 { r template' -e 'N; }' test.md
