Mapa Conceptual de AWS


![Logo de AWS](logos/amazon-web-services.png)


🗂️ Modelo Conceptual de Servicios AWS

Este documento presenta un mapa conceptual del ecosistema de Amazon Web Services (AWS), organizado por categorías principales. El propósito del modelo es identificar los servicios clave, sus funciones y su relación dentro de la arquitectura de la nube.

A continuación se presentan las cuatro familias de servicios del modelo, cada una con un espacio para agregar los logos de los componentes.

1. ☁️ CÓMPUTO (Compute)

![Logo de compute](logos/compute.jpeg)

Los servicios de cómputo de AWS permiten ejecutar aplicaciones, máquinas virtuales, contenedores y funciones sin servidor.

Servicios incluidos:
🖥️ Amazon EC2 (Máquinas virtuales)

![Maquina virtual](logos/maquinavirtual.png)

EC2 permite ejecutar servidores virtuales configurables según RAM, CPU y almacenamiento.

⚡ AWS Lambda (Serverless)

![Lambda](logos/lambda.png)


Lambda ejecuta funciones bajo demanda sin administrar servidores.

📦 Amazon ECS / Amazon EKS (Contenedores)

![ecs](logos/ecs.png)
![eks](logos/eks.png)


ECS y EKS permiten ejecutar contenedores en arquitecturas escalables.

2. 🧠 BASES DE DATOS (Database)
[Inserta aquí el logo general de Database de AWS]


Servicios para almacenamiento estructurado y no estructurado.

Servicios incluidos:
🛢️ Amazon RDS

![rds](logos/rds.png)


Base de datos relacional administrada por AWS.

⚡ Amazon DynamoDB

![dynamo](logos/dynamo.png)


Base NoSQL completamente gestionada.

🚀 Amazon Aurora

![aurora](logos/aurora.jpg)



Motor relacional de alto desempeño compatible con MySQL/PostgreSQL.

3. 📦 ALMACENAMIENTO (Storage)
![storage](logos/storage.png)



AWS proporciona almacenamiento seguro, escalable y de alta disponibilidad.

Servicios incluidos:
🗃️ Amazon S3

![s3](logos/s3.png)


Almacenamiento de objetos con durabilidad de 99.999999999%.

💾 Amazon EBS

![ebs](logos/ebs.jpg)

Volúmenes de discos persistentes para instancias EC2.

📁 Amazon EFS

![efs](logos/efs.png)


Sistema de archivos compartido para múltiples instancias.

4. 🔐 SEGURIDAD (Security & Identity)
![seguridad](logos/seguridad.png)


Servicios orientados al control de usuarios, permisos, cifrado y protección de redes.

Servicios incluidos:
🛡️ AWS IAM
![iam](logos/iam.jpeg)

iam.jpeg

Gestión de usuarios, roles y permisos.

🌐 Amazon VPC

![vpc](logos/vpc.png)


Permite crear redes privadas dentro de AWS.

🔑 AWS KMS

![kms](logos/kms.png)


Administración de llaves criptográficas y cifrado.

![diagrama](Distribuidos.drawio.png)