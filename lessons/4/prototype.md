---
sidebar_position: 3
---

# Prototipar

:::info[Importante]
**Duracion:** 60 minutos
:::

## Objetivo de la Fase:
Refinar y ampliar las capacidades de los robots construidos en sesiones anteriores, añadiendo un motor mediano y un sensor táctil para abordar problemáticas ambientales de manera más efectiva.

:::tip[Narrativa]
"Hoy transformaremos nuestro robot en un agente más activo en la conservación ambiental, añadiendo una garra mecánica que podría ayudar a recoger desechos, retirar objetos peligrosos o reubicar pequeñas especies en áreas de conservación."
:::

---

## Instrucciones:
1. **Innovación y Creatividad:** 
   - Discutan cómo el motor mediano y el sensor táctil pueden mejorar la funcionalidad del robot.
   - Reflexionen sobre cómo estas mejoras pueden ayudar al robot a reaccionar a cambios en su entorno.
   
2. **Diseño y Construcción:**
   - Modificar el diseño del robot en la **SPIKE™ App** (Proyecto "Base de Conducción 2") para incorporar los nuevos componentes.
   - Adaptar las funcionalidades para interactuar con el entorno de manera más efectiva.

---

## Programación y Pruebas:

### **Desafío 1: Limpieza de Espacios Verdes**
:::tip[Narrativa]
"Programemos el robot para que recoja desechos dispersos en un parque después de un evento de viento fuerte, utilizando su garra para recoger los objetos cada vez que los detecte con el sensor táctil."
:::

**Pseudocódigo sin Bucle:**
```plaintext
Mover hacia adelante 40 cm
Si el sensor táctil detecta contacto o sensor ultrasónico detecta objeto:
    Activar garra
    Recoger objeto
    Detenerse por 2 segundos
    Mover hacia la zona de depósito
    Soltar objeto en la zona de depósito
    Regresar a la posición inicial
```

**Explicación de Bucles:**
Repetir el proceso utilizando bucles para hacer el código más eficiente.

**Pseudocódigo con Bucle:**
```plaintext
Repetir 5 veces:
    Mover hacia adelante 40 cm
    Si el sensor táctil detecta contacto o sensor ultrasónico:
        Activar garra
        Recoger objeto
        Mover hacia la zona de depósito
        Soltar objeto
```

### **Desafío 2: Rescate de Especies en Miniatura**
:::tip[Narrativa]
"En este escenario, el robot deberá navegar por un terreno lleno de obstáculos y utilizar su garra para rescatar pequeñas especies atrapadas."
:::

**Pseudocódigo sin Bucle:**
```plaintext
Mover hacia adelante
Repetir hasta que el sensor ultrasónico detecte un obstáculo a menos de 10 cm:
    Detener
    Verificar si hay un objeto usando el sensor táctil
    Activar garra para levantar el objeto
    Retroceder 10 cm
    Girar y continuar avanzando
```

**Pseudocódigo con Bucle:**
```plaintext
Mover hacia adelante continuamente
    Si el sensor ultrasónico detecta un obstáculo:
        Detener
        Activar garra si el sensor táctil detecta contacto
        Retroceder y continuar
```

**Reflexión y Mejora:**
Después de las pruebas, los grupos deben discutir y proponer mejoras para optimizar la funcionalidad del robot.
