## ENH-001 - Definir límite máximo de sets por ejercicio

**Prioridad:** Media

**Estado:** Implemented

### Descripción

Actualmente es posible agregar una cantidad indefinida de sets a un ejercicio dentro de una rutina de fuerza.

La funcionalidad opera correctamente, pero no existe una restricción que limite la cantidad máxima de sets que puede configurar el usuario.

### Situación actual

El usuario puede continuar pulsando "Añadir set" sin alcanzar un límite definido.

### Mejora propuesta

Definir una cantidad máxima de sets por ejercicio y evitar que el usuario pueda agregar nuevos sets una vez alcanzado dicho límite.

Por ejemplo:

* Mínimo: 1 set
* Máximo: 10 sets

### Justificación

Un límite explícito permite controlar valores extremos, simplifica las validaciones y evita configuraciones poco realistas o accidentales.

### Criterios de aceptación

* El usuario puede configurar entre 1 y 10 sets por ejercicio.
* Al alcanzar 10 sets, no es posible agregar un set adicional.
* La interfaz comunica correctamente que se alcanzó el límite máximo.

### Casos de prueba asociados

* Añadir 10 sets → se muestran correctamente.
* Intentar añadir el set 11 → no se agrega y permanecen los 10 anteriores.

### Resultado

La mejora fue implementada correctamente y el límite máximo quedó establecido en 10 sets por ejercicio.

## ENH-002 - Definir límite máximo de repeticiones por sets

**Prioridad:** Media

**Estado:** Implemented

### Descripción

Actualmente es posible agregar una cantidad indefinida de repeticiones a un ejercicio dentro de una rutina de fuerza.

La funcionalidad opera correctamente, pero no existe una restricción que limite la cantidad máxima de repeticiones que puede configurar el usuario.

### Situación actual

El usuario puede continuar pulsando "Añadir repetición" sin alcanzar un límite definido.

### Mejora propuesta

Definir una cantidad máxima de repeticiones por sets y evitar que el usuario pueda agregar más repeticiones una vez alcanzado dicho límite.

Por ejemplo:

* Mínimo: 5 repeticiones
* Máximo: 20 repeticiones

### Justificación

Un límite explícito permite controlar valores extremos, simplifica las validaciones y evita configuraciones poco realistas o accidentales.

### Criterios de aceptación

* El usuario puede configurar entre 5 y 20 repeticiones por sets.
* La interfaz comunica correctamente que se alcanzó el límite máximo.

### Casos de prueba asociados

* Configurar 20 repeticiones → valor permitido.
* Intentar bajar de 5 o superar 20 → el valor permanece dentro del rango.

### Resultado

La mejora fue implementada correctamente, el límite máximo quedó establecido en 20 reps por sets y el límite mínimo en 5 reps.

## ENH-003 - Introducir por teclado la cantidad de repeticiones

**Prioridad:** Media

**Estado:** Implemented

### Descripción

Actualmente solo es posible agregar repeticiones pulsando los botones "+" y "-".

La funcionalidad opera correctamente, pero pulsar repetidas veces el botón "+" o "-" hasta alcanzar el límite máximo es frustrante para el usuario.

### Situación actual

El usuario constantemente pulsa los botones "+" o "-" para cada set y ejercicios.

### Mejora propuesta

Agregar la posibilidad de introducir la cantidad de repeticiones deseadas por teclado de forma complementaria a la interfaz de botones.

Por ejemplo:

* Dentro de recuadro que muestra la cantidad de repeticiones, el usuario puede introducir un valor deseado por teclado.

### Justificación

Proporciona una forma más rápida y menos frustrante para el usuario de configurar la cantidad de repeticiones que pulsar constantemente un botón para llegar al límite.

### Criterios de aceptación

* Al introducir un valor por teclado, el recuadro de repeticiones se actualiza instantáneamente.
* El usuario puede configurar entre 5 y 20 repeticiones por sets.
* El usuario puede seguir utilizando los botones "+" y "-" para ajustar la cantidad de repeticiones.
* No se permite introducir valores fuera del rango permitido (5-20).

### Casos de prueba asociados

* Introducir una cantidad válida de repeticiones mediante el teclado.
* Intentar introducir un valor inferior al mínimo: 4 repeticiones.
* Intentar introducir caracteres no numéricos.

### Resultado

La mejora fue implementada correctamente y el usuario puede configurar las repeticiones mediante teclado o utilizando los controles "+" y "-".
