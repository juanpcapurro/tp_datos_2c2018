# Trabajo práctico Organizacion de Datos

Grupo: null

Integrantes: 

  Federico Jure

  Carlos Talavera

  Juan Pablo Capurro

[Informe TP1](informe_tp1.md)
[Informe TP2](informe_tp2.md)

## Como generar los pdfs
```
pandoc -f markdown_mmd+yaml_metadata_block -o informe_tp1.pdf informe_tp1.md -t html  -s --css informes.css
```

# Contributing
Es importante hacer un 'clean all outputs' antes de forzar un merge o commitear.
Es muy facil que surjan conflictos en la salida de las celdas, y no deberiamos trackearlo.
