# Aplicación: Anvil of Ambition

El código fuente del videojuego está en un repositorio aparte:

**https://github.com/FelipeMillanOrellana/Anvil_of_Ambition** (rama `main`)

Ahí están el historial de commits de cada integrante, los Pull Requests y el README con los controles del juego.

## Cómo ejecutar el juego

1. Instalar **Godot 4.7** desde https://godotengine.org/download
2. Clonar el repositorio:
   ```bash
   git clone https://github.com/FelipeMillanOrellana/Anvil_of_Ambition.git
   ```
3. Abrir Godot, elegir **Importar** y seleccionar `project.godot`.
4. Ejecutar con **F5**. El juego parte en la pantalla de título (`scenes/ui/TitleScreen.tscn`).

Si en el editor está activado *Embed Game on Next Play*, la pantalla completa no se aplica; en una ventana normal sí funciona.

## Escenas de prueba

Se ejecutan con **F6** para probar un sistema de forma aislada (los casos están en `Fase 2/Evidencias de documentación/Pruebas.xlsx`):

| Escena | Sistema |
|---|---|
| `scenes/ForgeTest.tscn` | Ciclo completo de forja |
| `scenes/CombatTestScene.tscn` | Combate jugable (Atacar y Defender) |
| `scenes/CombatTest.tscn` | Panel de depuración del combate |
| `scenes/world/MovementTest.tscn` | Movimiento del personaje |

## Tecnología

- Motor: Godot 4.7, lenguaje GDScript, renderizador `gl_compatibility`.
- Plataforma objetivo: Windows (exportación ejecutable pendiente, ver requisito RNF-14).
- El juego funciona sin conexión a internet.
