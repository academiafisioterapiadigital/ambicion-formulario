# Formulario de entrada · Mastermind Ambición

Página del formulario de entrada de los alumnos de Mastermind Ambición (Academia de Fisioterapia Digital).

- **Publicada en:** https://academiafisioterapiadigital.github.io/ambicion-formulario/
- **Datos:** Supabase (proyecto Academia Fisioterapia Digital), tabla `ejercicio_formulario_entrada`.
- **Acceso:** el alumno escribe su correo y recibe un enlace de acceso (Supabase Auth). Solo puede leer y guardar su propia fila: lo comprueba la base de datos (RLS), no la página.
- **Este repositorio solo contiene las preguntas, que son genéricas.** Ni las respuestas ni lo que ya sabemos de cada alumno se guardan aquí: viven en la base de datos.

## Dar de alta a un alumno nuevo
1. Añadir su correo en `alumnos`.
2. Crear su fila en `ejercicio_formulario_entrada` con `prellenado` (lo que ya sabemos, por pregunta).
3. Enviarle el enlace de la página.
