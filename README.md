# 🦾 Brazo Robótico en 3D

## 📘 Descripción del Proyecto
El **Brazo Robótico en 3D** es un prototipo educativo diseñado para imitar los movimientos básicos de un brazo humano. Está fabricado mediante **impresión 3D** y controlado por un **microcontrolador Arduino**, que gestiona los servomotores encargados del movimiento de cada articulación.

Este proyecto integra **mecánica, electrónica y programación**, permitiendo a los estudiantes y entusiastas aprender sobre automatización, diseño 3D y control de actuadores.

---

## 🎯 Propósito
El propósito principal es **automatizar movimientos repetitivos y de precisión** en un entorno de bajo costo. Además, busca ser una herramienta didáctica para comprender los principios de la robótica aplicada.

---

## ⚙️ Características
- Estructura modular impresa en 3D  
- Control mediante **Arduino UNO o Mega**  
- Movimiento controlado por **servomotores**  
- Posibilidad de control manual o programado  
- Fácil de replicar y personalizar  

---

## 🧩 Problema que Resuelve
Los brazos robóticos comerciales suelen ser costosos y difíciles de implementar. Este proyecto ofrece una **alternativa accesible y práctica**, ideal para **estudiantes, laboratorios y makers** que buscan experimentar con robótica sin requerir grandes recursos.

---

## 🧠 Contexto y Alcance
El proyecto puede emplearse para:
- Prácticas de ingeniería y mecatrónica  
- Demostraciones de control de movimiento  
- Introducción a la automatización y programación de actuadores

---
## 🧰 Requisitos e Instalación

### 🔧 Requisitos de Hardware
- Placa **Arduino UNO** (o compatible)
- 4 **Servomotores SG90 / MG996R**
- 4 **Potenciómetros de 10kΩ**
- **Protoboard** (placa de pruebas)
- Cables **Dupont macho–macho**
- Fuente de alimentación de **5V (mínimo 2A)**
- **Piezas impresas en 3D** para el brazo robótico

### 💻 Requisitos de Software
- **Arduino IDE** (versión 1.8 o superior)
- Librería integrada **Servo.h** (ya incluida en el IDE)
- Cable USB para cargar el programa

### ⚙️ Instalación
1. Conecta la placa Arduino UNO a tu computadora mediante el cable USB.  
2. Abre **Arduino IDE**.  
3. Copia el código del proyecto 
4. Verifica el código con el botón ✔️ “Verificar”.  
5. Sube el programa al Arduino con el botón “Subir” 🔼.  
6. Conecta los servomotores y potenciómetros según el diagrama de conexión.  
7. Abre el **monitor serial** (opcional) para observar las lecturas de los potenciómetros.

---

## 🚀 Cómo Usarlo

### 🔌 Funcionamiento Básico
- Gira cada potenciómetro para mover una parte del brazo robótico:
  - **Potenciómetro 1 (A0):** Abre y cierra la pinza.  
  - **Potenciómetro 2 (A1):** Controla el brazo derecho.  
  - **Potenciómetro 3 (A2):** Controla el brazo izquierdo.  
  - **Potenciómetro 4 (A3):** Gira la base del brazo.  

Cada movimiento manual de un potenciómetro genera una lectura analógica entre **0 y 1023**, que el programa convierte en un ángulo de **0° a 180°** para el servomotor correspondiente.

### ⚙️ Ejemplo de uso paso a paso
1. Alimenta el Arduino (por USB o fuente externa de 5V).  
2. Observa cómo el brazo se mantiene en su posición inicial.  
3. Gira lentamente el **potenciómetro 1**: la pinza abrirá o cerrará.  
4. Gira los otros potenciómetros y verás cómo el brazo se mueve en diferentes direcciones.  
5. Experimenta con distintas posiciones para coordinar movimientos simultáneos.  
