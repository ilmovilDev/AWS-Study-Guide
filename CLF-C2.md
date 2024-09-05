# AWS Certified Cloud Practitioner Exam CLF-C02
Este documento contiene toda la información relevante sobre el nuevo examen AWS Certified Cloud Practitioner CLF-C02.

# Dominios del Examen CLF-C02 para AWS Certified Cloud Practitioner
Los nuevos dominios del examen AWS Certified Cloud Practitioner (CLF-C02) son los siguientes:

- Dominio 1: Conceptos de la Nube 24%
- Dominio 2: Seguridad y Cumplimiento 30%
- Dominio 3: Tecnología y Servicios en la Nube 34%
- Dominio 4: Facturación, Precios y Soporte 12%

[![Dominios del Examen AWS Certified Cloud Practitioner CLF-C02](https://td-mainsite-cdn.tutorialsdojo.com/wp-content/uploads/2023/06/aws-certified-cloud-practitioner-clf-c02-exam-guide-exam-topics-pdf-book-1200x899.png)](https://tutorialsdojo.com/new-aws-certified-cloud-practitioner-clf-c02-exam-version-in-2023/)

Toma en cuenta que el examen Cloud Practitioner ha aumentado significativamente su cobertura en el dominio de Seguridad y Cumplimiento. Esta parece ser la tendencia en los exámenes de certificación de AWS, donde el componente relacionado con la seguridad ha aumentado. En el examen CLF-C02, los temas relacionados con la seguridad ahora representan el 30%, en comparación con el 25% anterior.

También hay dos dominios del examen CLF-C01 que han sido renombrados. El dominio "Tecnología" ahora se llama "Tecnología y Servicios en la Nube" y "Facturación y Precios" ha sido modificado a "Facturación, Precios y Soporte".

# Temas del Examen CLF-C02 para AWS Certified Cloud Practitioner
La lista de temas del examen AWS Certified Cloud Practitioner se puede encontrar en la guía oficial del examen CLF-C02. Estos temas están divididos en dominios y por declaración de tareas:

## DOMINIO #1 CLF-C02: CONCEPTOS DE LA NUBE

## Declaración de Tarea 1.1: Definir los beneficios de la nube de AWS

### Beneficios de la Nube de AWS
- **Escalabilidad**: AWS permite escalar recursos automáticamente según la demanda. Esto significa que las empresas pueden ajustar su capacidad en función de las necesidades sin tener que invertir en infraestructura física adicional.
- **Costos bajo demanda**: Pago solo por los recursos que realmente se utilizan. AWS ofrece un modelo de precios basado en el uso, lo que ayuda a reducir los costos operativos y de capital.
- **Globalización**: AWS tiene centros de datos en varias regiones y zonas de disponibilidad alrededor del mundo, permitiendo la distribución global de servicios y aplicaciones.
- **Innovación rápida**: La nube facilita la experimentación y el desarrollo rápido de nuevas soluciones, ya que los recursos están disponibles de inmediato y sin necesidad de inversiones iniciales significativas.
- **Seguridad**: AWS ofrece una infraestructura con múltiples capas de seguridad, incluyendo controles de acceso, cifrado y monitoreo continuo para proteger datos y aplicaciones.

## Declaración de Tarea 1.2: Identificar los principios de diseño de la nube AWS

### Principios de Diseño de la Nube de AWS
- **Marco de Buenas Prácticas de AWS (AWS Well-Architected Framework)**:
  - **Excelencia operativa**: Se enfoca en la gestión y operación eficientes de los sistemas para proporcionar valor continuamente.
  - **Seguridad**: Protege la información, sistemas y activos mediante controles adecuados y la implementación de prácticas de seguridad.
  - **Confiabilidad**: Asegura que las aplicaciones sean resilientes y puedan recuperarse rápidamente de fallos.
  - **Eficiencia de rendimiento**: Utiliza recursos de manera eficiente y adapta la capacidad a las necesidades del negocio.
  - **Optimización de costos**: Maneja los gastos asociados a la infraestructura y busca oportunidades para reducir costos sin comprometer el rendimiento.
  - **Sostenibilidad**: Considera el impacto ambiental y optimiza el uso de recursos para reducir la huella de carbono.

### Identificación de los Pilares
- **Excelencia operativa vs. Seguridad**: Excelencia operativa se centra en la eficiencia y el monitoreo, mientras que Seguridad se enfoca en proteger los recursos y datos.
- **Confiabilidad vs. Eficiencia de rendimiento**: Confiabilidad se asegura de que las aplicaciones sean resilientes, mientras que Eficiencia de rendimiento busca un uso óptimo de los recursos.

## Declaración de Tarea 1.3: Comprender los beneficios y las estrategias de migración a la nube de AWS

### Beneficios de la Migración a la Nube
- **Reducción de costos**: Migrar a la nube elimina la necesidad de mantener hardware y reduce los costos operativos.
- **Agilidad y flexibilidad**: Permite a las organizaciones responder rápidamente a cambios en el mercado y ajustar recursos según sea necesario.
- **Acceso a tecnología avanzada**: La nube proporciona acceso a las últimas tecnologías y servicios sin necesidad de inversiones en infraestructura propia.

### Estrategias de Migración
- **Enfoque Lift-and-Shift**: Mover aplicaciones a la nube sin realizar cambios significativos en su diseño o arquitectura.
- **Replataformización**: Modificar algunas características de las aplicaciones para aprovechar las capacidades de la nube mientras se mantiene la base del código.
- **Refactorización**: Rediseñar y reescribir aplicaciones para aprovechar al máximo las capacidades de la nube.
- **Uso de AWS Snowball**: Utilizar dispositivos físicos para transferir grandes volúmenes de datos a AWS, especialmente útil para migraciones a gran escala.

## Declaración de Tarea 1.4: Comprender los conceptos de la economía en la nube

### Conceptos de la Economía en la Nube
- **Costos fijos vs. costos variables**:
  - **Costos fijos**: Gastos que no cambian con el uso, como el hardware y los costos de mantenimiento.
  - **Costos variables**: Gastos que fluctúan con el uso de recursos, como el almacenamiento y la computación en la nube.
- **Ahorro de costos al migrar a la nube**: La nube elimina la necesidad de grandes inversiones iniciales y permite a las empresas pagar solo por lo que utilizan, lo que puede resultar en un ahorro significativo.
- **Estrategias de licencias**:
  - **Modelo BYOL (Bring Your Own License)**: Permite a los clientes llevar sus licencias existentes a la nube.
  - **Licencias incluidas**: Los costos de licencia están incluidos en el precio de los servicios en la nube, simplificando la gestión de licencias.
- **Dimensionamiento correcto**: Ajustar los recursos en la nube para satisfacer las necesidades específicas de la aplicación sin sobreaprovisionar.
- **Beneficios de la automatización**:
  - **Aprovisionamiento y gestión de la configuración con AWS CloudFormation**: Facilita la creación y gestión de recursos mediante plantillas de infraestructura como código.
- **Servicios gestionados de AWS**:
  - **Amazon RDS**: Servicio gestionado para bases de datos relacionales.
  - **Amazon ECS**: Servicio para ejecutar y escalar contenedores Docker.
  - **Amazon EKS**: Servicio gestionado para Kubernetes.
  - **Amazon DynamoDB**: Base de datos NoSQL gestionada.

## DOMINIO #2 CLF-C02: SEGURIDAD Y CUMPLIMIENTO

### Declaración de Tarea 2.1: Comprender el modelo de responsabilidad compartida de AWS.

### Declaración de Tarea 2.2: Comprender los conceptos de seguridad, gobernanza y cumplimiento en la nube AWS.

### Declaración de Tarea 2.3: Identificar las capacidades de gestión de acceso de AWS.

### Declaración de Tarea 2.4: Identificar componentes y recursos de seguridad.

## DOMINIO #3 CLF-C02: TECNOLOGÍA Y SERVICIOS EN LA NUBE

### Declaración de Tarea 3.1: Definir métodos de despliegue y operación en la nube AWS.

### Declaración de Tarea 3.2: Definir la infraestructura global de AWS.
