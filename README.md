# Versiones de las placas

Este repositorio es **público** a propósito y solo tiene `versiones.json`: la **última
versión** de cada placa (número, fecha y qué cambia). **Nada de código ni de contraseñas.**

Las páginas web de las placas leen este archivo desde el navegador y, al lado de su versión,
enseñan:

- ✅ — está al día.
- ⬆ vX — en GitHub hay una versión más nueva (pasando el ratón se ve la fecha y qué cambia).
- ⚪ — no se ha podido comprobar (el móvil o PC con el que la miras no tiene internet).

Por ahora lo usan la **cámara (cam1)**, desde su versión v1.0, y la **cámara con caras (cam1_facial)**, desde su versión v2.0.

## Al sacar una versión nueva de una placa

Cambia su línea en `versiones.json` (versión, fecha y cambios). La versión tiene que ser
**exactamente igual** a la que enseña la placa: si no coincide, la placa dirá que hay una
versión nueva.

GitHub guarda el archivo en caché unos 5 minutos: el aviso puede tardar eso en aparecer.
