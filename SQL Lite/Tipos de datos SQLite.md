

Repasemos los tipos de datos soportados por SQLite y cómo se almacenan.

1. `NULL`- Valor de Nul.
2. `INTEGER`- Un entero firmado almacenado en 0,1,2,3,4,6, o 8 bytes.
3. `REAL`- Valor de punto flotante almacenado como número de punto flotante IEEE de 64 bits.
4. `TEXT`- Cierra de texto almacenada mediante codificación de bases de datos como UTF-8
5. `BLOB`- Corto para el objeto grande binario y utilizado típicamente para imágenes, audio u otro medio multimedia.
6. `BOOLEAN`- Los valores booleanos están escritos en consultas SQLite como `true`o o `false`, pero se registran como `1`o o `0`.

**creacion de tabla**
```SQL
CREATE TABLE posts(
 id INTEGER,
 image_url TEXT,
 description TEXT,
 author_id INTEGER,
 is_sponsored BOOLEAN);
```
