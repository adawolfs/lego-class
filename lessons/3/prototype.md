---
sidebar_position: 3
---

# Prototipar

:::info[Importante]
**Duracion:** 60 minutos
:::

### Objetivo de la Fase:
Construir y programar el robot utilizando el sensor ultrasónico para resolver la problemática definida.

### Descripción de la Fase:
:::tip[Narrativa]
"Continuamos profundizando en nuestro compromiso con la conservación ambiental, enfrentando desafíos significativos que requieren soluciones innovadoras. En esta sesión, nos centraremos en cómo podemos contribuir a resolver problemas críticos en nuestro entorno. Abordaremos tareas como el rescate de animales en peligro, la monitorización de la calidad del aire y la limpieza de residuos en áreas de difícil acceso. Para esto, desarrollaremos un robot equipado con un sensor ultrasónico. Esta tecnología, común en aplicaciones como autos autónomos y sistemas de seguridad para detectar obstáculos y movimientos, será adaptada para enfrentar desafíos ambientales específicos. Aprenderemos a programar y construir este robot, optimizando su capacidad para ejecutar estas tareas vitales de manera efectiva."
:::

### Construcción del Robot
**Tiempo:** 25 minutos

:::tip[Narrativa]
"Iniciemos la construcción de 'El Explorador Inteligente', diseñado para enfrentar desafíos ambientales específicos en nuestra comunidad. Equipado con un sensor ultrasónico, este robot se especializa en la detección de obstáculos y la navegación segura, crucial para tareas como patrullar áreas protegidas y evitar colisiones. Sigan detenidamente las instrucciones en el software SPIKE™ App para ensamblar adecuadamente el robot y garantizar que todas las conexiones estén correctamente establecidas. Este robot será una herramienta esencial en nuestros esfuerzos por monitorear y conservar el entorno."
:::

#### Instrucciones:
- **Reparto de Equipos:** Asignar a cada grupo un kit de Lego Education Spike Prime y una computadora o tablet con el software SPIKE™ App instalado.
- **Configuración Inicial:** Encender el hub programable y conectarlo a la computadora o tablet mediante Bluetooth o USB.
- **Construcción del Robot:**
  - Utilizar la base del carrito de reparto.
  - Conectar los motores medianos en la parte delantera para el movimiento hacia adelante y hacia atrás.
  - Conectar el motor grande en la parte trasera para la dirección.
  - Colocar el sensor ultrasónico en la parte delantera del robot para detectar objetos.
- **Personalización:** Motivar a los estudiantes a añadir piezas adicionales que consideren necesarias para resolver la problemática elegida.

### Programación del Robot
**Tiempo:** 25 minutos

:::tip[Narrativa]
"Ahora que hemos construido nuestro explorador ambiental, vamos a programarlo para que pueda detectar objetos y navegar de manera segura. Utilizaremos bloques de programación en el software SPIKE™ App para que el robot realice movimientos y evite obstáculos mientras patrulla su área asignada. A continuación, vamos a descargar los archivos de proyecto para cada desafío y trabajar en su implementación."
:::

### Desafíos:

**Desafío 1: Rescate de Animales en Peligro**
:::tip[Narrativa]
"Después de una tormenta severa, muchas áreas naturales quedan inaccesibles, y la fauna local puede quedar atrapada o en peligro debido a los escombros y las nuevas barreras físicas que se forman. Este escenario plantea un reto significativo para las operaciones de rescate, especialmente en terrenos difíciles. En este contexto, exploremos cómo un robot equipado con un sensor ultrasónico podría ser clave para navegar por estos entornos alterados, detectando obstáculos y facilitando el rescate de animales afectados. Reflexionemos sobre cómo podemos aplicar la tecnología no solo para preservar nuestra biodiversidad sino también para actuar efectivamente en crisis ambientales."
:::

#### Pseudocódigo sin Bucle:
```plaintext
Mover hacia adelante 30 cm
Si el sensor ultrasónico detecta un objeto a menos de 20 cm:
    Detener
    Girar 90 grados a la derecha
    Mover hacia adelante 20 cm
    Girar 90 grados a la izquierda
    Mover hacia adelante 30 cm
```

#### Instrucciones Adicionales:
- Colocar pequeños objetos (representando animales) en el área de desafío. Los estudiantes deben programar el robot para evitar obstáculos y llegar a los objetos para "rescatar" a los animales.
- Descargar el archivo .llps3 para este desafío y cargarlo en el software SPIKE™ App.

### Explicación de Bucles
:::tip[Narrativa]
"Ahora que hemos completado el primer desafío, habrán notado que tuvimos que repetir muchas instrucciones en nuestro código. Esto no solo es tedioso, sino que también hace que nuestro programa sea menos eficiente. Aquí es donde entra en juego el concepto de bucle. Un bucle nos permite repetir una serie de instrucciones varias veces, lo que hace que nuestro código sea más eficiente y fácil de leer. Por ejemplo, en lugar de escribir el mismo bloque de código varias veces, podemos usar un bucle para que el robot repita una acción hasta que alcance su objetivo. Esto es especialmente útil cuando necesitamos que el robot realice movimientos repetitivos, como patrullar una zona o evitar obstáculos."
:::

#### Ejemplo de Pseudocódigo sin Bucle:
```plaintext
Mover hacia adelante 20 cm
Girar 90 grados a la derecha
Mover hacia adelante 20 cm
Girar 90 grados a la derecha
Mover hacia adelante 20 cm
Girar 90 grados a la derecha
Mover hacia adelante 20 cm
Girar 90 grados a la derecha
```

#### Ejemplo de Pseudocódigo con Bucle:
```plaintext
Repetir 4 veces:
    Mover hacia adelante 20 cm
    Girar 90 grados a la derecha
```

#### Instrucciones:
- El uso de bucles ayuda a optimizar el código, haciendo que sea más corto y más fácil de entender.
- Implementar los bucles en la programación para mejorar la eficiencia de los robots.

**Desafío 2: Conservación de Áreas Protegidas**
:::tip[Narrativa]
"Nuestras áreas protegidas son hogares de especies valiosas pero vulnerables, muchas de las cuales están en peligro de extinción. Sin embargo, estas áreas enfrentan problemas constantes como la intrusión humana ilegal y los efectos devastadores de fenómenos naturales. Reflexionemos sobre las maneras en que la tecnología podría ayudar a monitorear y proteger estos espacios sin perturbar la vida silvestre."
:::

#### Pseudocódigo sin Bucle:
```plaintext
Mover hacia adelante 30 cm
Si el sensor ultrasónico detecta un objeto a menos de 20 cm:
    Detener
    Emitir un sonido de alerta
    Girar 90 grados a la derecha
    Mover hacia adelante 30 cm
    Girar 90 grados a la derecha
    Mover hacia adelante 30 cm
    Girar 90 grados a la derecha
    Mover hacia adelante 30 cm
    Girar 90 grados a la derecha
```

#### Pseudocódigo con Bucle:
```plaintext
Repetir 4 veces:
    Mover hacia adelante 30 cm
    Si el sensor ultrasónico detecta un objeto a menos de 20 cm:
        Detener
        Emitir un sonido de alerta
        Girar 90 grados a la derecha
```

#### Instrucciones Adicionales:
- Utiliza cinta de aislar para marcar una ruta en zigzag en el suelo de la sala de clase o el espacio disponible.
- Coloca obstáculos (como cajas, conos o libros) a lo largo del camino para simular un terreno natural de un área protegida que podría incluir árboles caídos, rocas o pequeñas elevaciones.
- Descargar el archivo .llps3 para este desafío y cargarlo en el software SPIKE™ App.

**Desafío 3: Limpieza de Residuos en Áreas Difíciles**
:::tip[Narrativa]
"En este desafío, enfrentaremos un problema común en la gestión ambiental: la limpieza de áreas contaminadas que son difíciles de acceder para los humanos. Nuestro avanzado robot explorador, equipado con un sensor ultrasónico, será programado para navegar de manera autónoma por un circuito en espiral, simulando la tarea de limpiar una zona irregularmente contaminada. Este escenario no solo desafiará las habilidades de programación de nuestros estudiantes avanzados, sino que también les mostrará cómo la robótica puede ser una herramienta valiosa en la mitigación de impactos ambientales, facilitando intervenciones en lugares que requieren una atención meticulosa y sostenida."
:::

#### Pseudocódigo sin Bucle:
```plaintext
1. Mover hacia adelante 10 cm
2. Si el sensor ultrasónico detecta un objeto a menos de 20 cm:
   a. Detener
   b. Emitir un sonido de alerta
   c. Retroceder 5 cm
   d. Girar 45 grados a la derecha
3. Repetir los pasos 1 y 2 tres veces más, aumentando la distancia de movimiento 5 cm cada vez
```

#### Pseudocódigo con Bucle:
```plaintext
1. Iniciar la distancia en 10 cm
2. Repetir 4 veces (incrementando la distancia de movimiento en 5 cm después de cada ciclo completo):
   a. Mover hacia adelante la distancia actual
   b. Si el sensor ultrasónico detecta un objeto a menos de 20 cm:
      i. Detener
      ii. Emitir un sonido de alerta
      iii. Retroceder 5 cm
      iv. Girar 45 grados a la derecha
   c. Incrementar la distancia de movimiento en 5 cm
```

#### Instrucciones Adicionales:
- **Configuración del Área:** Utiliza cinta de aislar para marcar una espiral en el suelo del aula o zona de pruebas. Coloca obstáculos pequeños y dispersos a lo largo de la espiral para simular desechos o

 impedimentos que el robot debe evitar.
- Descargar el archivo .llps3 para este desafío y cargarlo en el software SPIKE™ App.

### Pruebas y Ajustes
**Tiempo:** 10 minutos

:::tip[Narrativa]
"Ahora que hemos programado nuestro explorador ambiental con el sensor ultrasónico, es crucial verificar su eficacia en acción. Observemos cómo navega el entorno designado, identificando y esquivando obstáculos con precisión. Mientras realiza su patrullaje, estemos atentos a cualquier ajuste que podamos hacer para mejorar su rendimiento. Este paso es fundamental para asegurarnos de que nuestro robot no solo cumple con su función, sino que también opera de manera óptima en situaciones reales. Analicemos juntos su desempeño y discutamos las posibles mejoras que podríamos implementar."
:::

#### Instrucciones:
- Probar el robot en el área de desafío correspondiente marcada con cinta de aislar en el suelo.
- Observar cómo se mueve el robot y si cumple con las tareas asignadas.
- Realizar ajustes en la construcción o programación del robot según sea necesario.
- Descargar el archivo .llps3 para este desafío y cargarlo en el software SPIKE™ App.
