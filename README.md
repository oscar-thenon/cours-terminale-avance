# Contenu

Livre $\LaTeX$ destiné aux élèves de Terminale allant en prépa.
_Dernière version : août 2019._

![Preview] (dist/cours_terminale_avance.pdf)

# Auteur

[Oscar Thenon](mailto:oscar.thenon@etu.univ-amu.fr)

# Version compilée

`./dist/cours_terminale_avance.pdf`

# Compilation

```bash
latexmk -pdf -synctex=1 -interaction=nonstopmode -file-line-error -recorder src/cours_ts.tex; mkdir -p dist; mv src/cours_ts.pdf dist/cours_terminale_avance.pdf
```

# Licence

**[CC BY-NC-SA](https://creativecommons.org/licenses/by-sa/4.0/) Attribution-ShareAlike 4.0 International**

# Fichiers externes

Dans `./ext` se trouvent des fichiers ayant servi de sources à ce travail.
