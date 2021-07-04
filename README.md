# kafka Container
Configuración para un zookeeper y tres broker de kafka, con los listener internos y externos

### Configuraciones:
cree la carpeta en donde dejara el archivo .yml y cree en este las siguientes carpetas:

#### data:
/data/broker-1
/data/broker-2
/data/broker-3
#### configuraciones(properties):
/config/broker-1
/config/broker-2
/config/broker-3

### Ejecute:

Una vez descargado el archivo docker-compose.yml, ejecute en la terminal el siguiente comando para
levantar los servicios de kafka con los tres brokers
```cs
docker-compose up
```