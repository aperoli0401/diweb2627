# Actividad 4 - Tema 7

1. ¿Qué color tendrá el texto?
Se quedará de color rojo debido a que #principal p tiene mayo especificidad.

2. ¿Qué selector tiene mayor especificidad?
El #principal p.

3. ¿Qué ocurriría si eliminamos el selector #principal p?
En caso de eliminarlo se pasaría a aplicar el estilo de .mensaje.destacado, entocnes el texto cambiaría a morado.

4. ¿Qué sucedería si añadimos otra regla .mensaje.destacado al final?
Depende, si tenemos #principal p sigue el color rojo . En caso contrario se aplicaría la regla de .mensaje.destacado por orden en la cascada.

5. ¿Qué buenas prácticas aplicarías para evitar este tipo de conflictos?
Yo usaría mejor class que ID porque pesan menos luego para sobreescribirlos y tambien evitaría cadenas largas.