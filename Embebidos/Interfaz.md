Una interfaz es el medio o mecanismo que permite la interacción y comunicación entre sistemas, dispositivos o software.

Define:
- Cómo se conectan los componentes
- Qué señales o comandos utilizan
- Cómo el usuario o sistema interactúa con el dispositivo

Las interfaces pueden ser:
- Físicas (Hardware)
- Lógicas (Software)
- Gráficas (Interacción con usuarios)

> La interfaz establece el punto de conexión; el protocolo establece las reglas de comunicación.

---

#### Interfaces en Hardware H <-> H
Permiten conectar el [Microcontrolador] con otros chips, sensores o periféricos electrónicos.

_Funciones principales:_
- Transmisión de datos
- Control de dispositivos
- Expansión de hardware
- Comunicación entre circuitos integrados

_Características:_
- Uso de pines físicos
- Señales eléctricas
- Velocidades de transmisión específicas
- Comunicación serial o paralela

_Ejemplos:_
- [UART]
- [SPI]
- [I2C]
- [USB]
- [GPIO]

---

#### Interfaces Gráficas de Usuario [GUI]: S <-> H
Permiten que un usuario interactúe visualmente con un sistema electrónico mediante elementos gráficos.

Se desarrollan aplicaciones cliente para:
- Monitorear variables
- Configurar dispositivos
- Visualizar sensores
- Controlar actuadores
- Enviar comandos

_Elementos comunes:_
- Botones
- Gráficas
- Indicadores
- Consolas
- Paneles de control

_Ejemplos de tecnologías GUI:_
- [Qt]
- [Tkinter]
- [Electron]
- Aplicaciones móviles Android/iOS
- Interfaces Web

---

#### Interfaces de Programación de Aplicaciones [API]: S <-> S
Es un conjunto de funciones, métodos y reglas que permiten que dos aplicaciones o sistemas de software se comuniquen entre sí.

Las [API]s permiten:
- Compartir información
- Acceder a servicios
- Automatizar procesos
- Integrar plataformas

_Tipos comunes de API:_
- REST API
- SOAP API
- Web API
- Librerías SDK

_Ejemplos de uso:_
- Una app móvil consultando datos de un servidor
- Un sistema [IoT] enviando información a la nube
- Comunicación entre backend y frontend

---

#### Interfaces Hombre-Máquina [HMI]
Permiten la interacción directa entre personas y máquinas industriales o sistemas automatizados.

Usadas en:
- Automatización industrial
- PLCs
- Sistemas SCADA
- Paneles táctiles

_Funciones:_
- Supervisión
- Control manual
- Visualización de estados
- Alarmas y diagnóstico
--- 
### Ejemplo práctico completo:
Un sistema [IoT] puede utilizar:

- [SPI] para conectar sensores al microcontrolador
- [Wi-Fi] para enviar datos por red
- [MQTT] como protocolo de comunicación
- Una [API REST] para compartir datos
- Una [GUI] para visualizar información en tiempo real