#### **¿Qué es una base de datos relacional?**

- **Definición**: Colección de datos organizados en **tablas** (filas y columnas) relacionadas entre sí.
    
    - **Tabla** = Estructura que almacena datos (ej: `usuarios`, `productos`).
        
    - **Fila (registro)** = Entrada individual (ej: un usuario).
        
    - **Columna (atributo)** = Tipo de dato (ej: `nombre`, `edad`)
    
- - Lenguaje estándar para gestionar bases de datos relacionales.
    
- Se usa para:
    
    - **Consultar** datos (`SELECT`).
        
    - **Insertar/Modificar/Eliminar** datos (`INSERT`, `UPDATE`, `DELETE`).
        
    - **Definir estructuras** (`CREATE TABLE`, `ALTER TABLE`).

#### Para crear una tabla en SQL

```sql
CREATE TABLE usuarios (
    id INT PRIMARY KEY,
    nombre VARCHAR(50),
    edad INT,
    email VARCHAR(100)
);
```
