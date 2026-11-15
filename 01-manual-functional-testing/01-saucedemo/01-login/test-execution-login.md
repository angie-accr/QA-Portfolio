## TC-UI-LOGIN-001 — Login exitoso
- **Test Case ID:** TC-UI-LOGIN-001
- **Expected Result:** Acceso exitoso a la pantalla de inventario de productos.
- **Actual Result:** El usuario inició sesión con credenciales válidas. Se mostró la página de inventario con el título "Products" y los productos.
- **Status:** Pass
- **Evidence:** Captura guardada (evidence/TC-UI-LOGIN-001-pass.png).
- **Notes:** Sin observaciones adicionales.


## TC-UI-LOGIN-002 — Login denegado
- **Test Case ID:** TC-UI-LOGIN-002
- **Expected Result:** Acceso denegado con mensaje de error.
- **Actual Result:** El usuario ingresó un usuario inválido. Se mostró mensaje de error informando que el usuario y contraseña no coinciden con ningún usuario. "Epic sadface: Username and password do not match any user in this service".
- **Status:** Pass
- **Evidence:** Captura guardada (evidence/TC-UI-LOGIN-002-pass.png).
- **Notes:** Se observó un posible problema visual en el contenedor del mensaje de error. El texto parece desbordar el área disponible, dificultando su lectura completa. 


## TC-UI-LOGIN-003 — Login denegado
- **Test Case ID:** TC-UI-LOGIN-003
- **Expected Result:** Acceso denegado con mensaje de error.
- **Actual Result:** El usuario ingresó una contraseña inválida. Se mostró mensaje de error informando que el usuario y contraseña no coinciden con ningún usuario."Epic sadface: Username and password do not match any user in this service".
- **Status:** Pass
- **Evidence:** Captura guardada (evidence/TC-UI-LOGIN-003-pass.png).
- **Notes:** Se observó un posible problema visual en el contenedor del mensaje de error. El texto parece desbordar el área disponible, dificultando su lectura completa. 


## TC-UI-LOGIN-004 — Login denegado
- **Test Case ID:** TC-UI-LOGIN-004
- **Expected Result:** Acceso denegado con mensaje de error solicitando rellenar los campos vacíos.
- **Actual Result:** El usuario no ingresó información en los campos usuario y contraseña. Se mostró mensaje de error solicitando ingresar el usuario "Epic sadface: Username is required".
- **Status:** Pass
- **Evidence:** Captura guardada (evidence/TC-UI-LOGIN-004-pass.png).
- **Notes:** Sin observaciones adicionales.

## TC-UI-LOGIN-005 — Login denegado
- **Test Case ID:** TC-UI-LOGIN-005
- **Expected Result:** Acceso denegado con mensaje de error solicitando rellenar el campo usuario.
- **Actual Result:** El usuario no ingresó información en el campo usuario. Se mostró mensaje de error solicitando ingresar el usuario "Epic sadface: Username is required".
- **Status:** Pass
- **Evidence:** Captura guardada (evidence/TC-UI-LOGIN-005-pass.png).
- **Notes:** Sin observaciones adicionales.

## TC-UI-LOGIN-006 — Login denegado
- **Test Case ID:** TC-UI-LOGIN-006
- **Expected Result:** Acceso denegado con mensaje de error solicitando rellenar el campo contraseña.
- **Actual Result:** El usuario no ingresó información en el campo contraseña. Se mostró mensaje de error solicitando ingresar la contraseña "Epic sadface: Password is required".
- **Status:** Pass
- **Evidence:** Captura guardada (evidence/TC-UI-LOGIN-006-pass.png).
- **Notes:** Sin observaciones adicionales.



## Test Execution Summary — SauceDemo Login

**Proyecto:** SauceDemo — Login Testing  
**Módulo:** Login  
**Tipo de pruebas:** Manual Functional Testing  
**Total de casos de prueba:** 6  

## Resumen de resultados
**Total Test Cases** 6 
**Executed:** 6 
**Passed:** 6 
**Failed** 0 
**Blocked:** 0 
**Not Run** 0 
**Pass Rate:** 100% 

## Resultados por caso de prueba
**TC-UI-LOGIN-001:** Inicio de sesión con credenciales válidas *Pass*
**TC-UI-LOGIN-002:** Inicio de sesión con usuario inválido *Pass*
**TC-UI-LOGIN-003:** Inicio de sesión con contraseña inválida *Pass*
**TC-UI-LOGIN-004:** Inicio de sesión con ambos campos vacíos *Pass*
**TC-UI-LOGIN-005:** Inicio de sesión con usuario vacío *Pass*
**TC-UI-LOGIN-006:** Inicio de sesión con contraseña vacía *Pass*

### Observaciones

- En TC-UI-LOGIN-002 y TC-UI-LOGIN-003 se observó un posible desbordamiento visual del contenedor del mensaje de error, que dificulta su lectura completa.
- Esta observación no impidió validar el rechazo de credenciales inválidas.

### Conclusión

Se ejecutaron seis casos de prueba funcionales del módulo Login de SauceDemo, incluyendo escenarios positivos y negativos. De acuerdo con los resultados registrados, los seis casos cumplieron con sus resultados esperados y fueron clasificados como **Pass**, obteniendo una tasa de aprobación del **100%**.

**Estado del laboratorio:** Ejecución completada. 
