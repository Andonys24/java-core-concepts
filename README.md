# Java Core Concepts

Un repositorio educativo que contiene ejercicios, proyectos y conceptos fundamentales de programación en Java, organizados por unidades temáticas y tareas.

## 📋 Descripción

Este repositorio sirve como material de referencia y aprendizaje para conceptos clave de Java, incluyendo:

- **Conceptos Fundamentales** (Unidad I): POO, Herencia, Excepciones, Genéricos, Arreglos
- **Manipulación de Datos** (Unidad II): Manejo de Archivos, Serialización, Hilos, Fechas/Horas
- **Programación de Red** (Unidad III): Sockets, Servidores Web y HTTP
- **Proyectos Prácticos** (Tareas): Aplicaciones completas con servidor-cliente

## 🚀 Proyectos Destacados

### Repositorios Separados

Estos proyectos tienen sus propios repositorios:

| Proyecto | Descripción | Repositorio |
|----------|-------------|-------------|
| Chat Server | Servidor de chat concurrente con múltiples clientes | [chat-server](https://github.com/Andonys24/chat-server.git) |
| File Server | Servidor de archivos con descarga/subida | [file-server](https://github.com/Andonys24/file-server.git) |
| Web Server | Servidor HTTP con manejo GET/POST y logging | [web-server](https://github.com/Andonys24/web-server.git) |
| Directorio Telefónico | Gestión de contactos con serialización | [directorio-telefonico](https://github.com/Andonys24/directorio-telefonico.git) |
| Object Manager | Administrador de objetos con persistencia | [object-manager](https://github.com/Andonys24/object-manager-java.git) |

### Proyectos Incluidos en Este Repositorio

#### 🎓 Proyectos de Examen (Unidades II y III)

Estos proyectos fueron desarrollados como evaluaciones del curso:

- **Unidad II**: Directorio Telefónico, Object Manager
- **Unidad III**: Chat Server, File Server, Web Server

#### 🎯 Mini-Proyectos Educativos

#### 🎲 DiceGame (Unidad II)
Sistema de juego de dados con interfaz de consola.

```bash
cd mini-proyectos/DiceGame
mvn clean compile exec:java -Dexec.mainClass="com.github.andonys24.Main"
```

#### 📋 MenuMultiNivel (Unidad I)
Sistema de menús jerárquicos con navegación intuitiva.

```bash
cd mini-proyectos/MenuMultiNivel
javac -d bin src/menumultinivel/*.java
java -cp bin menumultinivel.Main
```

#### 🔄 Serializacion (Unidad II)
Utilidades generales para serialización de objetos Java.

```bash
cd mini-proyectos/serializacion
mvn clean compile
```

#### 🌐 SocketsHTML (Unidad III)
Servidor HTTP básico que sirve páginas estáticas.

```bash
cd "Unidad III/SocketsHTML"
mvn clean compile exec:java
```

#### 📱 SocketTest (Unidad III)
Pruebas básicas de conexión con sockets TCP.

```bash
cd "Unidad III/SocketTest"
javac src/sockettest/SocketTest.java
java -cp src sockettest.SocketTest
```

## 📝 Contenido por Unidad

### Unidad I: Programación Orientada a Objetos

- **POO**: Clases, objetos, encapsulación, métodos
- **Herencia**: Jerarquía de clases, polimorfismo, sobrescritura de métodos
- **Excepciones**: Try-catch, throws, excepciones personalizadas
- **Genéricos**: Tipos parametrizados, wildcards, bounded types
- **Arreglos**: Arrays unidimensionales y multidimensionales

### Unidad II: Manipulación de Datos

- **Manejo de Archivos**: Lectura/escritura con FileReader, FileWriter, BufferedReader
- **Serialización**: ObjectInputStream, ObjectOutputStream, interfaz Serializable
- **Hilos**: Thread, Runnable, sincronización, pools de hilos
- **Fechas y Horas**: LocalDate, LocalTime, LocalDateTime, DateFormatter
- **Estructuras de Datos**: ArrayList, HashMap, Sets

### Unidad III: Programación de Red

- **Sockets TCP**: ServerSocket, Socket, comunicación cliente-servidor
- **Protocolo HTTP**: GET, POST, parseo de solicitudes
- **Servidores Multihilo**: Manejo de múltiples conexiones simultáneas
- **Recursos Web**: Servicio de archivos estáticos, tipos MIME

## 🛠️ Requisitos

- **Java**: JDK 11+ (JDK 17+ recomendado para hilos virtuales)
- **Maven**: 3.6+
- **Git**: Para clonar el repositorio

## 📦 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/Andonys24/java-core-concepts.git
cd java-core-concepts

# Compilar un proyecto específico
cd "Unidad I/POO"
javac -d bin src/poo/*.java

# O usando Maven (en proyectos con pom.xml)
cd Tareas/DiceGame
mvn clean compile
```

## 🎯 Estructura de Aprendizaje Recomendada

1. **Nivel Básico**: Comienza con `Unidad I` para entender conceptos fundamentales
2. **Nivel Intermedio**: Continúa con `Unidad II` para manejo de datos y concurrencia
3. **Nivel Avanzado**: Estudia `Unidad III` para programación de red
4. **Práctica**: Revisa los mini-proyectos en `mini-proyectos/` para ver aplicaciones educativas

## 💡 Conceptos Clave Cubiertos

- ✅ Encapsulación y abstracción
- ✅ Herencia y polimorfismo
- ✅ Manejo de excepciones robusto
- ✅ Concurrencia y sincronización
- ✅ I/O de archivos y serialización
- ✅ Sockets y comunicación de red
- ✅ Protocolo HTTP básico
- ✅ Patrones de diseño simples

## 📚 Recursos Adicionales

- Cada carpeta puede contener un `README.md` específico con detalles del proyecto
- Archivos de instrucciones en `mini-proyectos/` explican los requisitos detallados
- Documentación incluida en `Unidad III/WebServer/DOCUMENTACION.txt`

## 🏫 Información Académica

Este repositorio contiene material del curso **Programación II** de la Universidad Nacional Autónoma de Honduras (UNAH), diseñado para proporcionar una base sólida en programación orientada a objetos, manipulación de datos y programación de red en Java.

## 🤝 Contribuciones

Este repositorio es principalmente educativo. Las mejoras y correcciones son bienvenidas.

## 📄 Licencia

Este proyecto es de uso educativo.

## 👨‍💻 Autor

**Andoni Hernández** - [@Andonys24](https://github.com/Andonys24)

---

### 🔗 Enlaces Relacionados

- [Chat Server](https://github.com/Andonys24/chat-server.git)
- [File Server](https://github.com/Andonys24/file-server.git)
- [Web Server](https://github.com/Andonys24/web-server.git)
- [Directorio Telefónico](https://github.com/Andonys24/directorio-telefonico.git)
- [Object Manager](https://github.com/Andonys24/object-manager-java.git)

---

**Última actualización**: Diciembre 2025  
