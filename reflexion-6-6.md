##Explica con tus palabras qué hace git cherry-pick y en qué se diferencia de merge y rebase.##

cherry-pick es una forma más selectiva de mover cambios entre ramas,
mientras que merge y rebase afectan al historial de manera más global, 
fusionando o reescribiendo varios commits a la vez.

##Indica tres situaciones reales donde cherry‑pick es una buena idea (por ejemplo, hotfix en producción, commit en rama equivocada, reutilizar un pequeño cambio en varias ramas).##

-Para aplicar un arreglo urgente de develop a main sin traer todo el historial.

-Mover un commit de una rama a otra sin afectar otras modificaciones.

-Aplicar un mismo cambio a varias ramas sin fusionar todo el historial.

##¿Por qué se recomienda usar git cherry-pick con moderación y no como herramienta principal para integrar ramas?##

Se recomienda usar git cherry-pick con moderación porque puede complicar el historial y generar duplicación de commits.
