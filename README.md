# Actividad 3: Hadoop-Yarn-Hive-PowerBI
Levantar un flujo analítico sencillo con estos servicios: Hadoop + YARN + Hive + PowerBI. No usar Spark.

Para poder cargar datos con Power BI desde hive en hadoop y yarn necesitas tener un contenedor con hive e insertar una base de datos con una tabla con datos y el contenedor tiene que estar corriendo para poder hacer la conexión correctamente.

git clone https://github.com/big-data-europe/docker-hive.git

## 1.
Descargar Power BI desktop para poder conectarte con la base de datos de Hive.

## 2. 
Dentro de Power BI, obtener datos de otro origen y buscar Hive LLAP.

## 3. 
Una vez conectado con Hive LLAP, el servidor es el puerto que tiene el contenedor de Hive, la base de datos es el nombre de la base de datos que este creada en Hive, el protocolo estandar y el modo de conectividad importar.

## 4. 
Conectar al servidor con nombre root y contraseña root.

## 5. 
Seleccionar la base de datos y la tabla deseada y cargarla desde Power BI.
