# Microservicios Spring Boot con Apache Kafka

## Descripción
Este proyecto demuestra la comunicación entre dos microservicios Spring Boot utilizando Apache Kafka como intermediario. Un microservicio actúa como productor, enviando mensajes a un tópico de Kafka, mientras que el otro microservicio actúa como consumidor, leyendo y procesando estos mensajes.

## Tecnologías Utilizadas
* **Spring Boot:** Framework Java para crear aplicaciones independientes.
* **Apache Kafka:** Plataforma de mensajería distribuida.
* **Maven:** Gestor de dependencias.

## Configuración
1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/diegolopez-dev/apache-kafka.git
2. Configurar Kafka:
  Instala y configura un clúster de Kafka.
3. Configurar las propiedades de los microservicios:
  Edita los archivos application.properties de producer y consumer para configurar la conexión a Kafka, el tópico, etc.

## Flujo de Trabajo
* Producer: Envía mensajes en formato JSON al tópico de Kafka.
* Consumer: Lee los mensajes del tópico y realiza las acciones correspondientes.
* Ejemplo de mensaje
{
  "mensaje": "Hola desde el productor",
  "timestamp": 1672530800000
}
