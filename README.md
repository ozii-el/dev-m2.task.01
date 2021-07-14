# dev-m2.task.01
Tarea 01 del Módulo 02 - Desarrollo con Base de datos



## ¿Cómo iniciar?
1) Hacer Fork del repositirio dev-m2.task.01 y clonarlo en su ambiente local.
2) Abrir Azure Data Studio y conectare a su base correspondiente.
3) Crear un archivo con extencion .sql donde van a guardar sus scripts y subirlos a GitHub  `creacionTablas.sql`
4) Crear las siguentes tablas
    
    `EntidadFederativa` con los siguientes campos `EntidadID, Nombre, NombreAbreviado, PoblacionTotal, PoblacionMasculina, PoblacionFemenina`
    
    `Municipio` con los siguientes campos `MunicipipID, Nombre, PoblacionTotal, PoblacionMasculina, PoblacionFemenina`
    
    `Localidad` con los siguientes campos `LocalidadID, Nombre, Ambito, LatitudDecimal, LongitudDecimal, Altitud, PoblacionTotal, PoblacionMasculina, PoblacionFemenina`

    Pueden seguir el ejemplo que vimos en la clase para crear la tabla e insertar datos.
```

CREATE TABLE dbo.Products  
   (ProductID int PRIMARY KEY NOT NULL,  
   ProductName varchar(25) NOT NULL,  
   Price money NULL,  
   ProductDescription varchar(max) NULL)  

```
5) Insertar todas las Entidades Federativas
6) Insertar 30 Municipios
7) Insertar 30 Localidades


**Nota: Los cátalogos que vamos a tomar como base son los del INEGI** 
``https://www.inegi.org.mx/app/ageeml/#``


