# 🧩 Taller: Sockets y Threads en Java

Este repositorio contiene dos proyectos desarrollados en :contentReference[oaicite:0]{index=0} que abordan conceptos fundamentales de **comunicación en red mediante sockets** y **programación concurrente mediante hilos**.  

El objetivo es comprender el funcionamiento de los protocolos  
:contentReference[oaicite:1]{index=1} (TCP) y :contentReference[oaicite:2]{index=2} (UDP), así como comparar la ejecución **secuencial** y **paralela** con `Thread` y `Runnable`.

---

## 📡 Proyecto 1 — Comunicación con Sockets (TCP y UDP)

Este proyecto implementa comunicación **cliente-servidor** utilizando sockets, permitiendo enviar y recibir mensajes a través de la red mediante TCP (orientado a conexión) y UDP (no orientado a conexión).

### 📝 Archivos

- `sockettcpser.java` → Servidor TCP (usa `ServerSocket` y `Socket`)
- `sockettcpcli.java` → Cliente TCP
- `socketudpser.java` → Servidor UDP (usa `DatagramSocket` y `DatagramPacket`)
- `socketudpcli.java` → Cliente UDP

### ⚙️ Ejecución

```bash
# Compilar todos los archivos .java
javac -d . *.java

# Ejecutar el servidor TCP
java sockets.sockettcpser

# Ejecutar el cliente TCP
java sockets.sockettcpcli

# Ejecutar el servidor UDP
java sockets.socketudpser

# Ejecutar el cliente UDP
java sockets.socketudpcli
