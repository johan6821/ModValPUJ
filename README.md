# Taller de Modelado y Validación de la Arquitectura

# Justificaciones de arquitectura 
Patrones 
Estilo de realización de servicios
Trade-off Estilos de arquitectura

# Generación de los artefactos de servicios identificados para el inventario. 
Se debe tener en cuenta que cada artefacto (esquemas, contratos y políticas) deben ser
independientes. Cada artefacto se debe diseñar bajo la premisa de “ Contrato Primero ”.
Se puede utilizar RAML/OpenAPI/JSON Schema, Thrift IDL, GRPC, … (No se admiten
servicios SOAP)

# Creación del inventario de servicio y registro de los mismos (Descubrir servicios)

# Creación de un servicio basado en el patrón Intermediate Routing que realice
enrutamiento basado en datos, para poder enrutar las peticiones al tipo de servicio
adecuados dependiendo del convenio

# Implementar los servicios que soportan el proceso

# Realizar la composición de los servicios usando cualquiera de las aproximaciones de
composición (basado en Orquestación o Coreografía, se puede utilizar FUSE, Camel
Kafka, ActiveMQ, RabbitMQ pero está prohibido utilizar BPEL y BPMS)

# Generar servicios que sean autocontenidos e independientemente desplegables en
Docker

# Implementar un servicio que modele el patrón de API Proxy

# El API Proxy debe ser capaz de trabajar con diferentes representaciones de los datos,
tanto para los request como para los response. De esta manera se pueden tener
requests/responses XML/JSON
