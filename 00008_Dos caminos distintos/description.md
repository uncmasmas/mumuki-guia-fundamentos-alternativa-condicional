En lo cotidiano, se presentan muchas situaciones donde debemos elegir entre dos acciones diferentes, dependiendo de si se cumple una cierta condición o no. 

* Si la remera está limpia me la pongo, _si no_ la lavo.
* Si no tengo aceite para freir las milanesas uso un poco de manteca, _si no_ uso el aceite.
* Si me puedo mover al Este lo hago, _si no_ me muevo al Norte.

Con lo que sabemos, podríamos utilizar la técnica de la negación para resolver problemas de este estilo. ¿Y cómo sería esto? Escribiendo dos `if`s: uno con la condición original y otro con la misma condición, pero negada. 

Supongamos que queremos hacer un procedimiento que se mueva al Oeste, y en caso de que no pueda lo haga hacia el Norte. Deberíamos tener un primer `if` que chequee si es posible moverse al Oeste y lo haga, y luego un segundo `if` que chequee que **no** es posible moverse al Oeste y se mueva al Norte. 

Veamos cómo quedaría esto con un poco de código:

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