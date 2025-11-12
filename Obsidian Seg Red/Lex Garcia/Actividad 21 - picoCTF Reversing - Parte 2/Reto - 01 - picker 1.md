### Descripcion
This service can provide you with a random number, but can it do anything else?Connect to the program with netcat:`$ nc saturn.picoctf.net 53903`The program's source code can be downloaded [here](https://artifacts.picoctf.net/c/515/picker-I.py).

### Solucion
tenemos que tener a la mano las 2 cosas
lo que hice fue ejecutar primero el saturn en la terminal, y despues ejecutamos el py que nos dan, en la terminal escribimos "win" y nos dara algo en forma de hex, fui a una pagina y resulto ser la bandera

### Notas


### Referencias
https://gchq.github.io/CyberChef/#recipe=From_Hex('Auto')&input=MHg3MCAweDY5IDB4NjMgMHg2ZiAweDQzIDB4NTQgMHg0NiAweDdiIDB4MzQgMHg1ZiAweDY0IDB4MzEgMHgzNCAweDZkIDB4MzAgMHg2ZSAweDY0IDB4NWYgMHgzMSAweDZlIDB4NWYgMHgzNyAweDY4IDB4MzMgMHg1ZiAweDcyIDB4MzAgMHg3NSAweDY3IDB4NjggMHg1ZiAweDYzIDB4NjUgMHgzNCAweDYyIDB4MzUgMHg2NCAweDM1IDB4NjIgMHg3ZA