# Configuracion de ventanas, shortcuts y otros para un mejor manejo de Parrot para el uso de pentesting

### Muy recomendable para el uso junto a Hack The Box (HTB)

**Enlace del video**

[https://www.youtube.com/results?search_query=s4vitar+entorno+linux](https://www.youtube.com/results?search_query=s4vitar+entorno+linux)

**Problemas que tuve con Parrot 4.9**

A la hora de definir el shortcut para crear una terminal resulta que gnome-terminal trabaja con python 3.5 y esta version de parrot viene por defecto con python 3.8 lo cual no es compatible y poner "gnome-terminal" como shortcut de la terminal no dara resultado.

Es recomendable ver la version de python3: 

```
python3 --version
```

si no es 3.5 se puede usar la siguiente opcion:

- x-terminal-emulator

O caso contrario cambiar la version de python 3 

puedes ver difrentes terminle accediendo a la opcion caja configurada en sxhkd que es winodws + d

Y colocar terminal y haber que sale...

saldra gnome terminal y otras