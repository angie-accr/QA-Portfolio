## TC-UI-LOGIN-001 - Inicio de sesión con credenciales válidas
- **Módulo:** Login
- **Tipo:** Prueba funcional 
- **Precondiciones:** El usuario está registrado y en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario válido (standard_user).
  2. Ingresar contraseña válida (secret_sauce).
  3. Hacer clic en el botón *Login*.
- **Resultado esperado:** Acceso exitoso a la pantalla de inventario de productos.


## TC-UI-LOGIN-002 - Inicio de sesión con usuario inválido
- **Módulo:** Login
- **Tipo:** Prueba funcional 
- **Precondiciones:** El usuario está en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario inválido (invalid_user).
  2. Ingresar contraseña válida (secret_sauce).
  3. Hacer clic en el botón *Login*.
- **Resultado esperado:** Acceso denegado con mensaje de error.

## TC-UI-LOGIN-003 - Inicio de sesión con contraseña inválida
- **Módulo:** Login
- **Tipo:** Prueba funcional 
- **Precondiciones:** El usuario está en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario válido (standard_user).
  2. Ingresar contraseña inválida (invalid_sauce).
  3. Hacer clic en el botón *Login*.
- **Resultado esperado:** Acceso denegado con mensaje de error.


## TC-UI-LOGIN-004 - Inicio de sesión con campos vacíos
- **Módulo:** Login
- **Tipo:** Prueba funcional 
- **Precondiciones:** El usuario está en la pantalla de inicio de sesión.
- **Pasos:**
  1. Verificar que el campo de texto Usuario esté vacío.
  2. Verificar que el campo de texto Contraseña esté vacío.
  3. Hacer clic en el botón *Login*.
- **Resultado esperado:** Acceso denegado con mensaje de error solicitando rellenar los campos vacíos.

## TC-UI-LOGIN-005 - Inicio de sesión con campo de usuario vacío
- **Módulo:** Login
- **Tipo:** Prueba funcional 
- **Precondiciones:** El usuario está en la pantalla de inicio de sesión.
- **Pasos:**
  1. Verificar que el campo de texto Usuario esté vacío.
  2. Ingresar contraseña válida (secret_sauce).
  3. Hacer clic en el botón *Login*.
- **Resultado esperado:** Acceso denegado con mensaje de error solicitando rellenar el campo usuario.

## TC-UI-LOGIN-006 - Inicio de sesión con campo de contraseña vacío
- **Módulo:** Login
- **Tipo:** Prueba funcional 
- **Precondiciones:** El usuario está en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario válido (standard_user).
  2. Verificar que el campo de texto Contraseña esté vacío.
  3. Hacer clic en el botón *Login*.
- **Resultado esperado:** Acceso denegado con mensaje de error solicitando rellenar el campo contraseña.

