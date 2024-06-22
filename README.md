# SSIS_SoftDevelopers
A continuacion se presenta el proyecto SSIS del caso de estudio #5 llamado SoftDevelopers, asegurese de revisar el archivo README para evitar errores/inconvenientes al ejecutar el proyecto

Se ha adjuntado al repositoro una carpeta llamada "Databases_backup" que contiene los respaldos de las bases de datos utilizadas para evitar el retraso de ejecutar todos los scripts DDL y DML, a su vez hay un Script llamado "Truncate_Tables(Staging&Dim)" que se encarga de limpiar la base de datos que sera usada como Datawarehouse, se recomienda ejecutar este script luego de realizar la restauracion de la base de datos, puesto que el DW se encuentra lleno.

Nota: Se probaron diversos proveedores de sqlserver en el proyecto,  y se han seleccionado los que no presentaron ni una falla en ninguna de las tareas, si por algun motivo el proveedor "Microsoft OLE DB Driver for SQL Server" presenta algun error algun error se recomienda cambiarlo a "Microsoft OLE DB Provider For SQL Server".
