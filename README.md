# Vibe Hunt

Un juego de reflejos donde debes evitar que un ninja capture tu cursor mientras recoges orbes para sumar puntos.

## Cómo jugar

1. Abre el archivo `index.html` en tu navegador
2. Mueve el cursor rojo para evitar que el ninja (cuadrado de colores) te atrape
3. **Recoge los orbes dorados** que aparecen en pantalla para aumentar tu puntuación
4. El objetivo es sobrevivir la mayor cantidad de tiempo posible y recoger la mayor cantidad de orbes
5. ¡Cuidado! El ninja se volverá más agresivo y rápido a medida que recojas más orbes

## Características

### Orbes Coleccionables

- Aparecen en ubicaciones estratégicas por toda la pantalla
- Al recoger un orbe, se suma a tu puntuación
- Después de 10 orbes, ¡aparecerá un segundo ninja!

### Ninjas

Los ninjas tienen diferentes estrategias para intentar atrapar tu cursor:

- **Verde (Pacífico)**: Estrategia inicial, movimientos más predecibles
- **Amarillo (Alerta)**: Velocidad y agresividad media
- **Rojo (Agresivo)**: Movimientos rápidos e impredecibles

Las estrategias incluyen:
- **Directa**: Persecución directa hacia tu cursor
- **Predicción**: Analiza tu velocidad para predecir tu movimiento
- **Zigzag**: Se mueve en patrones impredecibles
- **Emboscada**: Busca posiciones estratégicas para emboscarte
- **Intercepción**: Calcula puntos de intercepción óptimos
- **Curva**: Realiza movimientos curvilíneos para sorprenderte
- **Negación**: Intenta bloquear tu acceso a los orbes

### Comportamiento Adaptativo

Los ninjas:
- Comienzan con una velocidad reducida para permitirte adaptarte al juego
- Aumentan gradualmente su velocidad a medida que recoges orbes
- Son más agresivos cuando estás lejos para evitar que mantengas distancia
- Cambian de estrategia basándose en tus patrones de movimiento
- Colaboran entre sí cuando hay dos ninjas activos

### Interfaz Responsiva

- Diseño adaptable para dispositivos móviles y de escritorio
- Mensaje personalizado de reinicio según el dispositivo
- Centrado vertical y horizontal para mejor visualización
- Contador de inicio para prepararte antes de comenzar

## Controles

- **Dispositivos de escritorio**: Mueve el mouse para controlar el cursor rojo
- **Dispositivos móviles**: Desliza el dedo para mover el cursor rojo
- Si un ninja te atrapa, haz clic o levanta el dedo (en móviles) para reiniciar

## Consejos para sobrevivir

- Aprovecha el inicio lento para familiarizarte con los controles
- Realiza movimientos impredecibles y cambia de dirección constantemente
- Observa el color del ninja para anticipar su nivel de agresividad
- No te quedes quieto, los ninjas están diseñados para predecir puntos de parada
- Mantén una distancia prudente; estar demasiado lejos aumenta su agresividad

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)

## Optimizaciones recientes

- **Inicio gradual**: Los ninjas comienzan más lentos para facilitar la adaptación
- **Ajustes visuales**: Se oculta el ninja y cursor durante la cuenta regresiva inicial
- **Mejoras móviles**: Experiencia optimizada para dispositivos táctiles
- **Centrado**: El juego está perfectamente centrado tanto vertical como horizontalmente

## Créditos

Juego creado mediante **vibe coding** usando Claude-3.7-Sonnet y Gemini-2-5 Pro Max.
Creador: [@santiago-paz](https://github.com/santiago-paz)
Proyecto profesional: [Reema](https://www.reema.ar)
