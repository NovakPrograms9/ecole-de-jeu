# École de Jeu · Prototipo del sistema

Prototipo navegable del sistema de gestión de la École de Jeu (Maternelle, Lycée Claude Gay, Osorno). Sirve como referencia visual y funcional para desarrollar el sistema real según la especificación del proyecto.

**Es un prototipo:** usa datos de ejemplo, guarda los cambios solo en el navegador (localStorage) y simula el envío de correos e invitaciones. No tiene servidor, base de datos ni inicio de sesión real.

## Cómo verlo

Abre `index.html` en cualquier navegador. No requiere instalación.

Para publicarlo con GitHub Pages: en el repositorio, ve a **Settings → Pages**, elige la rama `main` y la carpeta raíz, y guarda.

## Qué incluye

El selector **"Ver como"** cambia entre los cuatro roles:

| Rol | Secciones |
| --- | --- |
| Coordinador | Inicio con alertas, Horario (por día, grupo y taller), Talleres (gestión completa de cada taller), Grupos (nómina por curso y carga desde Excel, CSV o lista pegada), Asistencia, Niños (fichas con autorizados), Salida, Avisos (con copia para WhatsApp, Schooltrack y Colegium), Equipo, Planificaciones y Académie (reservada) |
| Monitor | Mi día, Asistencia (solo nombres), Planificación semanal y Avisos internos |
| Dirección | Resumen y asistencia por grupo, sin datos personales |
| Familia | Nombre del hijo, qué traer, semana del grupo y avisos |

## Reglas del programa modeladas

- 6 grupos: PS 1, PS 2, MS 1, MS 2, GS 1 y GS 2.
- 6 talleres en simultáneo: Psicomotricidad y Yoga, Pequeños Músicos, Ritmo y Movimiento, Arte y Teatro, Pequeños Exploradores, Juega y Construye.
- Tres talleres alternan contenido: lunes y martes una parte, jueves y viernes la otra.
- 3 módulos diarios (14:00, 14:45 y 15:30); lunes y jueves comparten rotación, igual que martes y viernes.

## Para el desarrollo real

Ver la especificación del sistema (roles y permisos, modelo de datos, privacidad, integraciones y criterios de aceptación). Este prototipo no debe usarse con datos reales de niños.
