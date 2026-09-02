# Test Cases

## TC-ROUTINE-001 - Crear rutina de fuerza utilizando un ejercicio existente

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que se pueda crear una rutina de fuerza correctamente.

### Precondiciones:
  - Usuario se encuentra en pantalla rutinas

### Datos de prueba:
  - Nombre de rutina: Push Day
  - Ejercicio: Chain Press

### Pasos:
  1. Pulsar en el botón "+".
  2. Seleccionar rutina de fuerza.
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Pulsar la barra de búsqueda.
  6. Introducir "Chain Press".
  7. Seleccionar el ejercicio "Chain Press" de la lista.
  8. Pulsar el botón "Crear Rutina".

### Resultado esperado:
  - La rutina se crea correctamente.
  - La rutina se muestra en la lista de rutinas.
  - El nombre y los ejercicios permanecen asociados a la rutina.

## TC-ROUTINE-002 - Crear rutina de fuerza creando un ejercicio personalizado

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que se pueda crear una rutina de fuerza correctamente con un ejercicio personalizado.

### Precondiciones:
  - Usuario se encuentra en pantalla rutinas

### Datos de prueba:
  - Nombre de rutina: Push Day
  - Ejercicio: Press Banca
  - Músculo principal: Pectorales

### Pasos:
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Pulsar "Crear ejercicio personalizado".
  6. Introducir "Press Banca" como nombre del ejercicio.
  7. Pulsar el botón de siguiente.
  8. Abrir la selección de músculo principal.
  9. Seleccionar "Pectorales".
  10. Pulsar "Crear ejercicio".
  11. Pulsar "Crear rutina".

### Resultado esperado:
  - La rutina "Push Day" se crea correctamente.
  - La rutina se muestra en la lista de rutinas.
  - La rutina contiene los ejercicios "Press Banca".

## TC-ROUTINE-003 - Crear rutina de cardio correctamente

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que sea posible crear una rutina de cardio utilizando un ejercicio existente.

### Precondiciones:
- Usuario se encuentra en pantalla rutinas

### Datos de prueba:
- Nombre de rutina: Cardio Matutino
- Ejercicio: Bicicleta estática

### Pasos:
  1. Pulsar en el botón "+".
  2. Seleccionar rutina de cardio.
  3. Introducir el nombre "Cardio Matutino".
  4. Pulsar el botón de confirmación.
  5. Pulsar "Seleccionar ejercicios".
  6. Seleccionar el ejercicio "Bicicleta estática".
  7. Pulsar el botón "Ok".
  8. Pulsar el botón "Crear Rutina".

### Resultado esperado:
  - La rutina "Cardio Matutino" se crea correctamente.
  - La rutina se muestra en la lista de rutinas.
  - La rutina contiene los ejercicios "Bicicleta estática".

## TC-ROUTINE-004 - Intentar crear rutina sin nombre

**Prioridad**: Alta

**Tipo**: Funcional / Negativo

**Estado**: Passed

**Descripción**: Verificar que no sea posible crear una rutina sin nombre.

### Precondiciones:
- Usuario se encuentra en pantalla rutinas

### Datos de prueba:
  - Ejercicios: Chain Press

### Pasos:
  1. Pulsar en el botón "+".
  2. Seleccionar rutina de fuerza.
  3. Pulsar la barra de búsqueda.
  4. Introducir "Chain Press".
  5. Seleccionar el ejercicio "Chain Press" de la lista.
  6. Pulsar el botón "Crear Rutina".

### Resultado esperado:
  - El botón "Crear rutina" permanece deshabilitado mientras el campo de nombre esté vacío.

## TC-ROUTINE-005 - Eliminar rutina

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que sea posible eliminar una rutina.

### Precondiciones:
  - Usuario se encuentra en pantalla rutinas.
  - La rutina existe en la lista de rutinas.

### Datos de prueba:
  - Rutina: Push Day

### Pasos:
  1. Pulsar en el botón de opciones de la rutina.
  2. Pulsar en el botón de "Eliminar Rutina".

### Resultado esperado:
  - La rutina se elimina correctamente.
  - La rutina no aparece en la lista de rutinas.
  - La lista de rutinas se actualiza correctamente.

## TC-ROUTINE-006 - Crear rutina con diferente cantidad de repeticiones por set

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que se pueda crear una rutina de fuerza configurando varios sets.

### Precondiciones:
  - Usuario se encuentra en pantalla rutinas.
  - El ejercicio "Chain Press" está añadido a la rutina.
  - El ejercicio contiene al menos 3 sets.

### Datos de prueba:
  - Ejercicio: Chain Press
  - Set 1: 12 repeticiones
  - Set 2: 10 repeticiones
  - Set 3: 8 repeticiones

### Pasos:
  1. Localizar el ejercicio "Chain Press".
  2. Configurar 12 repeticiones en el primer set.
  3. Configurar 10 repeticiones en el segundo set.
  4. Configurar 8 repeticiones en el tercer set.
  5. Pulsar "Crear rutina".
  6. Volver a abrir la rutina creada.

### Resultado esperado:
  - La rutina se crea correctamente.
  - El ejercicio "Chain Press" conserva los 3 sets configurados.
  - El primer set mantiene 12 repeticiones.
  - El segundo set mantiene 10 repeticiones.
  - El tercer set mantiene 8 repeticiones.
  - Los valores permanecen asociados al set correspondiente al volver a abrir la rutina.

## TC-ROUTINE-007 - Crear rutina de fuerza con varios sets por ejercicio

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que sea posible configurar y guardar diferentes cantidades de repeticiones para los sets de un mismo ejercicio.

### Precondiciones:
  - El usuario se encuentra creando una rutina de fuerza.

### Datos de prueba:
  - Nombre de rutina: Push Day
  - Ejercicio 1: Chain Press
  - Ejercicio 2: Cable Chest Press
  - Sets esperados por ejercicio: 4

### Pasos:
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Pulsar la barra de búsqueda.
  6. Introducir "Chain Press".
  7. Seleccionar "Chain Press" de la lista.
  8. Pulsar nuevamente la barra de búsqueda.
  9. Introducir "Cable Chest Press".
  10. Seleccionar "Cable Chest Press" de la lista.
  11. Pulsar "Añadir set" en "Chain Press".
  12. Pulsar "Añadir set" en "Cable Chest Press".
  13. Pulsar "Crear rutina".

### Resultado esperado:
  - La rutina "Push Day" se crea correctamente.
  - La rutina contiene los ejercicios "Chain Press" y "Cable Chest Press".
  - Cada ejercicio conserva los sets configurados.
  - "Chain Press" queda configurado con 4 sets.
  - "Cable Chest Press" queda configurado con 4 sets.

## TC-ROUTINE-008 - Crear rutina de cardio configurando duración del ejercicio
  
  **Prioridad**: Alta
  
  **Tipo**: Funcional / Positivo
  
  **Estado**: Passed
  
  **Descripción**: Verificar que sea posible configurar y guardar una duración de 10 minutos para un ejercicio dentro de una rutina de cardio.
  
### Precondiciones:
  
  - Usuario se encuentra en pantalla rutinas.
  
### Datos de prueba:
  
  - Nombre de rutina: Cardio Matutino
  - Ejercicio: Bicicleta estática
  - Duración: 10 minutos
  
### Pasos:
  
  1. Pulsar en el botón "+".
  2. Seleccionar rutina de cardio.
  3. Introducir el nombre "Cardio Matutino".
  4. Pulsar el botón de confirmación.
  5. Pulsar "Seleccionar ejercicios".
  6. Seleccionar el ejercicio "Bicicleta estática".
  7. Pulsar el botón "Ok".
  8. Mover el slider de duración de "Bicicleta estática" hasta configurar 10 minutos.
  9. Pulsar el botón "Crear Rutina".
  10. Volver a abrir la rutina "Cardio Matutino".
  
### Resultado esperado:
  
  - La rutina "Cardio Matutino" se crea correctamente.
  - La rutina contiene el ejercicio "Bicicleta estática".
  - El ejercicio queda configurado con una duración de 10 minutos.
  - La duración de 10 minutos se mantiene al volver a abrir la rutina.

___
## TC-REMINDER-001 - Crear recordatorio para la rutina correctamente

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que sea posible crear un recordatorio para la rutina de cardio.

### Precondiciones:
  - Usuario se encuentra en pantalla rutinas
  - Rutina de cardio creada

### Datos de prueba:
  - Rutina: Cardio Matutino
  - Días de la semana: Lunes, Miércoles, Viernes
  - Hora: 08:00 AM

### Pasos: 
  1. Pulsar en el botón de "recordatorio" de la rutina de cardio.
  2. Seleccionar los días de la semana "Lunes", "Miércoles", "Viernes".
  3. Seleccionar la hora del recordatorio "08:00 AM".
  4. Pulsar el botón "Guardar".

### Resultado esperado: 
  - El recordatorio se crea correctamente.
  - Los días seleccionados se guardan correctamente.
  - La hora seleccionada se guarda correctamente.
  - El icono cambia a un icono de recordatorio activo.

## TC-REMINDER-002 - Eliminar recordatorio para la rutina correctamente

**Prioridad**: Alta

**Tipo**: Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que sea posible eliminar un recordatorio para la rutina de cardio.

### Precondiciones:
  - Usuario se encuentra en la pantalla "Rutinas"
  - Rutina de cardio creada

### Datos de prueba:
  - Rutina: Cardio Matutino

### Pasos: 
  1. Pulsar en el botón "recordatorio" de la rutina de Cardio Matutino.
  2. Pulsar en el botón de "Eliminar".

### Resultado esperado: 
  - El recordatorio se elimina correctamente.
  - El icono cambia a un icono de recordatorio inactivo.

___
## TC-TIMER-001 - Mantener cronómetro al enviar la aplicación a segundo plano

**Prioridad:** Alta  

**Tipo:** Funcional / Persistencia

**Estado**: Passed

**Descripción**: Verificar que el cronómetro se mantenga activo al enviar la aplicación a segundo plano.

### Precondiciones

  - Existe una rutina válida.
  - Se ha iniciado un entrenamiento.

### Pasos

  1. Iniciar el cronómetro del entrenamiento.
  2. Esperar 30 segundos.
  3. Enviar la aplicación a segundo plano.
  4. Esperar 2 minutos.
  5. Volver a abrir la aplicación.

### Resultado esperado

  - El entrenamiento continúa activo.
  - El tiempo transcurrido incluye el periodo en segundo plano.
  - No se pierde información del entrenamiento.
    
## TC-TIMER-002 - Pausar cronómetro

**Prioridad:** Alta  

**Tipo:** Funcional / Persistencia

**Estado**: Passed

**Descripción**: Verificar que el cronómetro se pausa correctamente y no se reinicia al reanudar.

### Precondiciones

  - Existe una rutina válida.
  - Se ha iniciado un entrenamiento.

### Pasos

  1. Iniciar el cronómetro del entrenamiento.
  2. Pausar el cronómetro.
  3. Esperar 2 minutos.
  4. Reanudar el cronómetro.

### Resultado esperado

  - El cronómetro se pausa.
  - El tiempo transcurrido no se reinicia al reanudar el cronómetro.

___
## TC-WORKOUT-001 - Completar entrenamiento de fuerza con todos los ejercicios

**Prioridad:** Alta  

**Tipo:** Funcional / Positivo

**Estado**: Passed

**Descripción**: Verificar que el usuario pueda completar correctamente un entrenamiento de fuerza realizando todos los ejercicios de la rutina.

### Precondiciones

  - El usuario se encuentra en la pantalla de rutinas.
  - Existe una rutina de fuerza con al menos dos ejercicios.
  - La rutina contiene series configuradas.

### Datos de prueba

  - Rutina: Push Day
  - Ejercicio 1: Press Banca
  - Ejercicio 2: Press Militar
  - Repeticiones: 10

### Pasos:
  1. Seleccionar la rutina "Push Day".
  2. Pulsar "Iniciar entrenamiento".
  3. Completar todas las series restantes de "Press Banca".
  4. Continuar con "Press Militar".
  5. Completar todas las series configuradas del ejercicio.
  6. Verificar que todos los ejercicios aparezcan como completados.
  7. Pulsar "Finalizar".

### Resultado esperado:

  - Todas las series pueden registrarse y marcarse como completadas.
  - Todos los ejercicios quedan identificados como completados.
  - El entrenamiento puede finalizar correctamente.
  - El entrenamiento completado queda registrado en el historial.
  - Los datos registrados durante el entrenamiento se mantienen correctamente.

## TC-WORKOUT-002 - Finalizar entrenamiento de fuerza con ejercicios incompletos

**Prioridad:** Alta

**Tipo:** Funcional / Positivo

**Estado:** Passed

**Descripción:** Verificar el comportamiento de la aplicación al finalizar un entrenamiento de fuerza sin completar todos los ejercicios de la rutina.

### Precondiciones

  - El usuario se encuentra en la pantalla de rutinas.
  - Existe una rutina de fuerza con al menos dos ejercicios.
  - La rutina contiene series configuradas.

### Datos de prueba

  - Rutina: Push Day
  - Ejercicio 1: Press Banca
  - Ejercicio 2: Press Militar
  - Repeticiones: 10

### Pasos

  1. Seleccionar la rutina "Push Day".
  2. Pulsar "Iniciar entrenamiento".
  3. Completar todas las series de "Press Banca".
  4. Dejar sin completar las series de "Press Militar".
  5. Pulsar "Finalizar".

### Resultado esperado

  - La aplicación permite finalizar el entrenamiento aunque existan ejercicios o series sin completar.
  - Las series completadas de "Press Banca" conservan sus datos.
  - Los ejercicios y series no completadas no se registran en el historial.
  - El entrenamiento queda registrado en el historial.
  - El registro del entrenamiento refleja correctamente que no se completaron todos los ejercicios.

## TC-WORKOUT-003 - Completar entrenamiento de cardio
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el usuario pueda completar correctamente un entrenamiento de cardio utilizando el temporizador configurado para el ejercicio.
  
### Precondiciones
  
  - El usuario se encuentra en la pantalla de rutinas.
  - Existe una rutina de cardio con un ejercicio configurado.
  - El ejercicio tiene una duración definida.
  
### Datos de prueba
  
  - Rutina: Cardio Matutino
  - Ejercicio: Bicicleta estática
  - Duración: 10 minutos
  
### Pasos
  
  1. Seleccionar la rutina "Cardio Matutino".
  2. Pulsar "Iniciar".
  3. Verificar que el temporizador comience desde 10 minutos.
  4. Verificar que el tiempo restante disminuya a medida que avanza el entrenamiento.
  5. Mantener el entrenamiento activo hasta que el temporizador llegue a 00:00.
  6. Verificar que el ejercicio se marque como completado al finalizar el temporizador.
  7. Pulsar "Finalizar".
  
### Resultado esperado
  
  - El temporizador inicia con una duración de 10 minutos.
  - El tiempo restante disminuye correctamente mientras el cronómetro está activo.
  - El temporizador finaliza en 00:00.
  - El ejercicio queda identificado como completado al terminar su duración.
  - La rutina puede finalizar correctamente.
  - El entrenamiento queda registrado en el historial.
  - La duración y los datos del entrenamiento se guardan correctamente.

___
## TC-SHARE-001 - Generar imagen de rutina para compartir
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que se genere correctamente una imagen PNG con la información de una rutina y se abra el menú nativo de compartir del dispositivo.
  
### Precondiciones
  
  - El usuario se encuentra en la pantalla de historial.
  - Existe una rutina completada con un ejercicio configurado.
  
### Datos de prueba
  
  - Rutina: Push Day
  
### Pasos
  
  1. Localizar la rutina "Push Day" en el historial.
  2. Seleccionar la rutina "Push Day".
  3. Pulsar "Compartir".
  4. Seleccionar el diseño.
  5. Pulsar "Compartir".
  6. Verificar que se abra el menú nativo de compartir del dispositivo.
  
### Resultado esperado
  
  - Se genera correctamente una imagen PNG de la rutina.
  - La imagen contiene la información correspondiente a "Push Day".
  - Se abre el menú nativo de compartir del dispositivo con la imagen generada disponible para compartir.

## TC-SHARE-002 - Compartir imagen de rutina mediante WhatsApp
  
  **Prioridad:** Media
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que la imagen generada de una rutina pueda compartirse correctamente mediante WhatsApp.

### Precondiciones
  
  - Existe una rutina completada con un ejercicio configurado.
  - El usuario tiene WhatsApp instalado en el dispositivo.
  - WhatsApp está configurado para el uso general.
  
### Datos de prueba
  
  - Rutina: Push Day
  - Aplicación: WhatsApp
  
### Pasos
  
  1. Localizar la rutina "Push Day" en el historial.
  2. Seleccionar la rutina "Push Day".
  3. Pulsar "Compartir".
  4. Seleccionar el diseño.
  5. Pulsar "Compartir".
  6. Verificar que se abra el menú nativo de compartir del dispositivo.
  7. Seleccionar WhatsApp.
  8. Seleccionar destinatario de prueba.
  9. Enviar la imagen.
  
### Resultado esperado
  
  - WhatsApp se abre correctamente desde el menú nativo de compartir del dispositivo.
  - La imagen generada se adjunta correctamente al mensaje de WhatsApp.
  - La imagen se envía correctamente al destinatario seleccionado.
  - La imagen no presenta elementos cortados, superpuestos o fuera del área visible.

___
## TC-REPORT-001 - Visualizar estadísticas mensuales
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que la pantalla "Reporte" muestre correctamente las estadísticas correspondientes a los entrenamientos realizados durante el mes actual.

### Precondiciones
  
  - Existen entrenamientos completados durante el mes actual.
  - Los entrenamientos se encuentran registrados correctamente en el historial.
  
### Datos de prueba
  
  - Mes: Mes actual
  - Rutinas completadas: 2
  - Rutinas utilizadas: Push Day, Cardio Matutino
  
### Pasos
  
  1. Ir a la pantalla "Reporte".
  2. Revisar las estadísticas mensuales mostradas.
  3. Comparar los valores mostrados con los entrenamientos registrados en el historial durante el mismo mes.
  
### Resultado esperado
  
  - La pantalla "Reporte" muestra correctamente las estadísticas correspondientes a los entrenamientos realizados durante el mes actual.
  - Los valores mostrados en la pantalla "Reporte" coinciden con los entrenamientos registrados en el historial durante el mismo mes.
  - Solo se muestran las estadísticas correspondientes al mes actual.

## TC-REPORT-002 - Cambiar período de estadísticas por mes
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el usuario pueda seleccionar un mes desde el selector de período y que la pantalla "Reporte" actualice las estadísticas correspondientes.

### Precondiciones
  
  - Existen entrenamientos registrados en al menos dos períodos diferentes.
  
### Datos de prueba
  
  - Mes 1: Agosto 2026
  - Rutinas completadas: 2
  - Mes 2: Julio 2026
  - Entrenamientos registrados en julio: 3
  
### Pasos
  
  1. Verificar que la pantalla "Report" muestre las estadísticas de agosto de 2026.
  2. Pulsar el botón de selección de período.
  3. Verificar que se abra el bottom sheet de selección de mes y año.
  4. Seleccionar mes "Julio".
  5. Seleccionar año "2026".
  6. Pulsar "Confirmar".
  7. Revisar las estadísticas mostradas en la pantalla "Reporte".
  
### Resultado esperado
  
  - El bottom sheet se abre correctamente.
  - El usuario puede seleccionar un mes y año.
  - El período seleccionado cambia a "Julio 2026".
  - Las estadísticas se actualizan con los datos correspondientes a julio de 2026.
  - La cantidad de entrenamientos mostrada cambia de 2 a 3.

## TC-REPORT-003 - Actualizar estadísticas mediante swipe down to refresh
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que las estadísticas mensuales se actualicen correctamente al realizar un gesto de swipe down to refresh en la pantalla "Reporte".

### Precondiciones
  
  - El usuario se encuentra en la pantalla "Reporte".
  - Existen estadísticas correspondientes al mes actual.
  - Completar un nuevo entrenamiento durante el mismo mes.
  
### Datos de prueba
  
  - Mes: Agosto 2026
  - Rutinas registradas inicialmente: 2
  - Nuevo entrenamiento completado: Leg Day
  
### Pasos
  
  1. Verificar que la pantalla "Reporte" muestra 2 rutinas para agosto 2026.
  2. Ir a la pantalla "Rutinas".
  3. Completar y guardar el entrenamiento "Leg Day".
  4. Volver a la pantalla "Reporte".
  5. Realizar un gesto de deslizamiento hacia abajo sobre la pantalla.
  6. Esperar a que finalice el proceso de actualización.
  7. Revisar nuevamente las estadísticas del mes.
  
### Resultado esperado
  
  - El gesto de deslizamiento hacia abajo inicia correctamente la actualización.
  - Se muestra el indicador visual de actualización.
  - La cantidad de entrenamientos cambia de 2 a 3.
  - El nuevo entrenamiento se incluye en las estadísticas de agosto de 2026.

___
## TC-HISTORY-001 - Mostrar entrenamiento completado en el historial
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que un entrenamiento completado y guardado se muestre correctamente en la sección de historial.

### Precondiciones
  
  - Existe una rutina creada.
  
### Datos de prueba
  
  - Rutina: Push Day
  - Fecha: Fecha actual
  
### Pasos
  
  1. Iniciar rutina "Push Day".
  2. Completar la rutina "Push Day".
  3. Pulsar "Finalizar".
  4. Ir a la sección de historial.
  5. Localizar el entrenamiento correspondiente a "Push Day"
  6. Verificar que el entrenamiento se muestra en la fecha correcta.
  
### Resultado esperado
  
  - El entrenamiento "Push Day" aparece en el historial.
  - El registro corresponde a la fecha en que se completó el entrenamiento.

## TC-HISTORY-002 - Visualizar detalle de entrenamiento completado
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el usuario pueda abrir un entrenamiento guardado en el historial y visualizar correctamente sus datos.

### Precondiciones
  
  - Existe al menos un entrenamiento completado y guardado en el historial.
  
### Datos de prueba
  
  - Rutina: Push Day
  
### Pasos
  
  1. Localizar el entrenamiento "Push Day" en el historial.
  2. Pulsar sobre el registro del entrenamiento.
  3. Revisar la información mostrada.
  
### Resultado esperado
  
  - Se abre correctamente el detalle del entrenamiento seleccionado.
  - Se muestra el nombre de la rutina correspondiente.
  - Se muestran los ejercicios realizados durante el entrenamiento.
  - La información corresponde al entrenamiento seleccionado y no a otro registro.

___
## TC-SETTINGS-001 - Cambiar sistema métrico a imperial
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el usuario pueda cambiar el sistema de unidades de métrico a imperial y que los valores de peso y altura se actualicen correctamente.

### Precondiciones
  
  - El usuario utiliza el sistema métrico.
  - Existen datos registrados con valores de peso.
  - El usuario se encuentra en la pantalla "Perfil".
  
### Datos de prueba
  
  - Sistema actual: Métrico
  - Sistema nuevo: Imperial
  - Peso del usuario: 50 kg
  - Altura del usuario: 170 cm
  
### Pasos
  
  1. Abrir la configuración de la aplicación.
  2. Seleccionar la opción "Sistema de Medidas".
  3. Seleccionar "Imperial".
  4. Pulsar "Guardar".
  5. Volver a la pantalla "Perfil".
  
### Resultado esperado
  
  - El sistema de unidades cambia correctamente a imperial.
  - Los valores de peso se muestran en libras.
  - Los valores de altura se muestran en pies.
  - El valor previamente registrado como 50 kg se muestra convertido al valor equivalente en lb.
  - El valor previamente registrado como 170 cm se muestra convertido al valor equivalente en ft.
  - La unidad visible cambia de "kg" a "lb".
  - La unidad visible para la altura cambia de "cm" a "ft".

## TC-SETTINGS-002 - Cambiar sistema imperial a métrico
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el usuario pueda cambiar el sistema de unidades de imperial a métrico y que los valores de peso y altura se actualicen correctamente.
  
### Precondiciones
  
  - El usuario utiliza el sistema imperial.
  - Existen datos registrados con valores de peso y altura.
  - El usuario se encuentra en la pantalla "Perfil".
  
### Datos de prueba
  
  - Sistema actual: Imperial
  - Sistema nuevo: Métrico
  - Peso del usuario: 110 lb
  - Altura del usuario: 5'7''
  
### Pasos
  
  1. Abrir la configuración de la aplicación.
  2. Seleccionar la opción "Sistema de Medidas".
  3. Seleccionar "Métrico".
  4. Pulsar "Guardar".
  5. Volver a la pantalla "Perfil".
  
### Resultado esperado
  
  - El sistema de unidades cambia correctamente a métrico.
  - Los valores de peso se muestran en kilogramos.
  - Los valores de altura se muestran en centímetros.
  - El valor previamente registrado como 110 lb se muestra convertido al valor equivalente en kg.
  - El valor previamente registrado como 5'7'' se muestra convertido al valor equivalente en cm.
  - La unidad visible cambia de "lb" a "kg".
  - La unidad visible para la altura cambia de "ft" a "cm".

## TC-SETTINGS-003 - Mantener sistema de unidades después de reiniciar la aplicación
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Persistencia
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el sistema de unidades seleccionado por el usuario se mantenga después de cerrar y volver a abrir la aplicación.
  
### Precondiciones
  
  - El usuario se encuentra en la pantalla "Perfil".
  - La aplicación utiliza actualmente el sistema métrico.
  
### Datos de prueba
  
  - Sistema inicial: Métrico
  - Sistema seleccionado: Imperial
  
### Pasos
  
  1. Abrir la configuración de la aplicación.
  2. Seleccionar la opción "Sistema de Medidas".
  3. Seleccionar "Imperial".
  4. Pulsar "Guardar".
  5. Verificar que el sistema de unidades haya cambiado a imperial.
  6. Cerrar completamente la aplicación.
  7. Volver a abrir la aplicación.
  8. Ir a la pantalla "Perfil".
  9. Abrir nuevamente la configuración de "Sistema de Medidas".
  
### Resultado esperado
  
  - La aplicación inicia correctamente después de ser cerrada.
  - El sistema imperial permanece seleccionado.
  - Los valores de peso continúan mostrándose en libras.
  - Los valores de altura continúan mostrándose en pies.
  - La configuración no vuelve automáticamente al sistema métrico.

## TC-SETTINGS-004 - Cambiar idioma de español a inglés
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el usuario pueda cambiar correctamente el idioma de la aplicación de español a inglés.
  
### Precondiciones
  
  - La aplicación se encuentra configurada en español.
  - El usuario se encuentra en la pestaña "Perfil".
  
### Datos de prueba
  
  - Idioma actual: Español
  - Idioma nuevo: Inglés
  
### Pasos
  
  1. Abrir la pestaña "Perfil".
  2. Abrir "Ajustes".
  3. Seleccionar la opción "Idioma".
  4. Seleccionar "Inglés".
  5. Pulsar "Guardar".
  6. Volver a la pestaña "Perfil".
  7. Navegar por distintas secciones de la aplicación.
  
### Resultado esperado
  
  - El idioma de la aplicación cambia correctamente de español a inglés.
  - Los textos de la pestaña "Perfil" se muestran en inglés.
  - Los textos de las demás secciones de la aplicación se muestran en inglés.
  - Los botones, títulos, etiquetas y mensajes visibles utilizan el idioma seleccionado.
  - No permanecen textos en español en las pantallas revisadas.
  - El idioma "Inglés" queda seleccionado en la configuración.

## TC-SETTINGS-005 - Mantener idioma seleccionado después de reiniciar la aplicación
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Persistencia
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el idioma seleccionado por el usuario se mantenga después de cerrar y volver a abrir la aplicación.
  
### Precondiciones
  
  - La aplicación se encuentra configurada en español.
  - El usuario se encuentra en la pestaña "Perfil".
  
### Datos de prueba
  
  - Idioma inicial: Español
  - Idioma seleccionado: Inglés
  
### Pasos
  
  1. Abrir la pestaña "Perfil".
  2. Abrir "Ajustes".
  3. Seleccionar la opción "Idioma".
  4. Seleccionar "Inglés".
  5. Pulsar "Guardar".
  6. Verificar que la aplicación se muestre en inglés.
  7. Cerrar completamente la aplicación.
  8. Volver a abrir la aplicación.
  9. Navegar por distintas secciones.
  10. Abrir nuevamente "Ajustes" y acceder a la configuración de idioma.
  
### Resultado esperado
  
  - La aplicación inicia correctamente después de ser cerrada.
  - El idioma inglés se mantiene después de reiniciar la aplicación.
  - Los textos continúan mostrándose en inglés.
  - No se restablece automáticamente el idioma español.
  - La opción "Inglés" permanece seleccionada en la configuración de idioma.

  ___
## TC-ENH-001 - Añadir 10 sets a un ejercicio
  
  **Prioridad:** Media
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que sea posible configurar hasta 10 sets en un ejercicio.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla rutinas.
  
### Datos de prueba
  
  - Nombre de rutina: Push Day
  - Ejercicio: Chain Press
  - Cantidad de sets: 10
  
### Pasos
  
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Buscar y seleccionar el ejercicio "Chain Press".
  6. Pulsar "Añadir set" hasta completar 10 sets.
  
### Resultado esperado
  
  - El ejercicio "Chain Press" queda configurado con 10 sets.
  - Los 10 sets se muestran correctamente.
  - El botón "Añadir set" se deshabilita después de alcanzar 10 sets.
  
## TC-ENH-002 - Intentar añadir más de 10 sets
  
  **Prioridad:** Media
  
  **Tipo:** Funcional / Negativo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que no sea posible superar el límite de 10 sets por ejercicio.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla rutinas.
  
### Datos de prueba
  
  - Nombre de rutina: Push Day
  - Ejercicio: Chain Press
  - Cantidad máxima de sets: 10
  
### Pasos
  
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Buscar y seleccionar el ejercicio "Chain Press".
  6. Pulsar "Añadir set" hasta completar 10 sets.
  7. Intentar añadir un nuevo set.
  
### Resultado esperado
  
  - El botón "Añadir set" se deshabilita al alcanzar 10 sets.
  - No se agrega el set número 11.
  - Los 10 sets configurados se mantienen sin modificaciones.
  
## TC-ENH-003 - Configurar los límites de repeticiones
  
  **Prioridad:** Media
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que sea posible configurar entre 5 y 20 repeticiones por set.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla rutinas.
  
### Datos de prueba
  
  - Nombre de rutina: Push Day
  - Ejercicio: Chain Press
  - Set 1: 5 repeticiones
  - Set 2: 20 repeticiones
  
### Pasos
  
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Buscar y seleccionar el ejercicio "Chain Press".
  6. Configurar 5 repeticiones en el primer set.
  7. Configurar 20 repeticiones en el segundo set.
  
### Resultado esperado
  
  - El primer set queda configurado con 5 repeticiones.
  - El segundo set queda configurado con 20 repeticiones.
  
## TC-ENH-004 - Intentar superar los límites de repeticiones
  
  **Prioridad:** Media
  
  **Tipo:** Funcional / Negativo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que no sea posible configurar menos de 5 ni más de 20 repeticiones por set.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla rutinas.
  
### Datos de prueba
  
  - Nombre de rutina: Push Day
  - Ejercicio: Chain Press
  - Límite mínimo: 5 repeticiones
  - Límite máximo: 20 repeticiones
  
### Pasos
  
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Buscar y seleccionar el ejercicio "Chain Press".
  6. Configurar 5 repeticiones en el primer set.
  7. Pulsar nuevamente el botón "-".
  8. Configurar 20 repeticiones en el segundo set.
  9. Pulsar nuevamente el botón "+".
  
### Resultado esperado
  
  - El primer set se mantiene en 5 repeticiones.
  - El segundo set se mantiene en 20 repeticiones.
  - Los botones "-" y "+" se deshabilitan al alcanzar sus respectivos límites.
  
## TC-ENH-005 - Introducir repeticiones mediante el teclado
  
  **Prioridad:** Media
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que sea posible introducir una cantidad válida de repeticiones mediante el teclado.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla rutinas.
  
### Datos de prueba
  
  - Nombre de rutina: Push Day
  - Ejercicio: Chain Press
  - Repeticiones: 12
  
### Pasos
  
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Buscar y seleccionar el ejercicio "Chain Press".
  6. Pulsar el campo de repeticiones del primer set.
  7. Introducir "12" mediante el teclado.
  8. Pulsar el botón "+".
  9. Pulsar el botón "-".
  
### Resultado esperado
  
  - El campo se actualiza a 12 repeticiones.
  - El botón "+" aumenta el valor a 13.
  - El botón "-" reduce nuevamente el valor a 12.
  
## TC-ENH-006 - Introducir valores no permitidos mediante el teclado
  
  **Prioridad:** Media
  
  **Tipo:** Funcional / Negativo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que el campo de repeticiones no acepte valores fuera del rango ni caracteres no numéricos.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla rutinas.
  
### Datos de prueba
  
  - Nombre de rutina: Push Day
  - Ejercicio: Chain Press
  - Valor inferior: 4
  - Valor superior: 21
  - Caracteres no numéricos: abc
  
### Pasos
  
  1. Pulsar el botón "+".
  2. Seleccionar "Rutina de fuerza".
  3. Introducir el nombre "Push Day".
  4. Pulsar el botón de confirmación.
  5. Buscar y seleccionar el ejercicio "Chain Press".
  6. Intentar introducir "4" en el campo de repeticiones del primer set.
  7. Intentar introducir "21" en el campo de repeticiones del segundo set.
  8. Intentar introducir "abc" en el campo de repeticiones del tercer set.
  
### Resultado esperado
  
  - El valor 4 no es aceptado.
  - El valor 21 no es aceptado.
  - Los caracteres no numéricos no son aceptados.
  - Los campos mantienen valores dentro del rango permitido entre 5 y 20 repeticiones.
  
___
## TC-PROFILE-001 - Ingresar peso del usuario
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que sea posible ingresar y guardar el peso del usuario.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla perfil.
  - La aplicación utiliza el sistema métrico.
  
### Datos de prueba
  
  - Peso: 70 kg
  
### Pasos
  
  1. Pulsar el campo de peso.
  2. Introducir el valor "70".
  3. Guardar los cambios.
  
### Resultado esperado
  
  - El peso se guarda correctamente.
  - El valor 70 kg se muestra en el perfil.
  
## TC-PROFILE-002 - Ingresar altura del usuario
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que sea posible ingresar y guardar la altura del usuario.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla perfil.
  - La aplicación utiliza el sistema métrico.
  
### Datos de prueba
  
  - Altura: 170 cm
  
### Pasos
  
  1. Pulsar el campo de altura.
  2. Introducir el valor "170".
  3. Guardar los cambios.
  
### Resultado esperado
  
  - La altura se guarda correctamente.
  - El valor 170 cm se muestra en el perfil.
  
## TC-PROFILE-003 - Actualizar card de IMC
  
  **Prioridad:** Alta
  
  **Tipo:** Funcional / Positivo
  
  **Estado:** Passed
  
  **Descripción:** Verificar que la card de IMC se actualice de acuerdo con el peso y la altura ingresados.
  
### Precondiciones
  
  - Usuario se encuentra en pantalla perfil.
  - La aplicación utiliza el sistema métrico.
  
### Datos de prueba
  
  - Peso: 70 kg
  - Altura: 170 cm
  - IMC esperado: 24.2
  
### Pasos
  
  1. Ingresar un peso de 70 kg.
  2. Ingresar una altura de 170 cm.
  3. Guardar los cambios.
  4. Revisar la sección de IMC.
  
### Resultado esperado
  
  - El IMC se calcula utilizando el peso y la altura ingresados.
  - La card muestra un IMC de 24.2.
  - La categoría y el diseño de la card se actualizan de acuerdo con el resultado obtenido.
