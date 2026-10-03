# Cuenta bancaria — Git y pull requests

**Autor:** Hilario Sebastian Espinoza Garcia

## Cómo correr

    ./correr.sh

## Mis pull requests

| # | Qué cambió |
|---|---|
| 1 | El estado de cuenta muestra cuántos retiros se hicieron y cuántos fueron gratis |
| 2 | README y evidencia de la práctica |

## Boleto de salida

1. ¿Qué diferencia hay entre `git add` y `git commit`?

   Respuesta:
   git add prepara los archivos a subir, como cambios en codigos o archivos nuevos y git commit toma todos los cambios y los guarda en el historial local del repositorio, generando una instantánea con un identificador único y un mensaje descriptivo.

2. ¿Por qué después del merge en GitHub tu `main` de Ubuntu no tenía el cambio hasta que hiciste `git pull`?

   Respuesta:
   Lo que esta en github y en la pc son copias distintas, al hacerlo en web los cambios no se ven en la pc hasta que se haga un git pull que compara los cambios y los trae a la pc

3. Abriste un PR y después hiciste otro commit en la misma rama. ¿Qué pasó con el PR?

   Respuesta:
   El pull request se actualiza automaticamente, rastrean la rama completa hasta que se aprueban, se fusionan o se cierran.

4. ¿Por qué en un equipo nadie hace cambios directamente en `main`?

   Respuesta:
   Por una cuestion de buenas practicas, se supone que un main debe representar la version estable y con los cambios necesarios. Si todos trabajaran en ella habria cambios no deseados, cruces y choques entre los equipos.