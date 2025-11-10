### Descripcion
In the last challenge, you mastered octal (base 8), decimal (base 10), and hexadecimal (base 16) numbers, but this vault door uses a different change of base as well as URL encoding!The source code for this vault is here: [VaultDoor5.java](https://challenge-files.picoctf.net/c_fickle_tempest/e0273648f1276c71952d98ee6611263932f766fd288de297c1881a0e4fcd775c/VaultDoor5.java)

### Solucion
este use la pagina de cyberchef, vemos que es en base64 despues de convertirlo nos lo manda a hex y despues de eso ya se ve la bandera

### Notas


### Referencias
https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false/disabled)From_Hex('Auto')&input=JTYzJTMwJTZlJTc2JTMzJTcyJTc0JTMxJTZlJTY3JTVmJTY2JTcyJTMwJTZkJTVmJTYyJTYxJTM1JTY1JTVmJTM2JTM0JTVmJTM0JTMyJTYzJTM2JTM0JTMwJTM5JTYy&oeol=FF