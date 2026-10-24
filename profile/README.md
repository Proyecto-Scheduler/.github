# Proyecto Scheduler

## Repositorios

- [reports](https://github.com/Proyecto-Scheduler/reports): informes finales y tesinas de cada proyecto, con metadatos sobre qué se hizo, qué quedó pendiente y dónde está el código. Si recién empezás, arrancá por acá. El [README](https://github.com/Proyecto-Scheduler/reports#readme) indica cómo recorrerlo y [CONTRIBUTING.md](https://github.com/Proyecto-Scheduler/reports/blob/main/CONTRIBUTING.md) explica cómo agregar un informe.
- [patches](https://github.com/Proyecto-Scheduler/patches): cambios sobre el kernel de FreeBSD del planificador basado en redes de Petri, extraídos del árbol original con `oot`. Contiene los archivos nuevos y modificados junto con las versiones base, para reaplicarlos sobre un clon limpio.
- [oot](https://github.com/Proyecto-Scheduler/oot): CLI para desarrollo out-of-tree del kernel. Extrae los commits de un clon del kernel a un repo de patches y los vuelve a aplicar con merge de 3 vías. Ver el [README](https://github.com/Proyecto-Scheduler/oot#readme) para configuración y uso.
- [ELFBag](https://github.com/Proyecto-Scheduler/ELFBag): plugins para Clang/LLVM y GCC que insertan metadatos en los ejecutables ELF de forma transparente, para que el kernel los lea al cargar el programa.
