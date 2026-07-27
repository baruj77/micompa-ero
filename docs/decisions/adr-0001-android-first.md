# ADR-0001: Android primero

- **Estado:** Aceptada para validación inicial
- **Fecha:** 2026-07-27

## Contexto

El producto debe probarse con bajo costo de entrada y en dispositivos que las personas ya utilizan. El teléfono aporta movilidad, datos móviles, GPS, cámara, micrófono y llamadas.

## Decisión

Desarrollar el MVP para teléfonos Android. La interfaz deberá adaptarse posteriormente a tablets Android. El familiar utilizará inicialmente un portal web responsive. iOS se evaluará después de validar utilidad, adopción y sostenibilidad económica.

## Beneficios

- Menor costo para participantes.
- Pilotos más rápidos.
- Mayor disponibilidad de dispositivos económicos.
- Reutilización futura en tablets.

## Riesgos

- Fragmentación de versiones y fabricantes.
- Pantallas pequeñas.
- Restricciones de batería y segundo plano.
- Permisos que pueden confundir.

## Alternativas consideradas

Tablet dedicada, aplicación multiplataforma simultánea y aplicación web progresiva.

## Consecuencias

Se debe inventariar el parque real de teléfonos antes de fijar versión mínima. La marca seguirá siendo “Mi Compañero/a”; los identificadores técnicos usarán caracteres ASCII cuando sea necesario.