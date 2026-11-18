# Test Environment — SauceDemo Login Testing

## 1. Información general

- **Proyecto:** SauceDemo — Login Testing
- **Aplicación:** SauceDemo
- **URL:** https://www.saucedemo.com/
- **Módulo:** Login
- **Tipo de pruebas:** Manual Functional Testing
- **Cantidad de casos funcionales:** 6

## 2. Entorno de la ejecución funcional original

- **Sistema operativo:** Windows 11 Home Single Language 26H2
- **Navegador:** Google Chrome.
- **Versión del navegador:** 157.0.8103.79.
- **Zoom:** 100%.
- **Resolución de pantalla:** 1920x1080.
- **Dimensiones del viewport:** 1920x945.
- **Fecha de ejecución:** Noviembre 13 de 2026.

**Observación:** Se documentaron los resultados de los seis casos de prueba funcionales y las características conocidas del entorno utilizado.

## 3. Entorno de investigación del defecto visual

- **Sistema operativo:** Windows 11
- **Navegador afectado:** Google Chrome 157
- **Navegador de comparación:** Microsoft Edge
- **Versión de Microsoft Edge:** 127.0.4341.60.
- **Zoom:** 100%
- **Resolución de pantalla:** 1920x1080.
- **Dimensiones del viewport:** 1920x945.
- **Fecha de investigación:** Noviembre 18 de 2026 .

### Configuraciones evaluadas

| Navegador | Tamaño de ventana | Comportamiento observado |
|---|---|---|
| Google Chrome 157 | Maximizada | El texto del mensaje de error se recorta verticalmente. |
| Google Chrome 157 | Aproximadamente mitad del escritorio | El mensaje se visualiza correctamente. |
| Microsoft Edge | Maximizada | No se observa recorte. |
| Microsoft Edge | Ventana reducida | No se observa recorte. |

## 4. Datos de prueba

**Usuario válido:** `standard_user` 
**Contraseña válida:** `secret_sauce` 
**Usuario inválido:** `invalid_user` 
**Contraseña inválida:** `invalid_sauce` 

Los datos corresponden a los escenarios de práctica definidos para SauceDemo.

## 5. Limitaciones del entorno

- No se dispone de todos los datos técnicos de la ejecución funcional original.
- No se ha determinado la causa técnica del defecto visual.
- La investigación se concentró en los navegadores y tamaños de ventana reportados.
- No se han realizado pruebas exhaustivas de compatibilidad entre navegadores, dispositivos y resoluciones.

## 6. Documentación relacionada

- [Casos de prueba](test-cases-login.md)
- [Reporte de ejecución](test-execution-login.md)
- [Reporte del defecto visual](bug-reports/BUG-UI-LOGIN-001.md)