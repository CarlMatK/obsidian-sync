La [Arquitectura] (ISA) define:

- Qué instrucciones entiende el procesador
- Cómo se organizan los registros
- Cómo maneja memoria y datos
- Cómo se ejecutan operaciones

En otras palabras:

> La [Arquitectura] define “cómo piensa y trabaja” el procesador internamente.

---
# Arquitecturas de Procesadores
La arquitectura de un procesador define el diseño lógico y el conjunto de instrucciones que utiliza para ejecutar programas.

Determina:
- Rendimiento
- Consumo energético
- Complejidad del hardware
- Compatibilidad de software
- Velocidad de ejecución

---
## ISA — Instruction Set Architecture

Es la interfaz entre:
- Hardware del procesador
- Software/programas

La ISA especifica:
- Instrucciones disponibles
- Registros
- Modos de direccionamiento
- Tipos de datos
- Formato de instrucciones

Ejemplos de ISA:
- [x86]
- [ARM]
- [RISC-V]
- [MIPS]

---
# Arquitectura [CISC]

### Complex Instruction Set Computer
Diseñada para usar instrucciones complejas capaces de realizar múltiples operaciones en una sola instrucción.

_Características:_
- Gran cantidad de instrucciones
- Instrucciones complejas
- Longitud variable de instrucciones
- Menor cantidad de líneas de código
- Hardware más complejo

_Ventajas:_
- Programas más compactos
- Mayor compatibilidad histórica
- Facilita programación en bajo nivel

_Desventajas:_
- Mayor consumo energético
- Hardware más complejo
- Menor eficiencia por instrucción

_Ejemplos:_
- [x86]
- [x86-64]

_Usado en:_
- PCs
- Laptops
- Servidores tradicionales

---
# Arquitectura [RISC]

### Reduced Instruction Set Computer
Diseñada para ejecutar instrucciones simples y rápidas.

La filosofía RISC busca:
- Instrucciones pequeñas
- Ejecución eficiente
- Mayor velocidad por ciclo

_Características:_
- Instrucciones simples
- Tamaño fijo de instrucciones
- Menor complejidad de hardware
- Más registros internos
- Optimización para pipelines

_Ventajas:_
- Bajo consumo energético
- Mayor eficiencia
- Hardware más simple
- Mejor rendimiento por watt

_Desventajas:_
- Programas más largos
- Más instrucciones para tareas complejas

_Ejemplos:_
- [ARM]
- [RISC-V]
- [MIPS]

_Usado en:_
- Smartphones
- Microcontroladores
- IoT
- Sistemas embebidos

---

# Arquitectura [RISC-V]]
[RISC-V] es una ISA abierta basada en la filosofía RISC.

Fue desarrollada para:
- Ser libre y abierta
- Permitir personalización
- Reducir dependencia de licencias propietarias

_Características:_
- Código abierto
- Modular
- Escalable
- Flexible
- Extensible

_Ventajas:_
- Sin costos de licencia
- Personalizable
- Ideal para investigación e [IoT]
- Crecimiento rápido en la industria

_Aplicaciones:_
- Microcontroladores
- Sistemas embebidos
- Investigación académica
- Chips personalizados
- IA y aceleradores

---
# Arquitectura [ARM]

[ARM] es una arquitectura [RISC] optimizada para eficiencia energética.

_Características:_
- Bajo consumo
- Alto rendimiento por watt
- Muy usada en dispositivos móviles

_Usado en:_
- Smartphones
- Tablets
- Raspberry Pi
- Microcontroladores
- Apple Silicon

---
# Comparación rápida:

|Arquitectura|Filosofía|Complejidad|Consumo|Uso típico|
|---|---|---|---|---|
|CISC|Instrucciones complejas|Alta|Mayor|PCs y servidores|
|RISC|Instrucciones simples|Baja|Menor|Embebidos y móviles|
|RISC-V|RISC abierta|Baja|Bajo|IoT y chips personalizados|

---
# Relación con Microcontroladores

Muchos microcontroladores modernos utilizan arquitecturas RISC debido a:
- Bajo consumo
- Simplicidad
- Menor costo
- Mayor eficiencia

Ejemplos:
- [ESP32] → arquitectura Xtensa/RISC
- [STM32] → ARM Cortex-M
- [RP2040] → ARM Cortex-M0+
- Nuevos MCUs → RISC-V

---

# Importante:
No debe confundirse:

- **Arquitectura (ISA)** → conjunto de instrucciones
- **Microarquitectura** → implementación física interna del procesador

Ejemplo:  
Dos procesadores pueden usar:

- La misma ISA [ARM]  
    pero tener:
- diferente rendimiento
- diferente caché
- distinta frecuencia
- distinto número de núcleos

Porque internamente usan microarquitecturas diferentes.