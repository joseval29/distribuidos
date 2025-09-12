# Taller Stocket y Threads

Este repositorio contiene dos proyectos desarrollados en entity["software","Java",1], orientados a la comprensión de conceptos fundamentales de **comunicación en red mediante sockets** y **programación concurrente con hilos**.  

El trabajo hace parte de un taller académico de la entity["organization","Pontificia Universidad Javeriana"] para la asignatura de Introducción a Sistemas Distribuidos.

---

## 📡 Proyecto 1 — Comunicación con Sockets (TCP y UDP)

Este proyecto implementa comunicación **cliente-servidor** mediante sockets utilizando los protocolos  
entity["scientific_concept","Transmission Control Protocol"] (TCP) y entity["scientific_concept","User Datagram Protocol"] (UDP).  

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
```

---

## ⚡ Proyecto 2 — Concurrencia con Threads

Este proyecto simula la atención de clientes para comparar la ejecución **secuencial** y **concurrente** mediante el uso de hilos (`Thread` y `Runnable`).

### 📝 Archivos

- `Cliente.java` → Datos de cada cliente
- `Cajera.java` → Atiende clientes secuencialmente
- `CajeraThread.java` → Atiende clientes en paralelo (extiende `Thread`)
- `Main.java` → Ejecución secuencial
- `MainThread.java` → Ejecución concurrente con `Thread`
- `MainRunnable.java` → Ejecución concurrente con `Runnable`

### ⚙️ Ejecución

```bash
# Compilar todos los archivos .java
javac -d . *.java

# Ejecutar la versión secuencial
java threadsJarroba.Main

# Ejecutar la versión concurrente usando Thread
java threadsJarroba.MainThread

# Ejecutar la versión concurrente usando Runnable
java threadsJarroba.MainRunnable
```

---

## 📌 Contenido del Informe

El informe incluye:

- Resumen y abstract en español e inglés.
- Introducción sobre comunicación en red y concurrencia.
- Objetivos generales y específicos.
- Descripción técnica de los dos proyectos.
- Tablas comparativas de sus archivos y estructuras.
- Evidencia de ejecución (capturas de pantalla).
- Conclusiones generales del taller.

📄 [Ver informe completo en PDF](./DistribuidosTaller.pdf)


---

