Un protocolo define las reglas, tiempos, formato y estructura que deben seguir los dispositivos para intercambiar información correctamente.

Un protocolo especifica:
- **Cómo inicia y termina una comunicación
- **Cómo se organizan los datos
- **Velocidad de transmisión
- **Detección de errores
- **Sincronización entre dispositivos

> Una interfaz define **cómo se conectan**, mientras que un protocolo define **cómo se comunican**.

Ejemplo:
- [USB] puede considerarse una interfaz física
- Pero también utiliza protocolos de comunicación [USB] para transferir datos

---

#### Protocolos de Red:
Conjunto de reglas y estándares que permiten a los dispositivos intercambiar datos, sin importar sus diferencias de Hardware o Sistema Operativo.

Se utilizan en:
- Internet
- Redes locales
- [IoT]
- Comunicación entre servidores y clientes

_Tipos de datos:_
- Texto
- Audio
- Video
- Archivos
- Señales de control
- Telemetría

_Ejemplos de protocolos de red:_
- [TCP]
- [IP]
- [HTTP]
- [HTTPS]
- [FTP]
- [MQTT]
- [WebSocket]

---

#### Protocolos de Comunicación Serial:

Permiten la transmisión de datos bit a bit entre dispositivos electrónicos.

Se usan ampliamente en sistemas embebidos y microcontroladores.

_Características:_
- Bajo consumo de pines
- Comunicación síncrona o asíncrona
- Corta o media distancia

_Ejemplos:_
- [UART]
- [SPI]
- [I2C]
- [CAN]
- [RS-232]

---

#### Protocolos Inalámbricos:
Permiten la comunicación sin cables mediante señales de radio.

Usados en:
- [IoT]
- Automatización
- Redes móviles
- Sensores inalámbricos

_Ejemplos:_
- [Wi-Fi]
- [Bluetooth]
- [Zigbee]
- [LoRa]
- [NFC]

---

### Diferencia rápida:

| Concepto  | Función                                             |
| --------- | --------------------------------------------------- |
| Interfaz  | Medio o sistema que conecta dispositivos o software |
| Protocolo | Reglas que siguen para intercambiar datos           |

Ejemplo práctico:
- [USB] = interfaz física
- [HTTP] = protocolo de comunicación
- [API] = interfaz de software
- [SPI] = interfaz + protocolo de comunicación serial

---

### Nota importante:
Algunas tecnologías funcionan tanto como interfaz como protocolo, dependiendo del contexto.

Por ejemplo:
- [SPI] define conexiones físicas y reglas de comunicación
- [I2C] también especifica cableado y formato de transmisión
- [USB] incluye capas físicas y protocolos internos

Por eso, en [sistemas embebidos] muchas veces ambos conceptos se superponen.