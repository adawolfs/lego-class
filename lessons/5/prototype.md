---
sidebar_position: 4
---

# Prototipar

:::info[Importante]
**Duracion:** 50 minutos
:::

## Objetivo de la Fase:
Construir y programar una "mano robótica" que ayude en la recolección de desechos, utilizando el software SPIKE™ App y los kits de Lego Education Spike Prime.

:::tip[Narrativa]
"Con las ideas desarrolladas, ahora construiremos prototipos reales utilizando el modelo 'mano robótica'. Este modelo nos ayudará a comprender cómo la mecánica y la programación se combinan para resolver problemas ambientales."
:::

## Construcción del Robot:
- Asignar a cada grupo un kit de Spike Prime y configurar el software SPIKE™ App.
- Buscar el Proyecto “Mano Robótica” en la App y construir el robot.

---

## Programación y Pruebas de Prototipos

### **Desafío 1: Apertura y Cierre del Brazo Robótico**
:::tip[Narrativa]
"Imagina que estamos en un parque donde hay varios residuos dispersos. Programemos una mano robótica que pueda abrirse y cerrarse para recoger estos residuos."
:::

**Pseudocódigo con Bucle:**
```plaintext
Repetir hasta que todos los residuos sean recogidos:
    Si [sensor táctil detecta contacto]:
        Activar motor mediano
        Abrir garra
        Esperar 2 segundos
        Cerrar garra
        Esperar 2 segundos
```

### **Desafío 2: Brazo Robótico con Sensor Ultrasónico**
:::tip[Narrativa]
"Utilizaremos el sensor ultrasónico para detectar objetos a cierta distancia y programar el brazo robótico para que los recoja."
:::

**Pseudocódigo con Bucle:**
```plaintext
Repetir hasta que todos los residuos sean recogidos:
    Si [sensor ultrasónico detecta objeto a menos de 10 cm]:
        Activar motor mediano
        Abrir garra
        Cerrar garra
```

### **Desafío 3: Brazo Robótico con Sensor de Color**
:::tip[Narrativa]
"Vamos a utilizar el sensor de color para detectar y clasificar diferentes tipos de residuos, moviendo los objetos a diferentes contenedores según su color."
:::

**Pseudocódigo con Bucle:**
```plaintext
Repetir hasta que todos los residuos sean clasificados:
    Si [sensor de color detecta color rojo]:
        Mover brazo a la zona de clasificación roja
    Si [sensor de color detecta color azul]:
        Mover brazo a la zona de clasificación azul
```
