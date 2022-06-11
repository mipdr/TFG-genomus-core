# Trabajo de Fin de Grado: *Crear muchos problemas para solucionar unos pocos: Constitución de GenoMus como un proyecto a prueba de futuro (Working title)*

### Autor: Miguel Pedregosa Pérez
### Tutores: Miguel Molina Solana, José López Montes


___

La documentación de este proyecto está realizada con `LaTeX`, por lo
tanto para generar el archivo PDF necesitaremos instalar `TeXLive` en
nuestra distribución.

Una vez instalada, ejecutaremos:

    pdflatex proyecto.tex


Seguido por

    bibtex proyecto
    
y de nuevo

    pdflatex proyecto.tex

O directamente

    make
    
(que habrá que editar si el nombre del archivo del proyecto cambia)
