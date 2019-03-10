# Microservicios
Todos sobre Microservicios, desde cero, migrando un aplicación monolitica a Microservicios. Pros &amp; Cons

# Definición
Según el mago Martín Fowler los microservicios es un  es un enfoque para desarrollar una aplicación única como un conjunto de pequeños servicios, cada uno ejecutándose en su propio proceso y comunicándose con mecanismos ligeros, a menudo una API de recursos HTTP. Mas información en: https://martinfowler.com/articles/microservices.html

# Beneficios
Los beneficios que para mi son destacables son:
1. Garantiza el desacomplamiento del codigo, ya que las web api son una frontera física entre el programa cliente y el web api.
2. Acelara y facilita la implementación de cambios en el codigo, y se beneficia de tecnologias como la componentización de Doker.
3. Libertad a los equipos de desarrollo de desarrollar el servicios en la tecnología que se sientan mas agusto o bien que sea mas eficiente para el negocio perse.

# Desventajas

1. Se requiere una mayor planeación al prinicipio, una clara identificación de cada contexto limitado (Bounded Context)
2. Compleja la construcción de la aplicación
3. Requiere de un monitoreo mas riguroso

# Conocimientos y Tecnologías involucradas en los microservicios

Aunque no es oblitatorias todas, digamos son las que se conocen hoy y se han utilizado para la construcción de los microservicios

1. Conceptos
  Bounded Context o Conexto limitado (DDD)
  Eventual consistency o Consistencia Eventual
  Software Evolutivo
  Base de datos No SQL
  Contenedores
 
  
 2.Patrones de Diseño
  CQRS - Command Query Responsibility Segregation https://martinfowler.com/bliki/CQRS.html 
  Event Sourcing
  Colas
  Gateways
   
 3.Tecnologías
  Contenedores - Docker
  Orquestador de contenedores Kubernetes
  Colas RabbitMQ, Apache Kafka
  NoSql - Redis, MongoDb, CosmoDb,Cassandra,HyperGraphDb,Jbase
  Gateways -  Ocelot
  
 4.Herramientas
  Postmant probar los web api
  Swagger documentar web api
  aspnet core 2.2 desarrollo agil de web api
  VS Code editor de codigo liviano, productivo y facil personalizable
  Lenguajes de programación: C#, Java, Pyton
  
  so far so good, mucho que escribir, emprendiendo un viaje increible a los microservicios... continuaremos con mucho mas hasta llegar al codigo.
