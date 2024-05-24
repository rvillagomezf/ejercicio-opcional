# EJERCICIO OPCIONAL 
### Hacer un script que tenga una lista de 5 mascotas: perro, gato, tortuga, pez, cobra; 

* Cuando la variable tenga un valor de perro, deberá imprimir:  ¡GUAU!
* Cuando tenga valor de gato: ¡MUAU!
* Cuando tenga valor de tortuga: "..." (sin comillas)
* Cuando tenga valor de pez: GLUGLU
* Cuando tenga valor de cobra: ZZZZ

```
#!/bin/bash

for i in perro gato tortuga pez cobra
do 
        echo "$i"

done


read -p "Selecciona una mascota de la lista:" MASCOTA


case $MASCOTA in 
        "perro")
                echo "!GUAU¡"
                ;;
        "gato")
                echo "!MIAU¡"
                ;;
        "tortuga")
                echo "..."
                ;;

        "pez")
                echo "GLUGLU"
                ;;
        "cobra")
                echo "ZZZZ"
                ;;
esac

```
