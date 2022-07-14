# Trabajo de Fin de Grado: *Contribuciones a GenoMus: Rediseño de un motor de cómputo funcional sobre estructuras musicales*

### Autor: Miguel Pedregosa Pérez
### Tutores: Miguel Molina Solana, José López Montes


___

La documentación de este proyecto está realizada con `LaTeX`. En este repositorio se incluye tanto el código fuente como una versión imprimible en formato PDF.

#### Compilación de las fuentes

En caso de querer generar la versión imprimible compilando las fuentes necesitaremos instalar `TeXLive` en nuestra distribución.

Una vez instalada, ejecutaremos:

    pdflatex proyecto.tex


Seguido por

    bibtex proyecto
    
y de nuevo

    pdflatex proyecto.tex

O directamente

    make
    
(que habrá que editar si el nombre del archivo del proyecto cambia)
