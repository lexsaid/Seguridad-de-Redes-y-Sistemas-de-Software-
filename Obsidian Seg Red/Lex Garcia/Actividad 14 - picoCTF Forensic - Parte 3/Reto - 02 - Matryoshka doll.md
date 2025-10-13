### Descripcion
Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one? Image: [this](https://mercury.picoctf.net/static/b6205dd933ec01c022c4e6acbdf11116/dolls.jpg)

### Solucion
descargamos el archivo y vemos que es una imagen, hacemos un binwalk para ver que contiene y vemos que contenia una carpeta, adentro de ella habia un zip y otra imagen, descomprimimos el zip y hacemos un binwalk a la nueva imagen que habia, hacemos esto como 3 veces mas hasta llegar a una ultima imagen, donde este nos dice que contiene un flag.txt, descomprimimos la imagen y nos suelta el txt con la bandera

### Notas


### Referencias
