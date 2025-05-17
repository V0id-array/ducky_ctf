# ducky_ctf

## Uso:
Descargar duck_ctf y ejecutar en terminal:
Este CTF se creó para ejecutarse con un equipo linux con gwen viewer y firefox

```bash
./duck_ctf
```

## Solución

encontrar archivo con find:

```bash
find / -name "*comida*"
```

Copiar y pegar el contenido de /tmp/.comida_patos.txt en el terminal

Después de esto se descargará un zip con un gif

Con exiftool buscar en los metadatos por la flag:

```bash
 exiftool victory.gif

Comment                         : synt{dh4px_dh4px91}

```

Con ciberchef en rot13 desencriptar


