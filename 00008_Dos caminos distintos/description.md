En lo cotidiano, se presentan muchas situaciones donde debemos elegir entre dos acciones diferentes, dependiendo de si se cumple una cierta condición o no. 

* Si la remera está limpia me la pongo, _si no_ la lavo.
* Si no tengo aceite para freir las milanesas uso un poco de manteca, _si no_ uso el aceite.
* Si me puedo mover al Este lo hago, _si no_ me muevo al Norte.

Podríamos utilizar la técnica de la negación para resolver problemas de este estilo, escribiendo dos `if`s: uno con la condición original (por ejemplo `puedeMover(Este)`) y otro con la condición negada (siguiendo el ejemplo, `not puedeMover(Este)`).

En ese caso, quedaría algo así:

```puppet
procedure MoverComoSea() {
    if (puedeMover(Oeste)) {
        Mover(Oeste)
    } 
    
    if (not puedeMover(Oeste)) {
        Mover(Norte)
    }
}
```

> Copiá ese código en el editor y fijate cómo resuelve el problema.