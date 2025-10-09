### Descripcion
Can you abuse the banner?The server has been leaking some crucial information on `tethys.picoctf.net 50647`. Use the leaked information to get to the server.To connect to the running application use `nc tethys.picoctf.net 64308`. From the above information abuse the machine and find the flag in the /root directory.

### Solucion
entramos al 1er link y nos muestra la contraseña y despues entramos al 2do link que nos dan y llenamos los campos con lo siguiente
![[Pasted image 20251007124004.png]]
![[Pasted image 20251007124034.png]]
despues de ello tratamos de ver que hay en root
![[Pasted image 20251007124910.png]]
vemos que esta posiblemente la bandera pero tambien hay un py, observamos que hay
![[Pasted image 20251007125006.png]]
![[Pasted image 20251007125007.png]]

![[Pasted image 20251007125139.png]]
hacemos un rm banner para que asi al ingresar de nuevo al link nos muestre la bandera
picoCTF{b4nn3r_gr4bb1n9_su((3sfu11y_b3ee718e}


### Notas


### Referencias