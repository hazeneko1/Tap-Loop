# Tap Loop
### Automatización inteligente por acciones en Android

Tap Loop es una aplicación Android de automatización avanzada que permite crear **flujos de acciones configurables**, ejecutar **clics inteligentes**, gestionar **bucles**, y automatizar interacciones con otras aplicaciones **sin necesidad de root**.

Pensada para usuarios avanzados, testing y automatización de tareas repetitivas.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Características principales

- Apertura y cierre automático de aplicaciones
- Clics automáticos por **texto, descripción o ID**
- Cierre inteligente de anuncios
- Ejecución de acciones en **bucle**
- Control total del tiempo, frecuencia y repeticiones
- Acciones encadenadas en flujos personalizables
- Persistencia de datos incluso tras desinstalar la app
- Herramientas de **debug visual** integradas

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🧠 Concepto de funcionamiento

Tap Loop funciona mediante **acciones secuenciales** que se ejecutan en orden.  
Cada acción es configurable y puede repetirse de forma controlada.

Un flujo típico sería:

1. Abrir una aplicación
2. Esperar unos segundos
3. Pulsar un botón concreto por texto o descripción
4. Repetir la acción en bucle
5. Cerrar la aplicación

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## ⚙️ Configuración de acciones

Cada acción dispone de los siguientes parámetros (en segundos):

1. **Delay inicial**  
   Tiempo de espera antes de ejecutar la acción.

2. **Intervalo de repetición**  
   Cada cuánto tiempo se repite la acción.

3. **Número de repeticiones**  
   Cuántas veces se ejecutará la acción.

4. **Doble ejecución por intento**  
   Opción para ejecutar la acción **dos veces seguidas**.

5. **Delay de la segunda ejecución**  
   Tiempo de espera entre la primera y la segunda ejecución.

---

## 📦 Cómo obtener el nombre del paquete de una app

Para configurar correctamente una acción sobre otra aplicación:

1. Busca la app objetivo en **Google Play**
2. Pulsa en **Compartir**
3. Copia el enlace
4. Al pegarlo, aparecerá el **nombre del paquete**  
   (ejemplo: `com.example.app`)

Ese nombre es el que debes usar en Tap Loop.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 💾 Guardado y persistencia de datos

Tap Loop permite guardar de forma persistente:

- Nombre del paquete de la app
- Valores de los campos de las acciones
- Listas completas de acciones
- Flujos configurados

📌 **Los datos permanecen guardados incluso si desinstalas la app**.

Para guardar:
1. Pulsa el botón **Guardar**
2. Accede desde el botón de **carpeta** o el **menú**

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🛠️ Botón flotante (Debug & Control)

Tap Loop incluye un **botón flotante** con opciones avanzadas:

### 🔍 Debug de pantalla
- Realiza un **volcado completo** de todos los elementos visibles
- Muestra:
  - Texto
  - Descripción
  - ID interno
- Muy útil cuando un botón no tiene texto visible

Ejemplo:
text
CashoutActivity.NavIconBack

📄 Licencia

Este proyecto se distribuye bajo la licencia **GNU GPL v3**.

Cualquier uso, modificación o distribución debe cumplir los términos de dicha licencia.
