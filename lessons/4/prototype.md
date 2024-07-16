---
sidebar_position: 3
---

# Prototipar

:::info[Importante]
**Duracion:** 60 minutos
:::

## Objetivo de la Fase:
Refinar y ampliar las capacidades del robot diseñado en sesiones anteriores para abordar problemáticas ambientales específicas, incorporando un motor mediano y un sensor táctil. Este enfoque permitirá a los estudiantes aplicar y profundizar su comprensión de cómo la tecnología puede interactuar y mitigar efectivamente los desafíos ambientales.

:::tip[Narrativa]
"En nuestra continua misión de conservación ambiental, hoy vamos a explorar nuevas capacidades que pueden transformar nuestro robot en un agente más activo en la gestión y mitigación de problemáticas ambientales. Expandiremos las funcionalidades de nuestro robot para que pueda interactuar de manera más efectiva con su entorno."

"Pensemos en las diversas maneras en que esta nueva herramienta, una garra mecánica, podría utilizarse en el campo. ¿Podría ayudar a recoger muestras de áreas contaminadas, retirar desechos de lugares de difícil acceso o incluso asistir en la reubicación de especies pequeñas para estudios de conservación? Hoy los invito a imaginar y diseñar cómo este robot podría emplear su garra para realizar tareas que aporten significativamente a nuestra labor ambiental. Este enfoque nos permite no solo aprender sobre robótica sino también aplicar estos conocimientos de manera creativa para resolver retos reales."
:::

### Instrucciones:

- **Innovación y Creatividad:**
  - Discutir como grupo cómo el motor mediano y el sensor táctil pueden ser utilizados para mejorar las funcionalidades del robot. Considerar escenarios como la recolección de materiales peligrosos o el reubicar elementos naturales con cuidado para no dañar el ecosistema.
  - Reflexionar sobre cómo estas mejoras permiten al robot realizar tareas de manera autónoma y reaccionar a los cambios en su entorno.

- **Diseño y Construcción:**
  - Utilizar las instrucciones de la 'Base de Conducción 2' en el software SPIKE™ App como punto de partida para construir la estructura básica del robot.
  - Modificar y adaptar este diseño para incorporar el motor mediano y el sensor táctil. Imaginar y planificar cómo estas adiciones pueden ser utilizadas para interactuar con el entorno de maneras innovadoras.


## Desafío 1: Limpieza de Espacios Verdes
:::tip[Narrativa]
"Imaginen un parque local después de un evento de viento fuerte, lleno de desechos dispersos que necesitan ser limpiados. Este primer desafío les pide que programen el robot para que pueda navegar por el parque y utilizar su garra para recoger pequeños desechos, activando la garra a través del sensor táctil cada vez que se encuentre con un objeto."
:::

### Pseudocódigo sin Bucle:
```plaintext
Mover hacia adelante 40 cm
Si el sensor táctil detecta contacto:
    Activar garra
    Recoger objeto
    Detenerse por 2 segundos
    Mover hacia la zona de depósito
    Soltar objeto en la zona de depósito
    Regresar a la posición inicial
```

### Instrucciones Adicionales:
- Colocar pequeños objetos (representando desechos) en el área de desafío. Los estudiantes deben programar el robot para evitar obstáculos y recoger los objetos.
- Descargar el archivo .llps3 para este desafío y cargarlo en el software SPIKE™ App.

## Explicación de Bucles:
"Ahora que hemos completado el primer desafío, habrán notado que tuvimos que repetir muchas instrucciones en nuestro código. Esto no solo es tedioso, sino que también hace que nuestro programa sea menos eficiente. Aquí es donde entra en juego el concepto de bucle. Un bucle nos permite repetir una serie de instrucciones varias veces, lo que hace que nuestro código sea más eficiente y fácil de leer. Por ejemplo, en lugar de escribir el mismo bloque de código varias veces, podemos usar un bucle para que el robot repita una acción hasta que alcance su objetivo. Esto es especialmente útil cuando necesitamos que el robot realice movimientos repetitivos, como patrullar una zona o evitar obstáculos."

### Pseudocódigo con Bucle:
```plaintext
Repetir 5 veces:
    Mover hacia adelante 40 cm
    Si el sensor táctil detecta contacto:
        Activar garra
        Recoger objeto
        Detenerse por 2 segundos
        Mover hacia la zona de depósito
        Soltar objeto en la zona de depósito
        Regresar a la posición inicial
```

## Desafío 2: Rescate de Especies en Miniatura
:::tip[Narrativa]
"En este escenario, se simula un bosque donde varias especies pequeñas están atrapadas entre escombros después de una inundación. El objetivo es utilizar el robot para navegar a través de un terreno lleno de obstáculos, utilizando el sensor ultrasónico para evitar colisiones, y el sensor táctil para activar la garra y rescatar a las especies en miniatura."
:::

### Pseudocódigo sin Bucle:
```plaintext
Mover hacia adelante
Repetir hasta que el sensor ultrasónico detecte un obstáculo a menos de 10 cm:
    Avanzar lentamente
Detener
Verificar si hay un objeto usando el sensor táctil
Si el sensor táctil detecta contacto:
    Activar la garra para levantar el objeto cuidadosamente
    Detenerse
    Retroceder 10 cm
    Si es posible girar a la derecha, entonces girar 90 grados a la derecha
    Si no, girar 90 grados a la izquierda
Continuar avanzando hasta encontrar un nuevo espacio libre
```

### Instrucciones Adicionales:
- Colocar figuras de animales en el área de desafío, simulando un terreno con obstáculos naturales.
- Descargar el archivo .llps3 para este desafío y cargarlo en el software SPIKE™ App.

## Explicación de Ciclos:
"Al completar este desafío más complejo, es crucial entender cómo los bucles pueden facilitar la navegación y la operación del robot en entornos desafiantes, evitando la repetición manual de instrucciones y optimizando la eficiencia del código."

### Pseudocódigo con Bucle:
```plaintext
Mover hacia adelante continuamente
    Si el sensor ultrasónico detecta un obstáculo a menos de 10 cm:
        Detener
        Verificar si hay un objeto usando el sensor táctil
        Si el sensor táctil detecta contacto:
            Activar la garra para levantar el objeto cuidadosamente
            Retroceder 10 cm
            Si es posible girar a la derecha, entonces girar 90 grados a la derecha
            Si no, girar 90 grados a la izquierda
        Continuar avanzando
```

## Reflexión y Mejora:
- Después de las pruebas, discutan como grupo qué ajustes son necesarios para optimizar la funcionalidad del robot.
- Considerar cualquier limitación observada durante las pruebas y buscar soluciones creativas para superar estos desafíos.
