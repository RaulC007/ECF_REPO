# Formas de integrar cambios (Merge strategies)

## 1. Merge commit
La herramienta git merge se utiliza para fusionar una o más ramas dentro de la rama que se encuentra activa. A continuación, Git avanzará la rama actual y creará un merge commit explícito para registrar el resultado de la fusión en el historial.

## 2. Squash merge
Esta opción de git merge es una forma de aplanar commits (de ahí el término squash, que significa aplastar o comprimir) utilizando comandos como git merge --squash. Este comando permite combinar todos los cambios de una rama secundaria en la rama destino como si fuera un solo commit, sin hacer un merge tradicional. No se fusionan los historiales individuales de ambas ramas; simplemente se aplican los cambios consolidados para poder crear un único commit que los represente.

## Referencias de todas las investigaciones

https://monoforms.com/content/merge-commit-rebase-y-squash-merge-en-git-diferencias-y-cuando-usar-cada-uno
https://www.webtutoriales.com/articulos/2025/03/28/git-merge-squash/
https://git-scm.com/book/es/v2/Ap%C3%A9ndice-C:-Comandos-de-Git-Ramificar-y-Fusionar
https://www.ibm.com/docs/es/tap/5.0.0?topic=tasks-fork-task
https://graphite.com/guides/understanding-git-fork-pull-request-workflow
https://graphite.com/guides/understanding-git-fork-pull-request-workflow
https://wingify.com/glossary/es/feature-branch/
https://git-scm.com/book/es/v2/Git-en-entornos-distribuidos-Flujos-de-trabajo-distribuidos
