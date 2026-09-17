# PanelHAD

Prototipo de webapp para apoyar la organización diaria de profesionales de Hospitalización a Domicilio (HAD/HADom).

## Estado
Primera versión funcional orientada a descubrir y validar necesidades reales con profesionales. Todos los pacientes, horarios, tratamientos, ubicaciones y datos incluidos son ficticios y sirven únicamente para demostrar la interfaz.

## Módulos actuales
- **Turno**: resumen, Radar HAD, progreso, agenda y tareas pendientes.
- **Pacientes**: tarjetas, prioridades, ventanas horarias, filtros, búsqueda y modo visita.
- **Ruta**: secuencia de visitas, distancias ficticias y mapa demostrativo.
- **Material**: checklist logístico derivado de la actividad prevista.
- **Protocolos**: buscador y estructura preparada para documentación institucional validada.
- Diseño responsive para escritorio y móvil, con modo oscuro.

## Principios del prototipo
1. No es una historia clínica electrónica.
2. No realiza diagnósticos ni propone decisiones terapéuticas.
3. No se deben introducir datos clínicos identificables reales en esta versión.
4. La biblioteca clínica no contiene instrucciones asistenciales: deberá alimentarse posteriormente con protocolos oficiales y validados.
5. Las funciones actuales son hipótesis de producto que deberán contrastarse con profesionales de HADom.

## Próximas fases
- Entrevistas con enfermería HAD/HADom para identificar fricciones reales del turno.
- Priorización de problemas por frecuencia, impacto y tiempo consumido.
- Rediseño del flujo de turno con los hallazgos.
- Modelo de datos y permisos.
- Evaluación de privacidad, seguridad, RGPD y requisitos aplicables antes de manejar información real.
- Integraciones con sistemas corporativos solo cuando exista un caso de uso validado y autorización de la organización.

## Ejecución
Es una aplicación estática sin dependencias. Abrir `index.html` o publicar la rama mediante un servicio de hosting estático.

**Aviso:** PanelHAD está actualmente en fase de prototipo y demostración. No debe utilizarse para asistencia clínica real.