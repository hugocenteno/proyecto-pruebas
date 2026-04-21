# Recuperación de archivo eliminado

En esta práctica se ha simulado la eliminación accidental del archivo errores.sh.

Primero se creó el archivo y se añadió al repositorio mediante un commit. Posteriormente, se eliminó el archivo de forma intencionada y se confirmó el cambio con otro commit.

Para recuperar el archivo, se utilizó el comando git reflog, que permite ver el historial de movimientos de HEAD. Gracias a esto, se identificó el estado anterior donde el archivo aún existía.

Después se utilizó el comando git checkout HEAD@{1} -- errores.sh para restaurar el archivo eliminado.

Finalmente, se volvió a añadir el archivo al repositorio y se realizó un nuevo commit.

Esta práctica ha permitido entender cómo recuperar archivos eliminados y la importancia de herramientas como git reflog en la gestión de errores.
