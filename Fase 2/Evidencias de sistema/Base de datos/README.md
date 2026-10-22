# Persistencia de datos

El juego no usa un motor de base de datos. Guarda la información en archivos locales dentro de la carpeta de usuario de Godot (`user://`):

| Archivo | Formato | Lo escribe | Contenido |
|---|---|---|---|
| `user://saves/slot_1.json` … `slot_3.json` | JSON | `SaveManager` | Partida: estadísticas, inventario, monedas, progresión del herrero, estado del mundo, escena y posición |
| `user://settings.cfg` | ConfigFile (INI) | `pause_menu.gd` | Opciones globales: volumen, pantalla completa, Modo Asistencia y consejos |

Los datos de diseño del juego (objetos, materiales, equipo, planos, monstruos y diálogos) son Resources de Godot (`.tres`) dentro del repositorio del juego, en `resources/` y `scripts/resources/monsters/`.

En Windows, `user://` corresponde a `%APPDATA%\Godot\app_userdata\AnvilOfAmbition\`.

## Archivos de ejemplo

- [`ejemplo_slot_1.json`](ejemplo_slot_1.json): estructura de una partida guardada.
- [`ejemplo_settings.cfg`](ejemplo_settings.cfg): archivo de opciones.

**Son ejemplos ilustrativos:** las claves corresponden al código de `SaveManager.gd` y `pause_menu.gd`, pero los valores son de muestra.

El modelo completo (diagrama entidad-relación, diccionario de datos y restricciones) está en `Fase 2/Evidencias de documentación/Modelo de datos.pdf`.
