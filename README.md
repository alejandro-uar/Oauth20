# Authentication Oauth 2.0 + Nestjs

## Strategy: Google

- El usuario accede a /auth/google para iniciar el proceso de autenticación.
- Google muestra la pantalla de inicio de sesión y autorización.
- Una vez autenticado y autorizado, Google redirige al usuario a /auth/google/redirect, pasando la información del usuario.
- La aplicación procesa esta información y devuelve los datos del usuario autenticado en la respuesta.
