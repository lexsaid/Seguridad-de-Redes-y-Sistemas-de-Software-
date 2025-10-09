### Descripcion
Help us test the form by submiting the username as `test` and password as `test!`The website running [here](http://saturn.picoctf.net:53176/).

### Solucion
aqui usamos la aplicacion burp suite
al iniciar sescion nos sale esto
![[Pasted image 20251008131447.png]]
lo agarramos porque parece que es un encriptado
despues de eso
![[Pasted image 20251008131808.png]]
hay vemos 2 id muy parecidos, los deciframos a base64 y nos da la llave
picoCTF{proxies_all_the_way_a0fe074f}


### Notas


### Referencias