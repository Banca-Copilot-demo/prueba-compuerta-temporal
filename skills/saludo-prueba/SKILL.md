---
name: saludo-prueba
description: Skill mínimo para medir si un plugin compuesto resuelve una referencia a un artefacto que vive fuera de su directorio. No hace nada útil.
---

# Saludo de prueba

Este skill existe sólo para una medición: comprobar si un `plugin.json` que lo referencia
desde otro directorio del repositorio consigue que el cliente lo materialice al instalar.

Si ves este archivo dentro de `installed-plugins/<marketplace>/compuesto-publico/skills/`,
la referencia se resolvió.
