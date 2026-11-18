# BUG-UI-LOGIN-001 — Mensaje de error recortado en Google Chrome con ventana maximizada

**Módulo:** Login
**Aplicación:** SauceDemo
**Tipo:** UI / Visual Defect
**Severidad propuesta:** Baja
**Prioridad propuesta:** Media

**Estado:** Confirmado mediante reproducción y evidencia visual.

**Caso relacionado:** TC-UI-LOGIN-002, TC-UI-LOGIN-003.

## Entorno de prueba

- Sistema operativo: Windows 11
- Navegador afectado: Google Chrome 157
- Navegador de comparación: Microsoft Edge
- Zoom: 100%
- Condición: Ventana maximizada

## Precondiciones

El usuario se encuentra en la pantalla de inicio de sesión de SauceDemo.

## Pasos para reproducir

1. Abrir SauceDemo en Google Chrome.
2. Maximizar la ventana del navegador.
3. Ingresar `invalid_user` en el campo Username.
4. Ingresar `secret_sauce` en el campo Password.
5. Hacer clic en Login.
6. Observar el mensaje de error.
7. Repetir la prueba utilizando:
   - Username: `standard_user`
   - Password: `invalid_sauce`
8. Verificar si el mismo recorte visual aparece.

## Resultado esperado

El mensaje de error debe visualizarse completamente dentro de su contenedor, sin recortes ni superposiciones que dificulten la lectura.

## Resultado obtenido

En Google Chrome, con la ventana maximizada, el mensaje de credenciales incorrectas se distribuye en tres líneas. La parte superior de la primera línea y la parte inferior de la última quedan recortadas.

Al reducir el tamaño de la ventana, el mensaje se visualiza correctamente.

En Microsoft Edge maximizado no se observó el mismo recorte.

## Reproducibilidad

El problema se presenta de forma consistente en las pruebas reportadas con Chrome maximizado.

## Evidencias

- `../evidence/TC-002-chrome-half-window.png`
- `../evidence/TC-002-chrome-maximized.png`
- `../evidence/TC-002-edge-maximized.png`

## Impacto

El defecto afecta la legibilidad del mensaje de validación. No impide que el sistema rechace las credenciales incorrectas.

## Observaciones

La causa técnica no ha sido determinada. La condición de reproducción identificada es el uso de Google Chrome con la ventana maximizada.