# Pruebas del kit

Registros reales de las pruebas hechas el 23-10-2026 sobre una copia limpia del kit, con una
sesión nueva de Claude Code que no conocía el proyecto. Las rutas que aparecen (`/tmp/...`,
`kit-equipo-ia/`, `pruebas/kit-e2e/`) son las de esa copia y del repositorio donde se construyó.

| Archivo | Qué demuestra |
|---|---|
| `salida_turno.txt` | Un turno completo: constructor, revisor (PASA), informador y commit |
| `T01-archivos.md` | El resultado de la tarea de prueba, con el comando y su salida real |
| `TAREAS-tras-turno.md`, `MEMORIA-tras-turno.md`, `git-log.txt` | El estado y la memoria que dejó el turno |
| `salida_permisos.txt` | Editar en `publicado/` con la herramienta de edición se rechaza |
| `salida_permisos_env.txt` | Leer `.env` con la herramienta de lectura se rechaza (prompt, ruta y llamada exactos) |
| `casos-con-errores-TAREAS.md`, `salida_comprobador_errores.txt` | El comprobador detecta 6 de 6 errores provocados |
| `revision-independiente*.txt` | Tres revisiones independientes: las dos primeras dieron FALLA y se corrigió; la tercera, PASA |
