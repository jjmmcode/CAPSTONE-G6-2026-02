# CAPSTONE-G6-2026-02 · Anvil of Ambition

Repositorio de evidencias del **Proyecto APT (Capstone PTY4614)** del Grupo 6, Ingeniería Informática, DuocUC.

**Anvil of Ambition** es un videojuego 2D de herrería y rol desarrollado en **Godot 4.7**. El jugador encarna a Aiden, aprendiz de herrero, que forja armas mediante minijuegos de habilidad (temperatura e impacto), recolecta minerales en la mina, comercia en la tienda y enfrenta monstruos en combates por turnos con ventanas de timing.

## Integrantes

| Integrante | GitHub | Áreas principales |
|---|---|---|
| Felipe Millán | [@FelipeMillanOrellana](https://github.com/FelipeMillanOrellana) | Mundo y escenas, forja, minería, narrativa, guardado de partida, arte |
| Joel Medina | [@jjmmcode](https://github.com/jjmmcode) | Menús e interfaz, sistema de combate base (turnos, daño, atacar), estadísticas y progresión, persistencia de opciones |
| Yerko Loncón | [@kick-assgrr](https://github.com/kick-assgrr) | IA de los monstruos, acción Defender, escenas de prueba de combate |

## Enlaces del proyecto

- **Tablero Trello (gestión de tareas):** https://trello.com/b/dxwSYImH/capstone-g6-2026-02
- **Repositorio del videojuego (código fuente):** https://github.com/FelipeMillanOrellana/Anvil_of_Ambition

## Estructura del repositorio

La estructura sigue el repositorio base de la asignatura ([ErnestoLeonidas/base_capstone](https://github.com/ErnestoLeonidas/base_capstone)).

```text
Fase 1/   Definición del proyecto
├── Evidencias Grupales        Definición del Proyecto APT (1.5), presentación de la idea, Product Vision
└── Evidencias Individuales    Autoevaluación de competencias (1.1), diario de reflexión (1.2), autoevaluación (1.3)

Fase 2/   Desarrollo del proyecto
├── Evidencias Grupales        Informe de avance (2.4), informe final (2.6)
├── Evidencias Individuales    Diario de reflexión (2.1), autoevaluación de avance (2.2), formativa (2.3)
├── Evidencias de documentación  Product Backlog, Sprint Backlog, pruebas, requisitos no funcionales,
│                                retrospectivas, diagramas UML, modelo de datos
└── Evidencias de sistema      Aplicación, base de datos, Docker

Fase 3/   Presentación final
├── Evidencias Grupales        Presentación final
├── Evidencias Individuales    Diario de reflexión (3.1), autoevaluación (3.2)
└── Evidencias Proyecto        Presentación del proyecto
```

Los documentos individuales siguen el formato `Apellido_Nombre_<n°>_APT122_<documento>.docx`.

## Metodología

El proyecto sigue la metodología **en cascada** definida en la Definición del Proyecto APT (1.5): planificación, diseño, implementación, pruebas, corrección y cierre, y presentación.

Dentro de la etapa de implementación, el equipo complementa la cascada con prácticas ágiles:

- **Iteraciones** de una a dos semanas, registradas en el Sprint Backlog.
- **Product Backlog y Sprint Backlog** en `Fase 2/Evidencias de documentación/`, construidos a partir del tablero Trello y del historial de commits del repositorio del videojuego.
- **Retrospectivas** al cierre de cada iteración, con acciones y responsables.
- **Control de versiones** con Git y GitHub: cada funcionalidad se desarrolla en una rama propia y se integra a `main` mediante Pull Request.

## Tecnologías

- Godot Engine 4.7 (GDScript)
- Git, GitHub y GitHub Desktop
- Trello
