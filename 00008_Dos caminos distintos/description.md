En lo cotidiano, se presentan muchas situaciones donde debemos elegir entre dos acciones diferentes, dependiendo de si se cumple una cierta condición o no. 

* Si la remera está limpia me la pongo, _si no_ la lavo.
* Si tengo aceite para freir las milanesas lo uso, _si no_ le pongo un poco de manteca.
* Si me puedo mover al Este lo hago, _si no_ me muevo al Norte.

Para estos casos, en Gobstones tenemos una nueva palabra clave que nos ayuda a cumplir nuestra tarea: el **else**. En castellano significa _si no_ y hace justamente lo que necesitamos, ejecuta una serie de acciones _si no se cumple_ la condición que pusimos en el `if`.

Supongamos que queremos hacer un procedimiento que se mueva al Oeste, y en caso de que no pueda lo haga hacia el Norte. Haciendo uso del `else`, podemos escribirlo de la siguiente manera:

```puppet
procedure MoverComoSea() {
    if (puedeMover(Oeste)) {
        Mover(Oeste)
    } else {
        Mover(Norte)
    }
}
```

> Copiá ese código en el editor y fijate cómo resuelve el problema.