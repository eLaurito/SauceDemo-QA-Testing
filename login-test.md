# SAUCE DEMO - LOGIN TEST

## PLAN DE PRUEBAS
* **APP:** WEB SAUCE DEMO
* **MODULO:** Login
* **TESTER:** Ezequiel Laurito Nogueira
* **Versión:** Final
* **Tipo de prueba:** Manual

---

## TC-01 - LOGIN Y PASSWORD VACÍOS

**Precondición:** 
* Estar en la pantalla de login.

**Pasos:**

* Dejar el campo usuario vacío.
* Dejar el campo password vacío.
* pulsar la tecla ENTER.

**Resultado esperado:**
* Impedir el acceso y mostrar un mensaje de error.

**Resultado obtenido:**
* Epic sadface: Username is required

**Estado:**
PASS
 
---

## TC-02 - Usuario vacío y contraseña correcta

**Precondición:** 
* Estar en la pantalla de login.

**Pasos:**

* Dejar el campo usuario vacío.
* Escribir una contraseña correcta.
* pulsar la tecla ENTER.

**Resultado esperado:**
* Impedir el acceso y mostrar un mensaje de error.

**Resultado obtenido:**
* Epic sadface: Username is required

**Estado:**
PASS

---

## TC-03 - Usuario correcto y contraseña vacía

**Precondición:** 
* Estar en la pantalla de login.

**Pasos:**

* Escribir un usuario correcto.
* Dejar vacío el campo Password.
* pulsar la tecla ENTER.

**Resultado esperado:**
* Impedir el acceso, mostrar mensaje de error señalando que el campo Password es obligatorio.

**Resultado obtenido:**
* Epic sadface: Password is required

**Estado:**
PASS

---

## TC-04 - Usuario correcto y contraseña incorrecta

**Precondición:** 
* Estar en la pantalla de login.

**Pasos:**

* Escribir un usuario correcto.
* Escribir una contraseña incorrecta.
* pulsar la tecla ENTER.

**Resultado esperado:**
* Impedir el acceso y mostrar un mensaje indicando que las credenciales no son válidas.

**Resultado obtenido:**
* Epic sadface: Username and password do not match any user in this service

**Estado:**
PASS

---

## TC-05 - USUARIO INCORRECTO Y CONTRASEÑA CORRECTA

**Precondición:** 
* Estar en la pantalla de login.

**Pasos:**

* Escribir un usuario inexistente.
* Escribir una contraseña correcta.
* pulsar la tecla ENTER.

**Resultado esperado:**
* Impedir el acceso y mostrar un mensaje indicando que las credenciales no son válidas.

**Resultado obtenido:**
* Mensaje mostrado: 'Epic sadface: Username and password do not match any user in this service'

**Estado:**
PASS

---

## TC-06 - Usuario incorrecto + contraseña incorrecta

**Precondición:** 
* Estar en la pantalla de login.

**Pasos:**

* Escribir un usuario inexistente.
* Escribir una contraseña incorrecta.
* pulsar la tecla ENTER.

**Resultado esperado:**
* Impedir el acceso y mostrar un mensaje indicando que las credenciales no son válidas.

**Resultado obtenido:**
* Mensaje mostrado: 'Epic sadface: Username and password do not match any user in this service'

**Estado:**
PASS

---

## TC-07 - Usuario y contraseña correctos

**Precondición:** 
* Estar en la pantalla de login.

**Pasos:**

* Escribir un usuario correcto.
* Escribir una contraseña correcta para ese usuario.
* pulsar la tecla ENTER.

**Resultado esperado:**
* Permitir el acceso y redirigir al usuario a la página de productos.

**Resultado obtenido:**
* Es redirigido a /inventory.html sin complicaciones.

**Estado:**
PASS

---
