# 🏐 Tablero de Vóley Web

Un tablero digital interactivo, responsive y libre de dependencias para partidos de vóley. Diseñado para funcionar de manera fluida y limpia en cualquier dispositivo (Desktop, Tablets y Celulares en modo Portrait o Landscape).

El use case principal es conectar una PC con la página abierta a un televisor (tablero), y usar un mouse inalámbrico para sumar puntos (los controles se detallan más abajo, pero pueden cambiarse por cualquiera). 



## ✨ Características Principales

* **🎮 Control Multidispositivo:**
  * **PC:** Clics del mouse, teclas configurables y modo restar rápido (por defecto con la tecla `Espacio`).
  * **Móviles / Tablets:** Tap simple en pantalla para sumar puntos y *Long Press* (presión mantenida de 0.5s) para restar.
* **⚙️ Totalmente Personalizable:**
  * Cambio de nombres de equipos mediante **doble clic directo** sobre el texto (sin bordes de selección molestos) o desde el panel de opciones.
  * Selectores de color dinámicos para identificar a cada equipo.
  * Sistema de rebindeo completo para asignar cualquier tecla o botón del mouse a cada acción.
* **🏆 Reglas Oficiales Adaptables:**
  * Soporte para partidos al mejor de 1, 3 o 5 sets (**BO1, BO3, BO5**).
  * Puntuación objetivo automática: **25 puntos** en sets regulares y **15 puntos** en el set decisivo (*Tiebreak*), requiriendo diferencia mínima de 2 puntos para ganar.
  * Pantalla emergente de felicitación al equipo ganador del partido.
* **📱 Layout Anti-Clipping & Escalado Inteligente:**
  * Controles de zoom manual de números (`+` / `-`) desde el 60% hasta el 140% en Desktop/Vertical.
  * **Detección de Mobile Landscape:** Habilita automáticamente un escalado ampliado de hasta el **200%** para maximizar visibilidad en pantalla horizontal.
  * Protección CSS Flex/Grid: Garantiza que el tamaño del número nunca solape ni recorte el nombre de los equipos.
* **🌙 Modo Oscuro y Pantalla Completa:**
  * Alternancia instantánea entre tema claro y oscuro.
  * Botón directo para ocultar la interfaz del navegador (*Fullscreen API*).
* **📊 Historial de Sets:** Registro inferior en vivo con los parciales de cada set finalizado.


## 🚀 Cómo Ejecutarlo

No requiere instalación, entorno Node.js, dependencias ni proceso de compilación.

1. Clona el repositorio:

   ```bash
   git clone https://github.com/ignamosconi/tablero-voley.git
   ```

2. Abre el archivo `index.html` en tu navegador web preferido (Chrome, Firefox, Edge, Safari).
3. ¡Listo para llevar el tanteador!

## ⌨️ Tabla de Controles

| Acción | PC (Teclado / Mouse) | Pantalla Táctil (Móvil/Tablet) |
| ------------------------- | ----------------------- | ------------------------------ |
| **Sumar Punto Local** | Clic Izquierdo | Tap en el lado Local |
| **Sumar Punto Visitante** | Clic Derecho | Tap en el lado Visitante |
| **Activar Modo Restar** | Tecla `Espacio` | — |
| **Restar Punto** | Modo Restar + Clic | Mantener presionado (0.5s) |
| **Editar Nombre** | Doble clic en el nombre | Doble clic en el nombre |

> *Todos los controles se pueden reconfigurar a gusto desde el panel de **⚙ Opciones**.*


## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.
