# Exploratory Testing

## ET-001 - Creación y configuración de rutinas

**Objetivo:** Explorar comportamientos límite durante la creación de rutinas de fuerza.

### Información de la sesión

- **Tester:** Matius Alcaino
- **Fecha:** 26/08/2026
- **Versión:** v1.0.0 build 24
- **Dispositivo:** OnePlus 6 - Android 11
- **Duración:** 10 minutos
- **Técnica:** Valores límite y entradas inválidas

### Áreas exploradas

- Nombres de rutinas
- Ejercicios personalizados
- Cantidad de sets
- Cantidad de repeticiones

### Hallazgos

- BUG-001 - No existe límite de caracteres para nombres de rutinas.
- BUG-002 - No existe límite de caracteres para nombres de ejercicios personalizados.
- ENH-001 - Definir límite máximo de sets por ejercicio.
- ENH-002 - Definir límite de repeticiones por set.
- ENH-003 - Introducir por teclado la cantidad de repeticiones.

### Resultado

Se identificaron dos defectos visuales y tres oportunidad de mejora.

### Seguimiento

- BUG-001: Corregido en v1.0.0 build 25.
- BUG-002: Corregido en v1.0.0 build 25.
- ENH-001: Implementada.
- ENH-002: Implementada.
- ENH-003: Implementada.

Los defectos fueron corregidos y las mejoras fueron implementadas correctamente.
