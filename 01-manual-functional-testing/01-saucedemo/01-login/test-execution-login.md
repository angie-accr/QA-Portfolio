## TC-UI-LOGIN-001 — Inicio de sesión con credenciales válidas
- **ID del Caso de Prueba:** TC-UI-LOGIN-001
- **Resultado Esperado:** El sistema debe permitir el acceso y redirigir a la pantalla de inventario de productos.
- **Resultado Obtenido:** El sistema permitió el acceso y mostró la página de inventario con el título "Products" y el catálogo de productos.
- **Estado:** Aprobado
- **Evidencia:** `evidence/TC-UI-LOGIN-001-Aprobado.png`
- **Notas:** Sin observaciones adicionales.

## TC-UI-LOGIN-002 — Inicio de sesión con usuario inválido
- **ID del Caso de Prueba:** TC-UI-LOGIN-002
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que las credenciales son incorrectas.
- **Resultado Obtenido:** El sistema denegó el acceso y mostró el mensaje: "Epic sadface: Username and Aprobadoword do not match any user in this service".
- **Estado:** Aprobado
- **Evidencia:** `evidence/TC-UI-LOGIN-002-Aprobado.png`
- **Notas:** Se observó un posible desbordamiento visual del mensaje de error. Pendiente de investigación.

## TC-UI-LOGIN-003 — Inicio de sesión con contraseña inválida
- **ID del Caso de Prueba:** TC-UI-LOGIN-003
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que las credenciales son incorrectas.
- **Resultado Obtenido:** El sistema denegó el acceso y mostró el mensaje: "Epic sadface: Username and Aprobadoword do not match any user in this service".
- **Estado:** Aprobado
- **Evidencia:** `evidence/TC-UI-LOGIN-003-Aprobado.png`
- **Notas:** Se observó un posible desbordamiento visual del mensaje de error. Pendiente de investigación.

## TC-UI-LOGIN-004 — Inicio de sesión con ambos campos vacíos
- **ID del Caso de Prueba:** TC-UI-LOGIN-004
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que existe un campo obligatorio sin completar.
- **Resultado Obtenido:** El sistema denegó el acceso y mostró el mensaje: "Epic sadface: Username is required".
- **Estado:** Aprobado
- **Evidencia:** `evidence/TC-UI-LOGIN-004-Aprobado.png`
- **Notas:** El mensaje identifica el campo usuario como obligatorio. No se verificó el orden interno de validación de los campos.

## TC-UI-LOGIN-005 — Inicio de sesión con usuario vacío
- **ID del Caso de Prueba:** TC-UI-LOGIN-005
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que el campo usuario es obligatorio.
- **Resultado Obtenido:** El sistema denegó el acceso y mostró el mensaje: "Epic sadface: Username is required".
- **Estado:** Aprobado
- **Evidencia:** `evidence/TC-UI-LOGIN-005-Aprobado.png`
- **Notas:** Sin observaciones adicionales.

## TC-UI-LOGIN-006 — Inicio de sesión con contraseña vacía
- **ID del Caso de Prueba:** TC-UI-LOGIN-006
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que el campo contraseña es obligatorio.
- **Resultado Obtenido:** El sistema denegó el acceso y mostró el mensaje: "Epic sadface: Aprobadoword is required".
- **Estado:** Aprobado
- **Evidencia:** `evidence/TC-UI-LOGIN-006-Aprobado.png`
- **Notas:** Sin observaciones adicionales.



## Resumen de Ejecución de Pruebas — SauceDemo Login

**Proyecto:** SauceDemo — Login Testing  
**Módulo:** Login  
**Tipo de pruebas:** Manual Functional Testing  
**Total de casos de prueba:** 6  

## Resumen de resultados
**Total de Casos de Prueba** 6 
**Ejecutados:** 6 
**Aprobados:** 6 
**Fallidos** 0 
**Bloqueados:** 0 
**No Ejecutados** 0 
**Tasa de Aprobación:** 100% 

## Resultados por caso de prueba
**TC-UI-LOGIN-001:** Inicio de sesión con credenciales válidas *Aprobado*
**TC-UI-LOGIN-002:** Inicio de sesión con usuario inválido *Aprobado*
**TC-UI-LOGIN-003:** Inicio de sesión con contraseña inválida *Aprobado*
**TC-UI-LOGIN-004:** Inicio de sesión con ambos campos vacíos *Aprobado*
**TC-UI-LOGIN-005:** Inicio de sesión con usuario vacío *Aprobado*
**TC-UI-LOGIN-006:** Inicio de sesión con contraseña vacía *Aprobado*

### Observaciones

- En TC-UI-LOGIN-002 y TC-UI-LOGIN-003 se observó un posible desbordamiento visual del contenedor del mensaje de error, que dificulta su lectura completa.
- Esta observación no impidió validar el rechazo de credenciales inválidas.

### Conclusión

Se ejecutaron seis casos de prueba funcionales del módulo Login de SauceDemo, incluyendo escenarios positivos y negativos. De acuerdo con los resultados registrados, los seis casos cumplieron con sus resultados esperados y fueron clasificados como **Aprobado**, obteniendo una tasa de aprobación del **100%**.

**Estado del laboratorio:** Ejecución completada.