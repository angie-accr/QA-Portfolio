## TC-UI-LOGIN-001 — Inicio de sesión con credenciales válidas
- **Módulo:** Login
- **Tipo:** Prueba funcional
- **Precondiciones:** El usuario está registrado y se encuentra en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario válido (`standard_user`).
  2. Ingresar contraseña válida (`secret_sauce`).
  3. Hacer clic en el botón *Login*.
- **Resultado Esperado:** El sistema debe permitir el acceso y redirigir a la pantalla de inventario de productos.

## TC-UI-LOGIN-002 — Inicio de sesión con usuario inválido
- **Módulo:** Login
- **Tipo:** Prueba funcional
- **Precondiciones:** El usuario se encuentra en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario inválido (`invalid_user`).
  2. Ingresar contraseña válida (`secret_sauce`).
  3. Hacer clic en el botón *Login*.
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que las credenciales son incorrectas.

## TC-UI-LOGIN-003 — Inicio de sesión con contraseña inválida
- **Módulo:** Login
- **Tipo:** Prueba funcional
- **Precondiciones:** El usuario se encuentra en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario válido (`standard_user`).
  2. Ingresar contraseña inválida (`invalid_sauce`).
  3. Hacer clic en el botón *Login*.
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que las credenciales son incorrectas.

## TC-UI-LOGIN-004 — Inicio de sesión con ambos campos vacíos
- **Módulo:** Login
- **Tipo:** Prueba funcional
- **Precondiciones:** El usuario se encuentra en la pantalla de inicio de sesión.
- **Pasos:**
  1. Verificar que el campo usuario esté vacío.
  2. Verificar que el campo contraseña esté vacío.
  3. Hacer clic en el botón *Login*.
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que existe un campo obligatorio sin completar.

## TC-UI-LOGIN-005 — Inicio de sesión con usuario vacío
- **Módulo:** Login
- **Tipo:** Prueba funcional
- **Precondiciones:** El usuario se encuentra en la pantalla de inicio de sesión.
- **Pasos:**
  1. Verificar que el campo usuario esté vacío.
  2. Ingresar contraseña válida (`secret_sauce`).
  3. Hacer clic en el botón *Login*.
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que el campo usuario es obligatorio.

## TC-UI-LOGIN-006 — Inicio de sesión con contraseña vacía
- **Módulo:** Login
- **Tipo:** Prueba funcional
- **Precondiciones:** El usuario se encuentra en la pantalla de inicio de sesión.
- **Pasos:**
  1. Ingresar usuario válido (`standard_user`).
  2. Verificar que el campo contraseña esté vacío.
  3. Hacer clic en el botón *Login*.
- **Resultado Esperado:** El sistema debe denegar el acceso y mostrar un mensaje de error indicando que el campo contraseña es obligatorio.