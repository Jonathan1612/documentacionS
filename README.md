# Documentacion de commits Git

**Tipo de commit:**

Comienza tu mensaje de commit con un tipo que indique la naturaleza del cambio. Algunos ejemplos comunes son:

***feat***: para nuevas características.

```
git commit -m "feat(usuario): Agrega la funcionalidad de cambiar la foto de perfil

Implementa una nueva característica que permite a los usuarios cambiar su foto de perfil desde la configuración del perfil."
```

***fix***: para corrección de errores.

```
git commit -m "fix(validación): Corrige la validación de contraseñas débiles

Se corrigió un error que permitía contraseñas débiles no cumplir con los requisitos mínimos de seguridad."
```

***docs***: para cambios en la documentación.

```
git commit -m "docs(readme): Actualiza el README con ejemplos de uso

Se mejoró la documentación del proyecto incluyendo ejemplos de uso y configuración."
```

***style***: para cambios en el formato del código (sin cambios en la lógica).

```
git commit -m "style(css): Alinea las reglas CSS en el archivo de estilos principal

Se aplicaron cambios en el formato del código para mejorar la legibilidad del archivo CSS principal."
```

***refactor***: para refactorización de código.

```
git commit -m "refactor(api): Reorganiza la lógica de autenticación en el servicio Auth

Se refactorizó el servicio de autenticación para mejorar la modularidad y facilitar el mantenimiento."
```

***test***: para la adición de pruebas.

```
git commit -m "test(auth): Agrega pruebas unitarias para la función de autenticación

Se introdujeron nuevas pruebas unitarias para garantizar la robustez y fiabilidad de la función de autenticación."
```

***chore***: para tareas de construcción y otras tareas no relacionadas con el código.

```
git commit -m "chore(build): Actualiza las dependencias del sistema de construcción

Este commit actualiza las versiones de las herramientas de construcción y sus dependencias para garantizar la compatibilidad con las últimas versiones."
```