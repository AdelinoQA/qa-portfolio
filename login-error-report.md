# Reporte de Bug: Error en validación de login

**ID:** BUG-001  
**Fecha:** 25/07/2025  
**Reportado por:** Adelis Graterol  
**Severidad:** Alta  
**Prioridad:** Alta  

## Descripción
Al ingresar credenciales incorrectas en el formulario de login, no se muestra el mensaje de error esperado.

## Pasos para reproducir
1. Ir a la página de login.
2. Ingresar usuario válido y contraseña incorrecta.
3. Click en "Iniciar sesión".

## Resultado esperado
Se debe mostrar un mensaje de error: `"Usuario o contraseña incorrectos"`.

## Resultado obtenido
La página se recarga sin mostrar ningún mensaje.

## Entorno
- Navegador: Chrome 114
- SO: Windows 10
- URL: https://demoapp.com/login