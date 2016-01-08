Vamos a hacer un programa que saque una bolita de manera "segura": no tiene que producirse un _BOOM_, aún cuando no haya ninguna bolita en la celda actual.

Con lo que sabés hasta ahora, probablemente tu primera idea sea hacer algo como esto:

```puppet
program {
  Sacar(Negro)
}
```

Te invitamos a que antes de seguir leyendo pruebes de ejecutar ese programa y veas qué pasa, nosotros te esperamos...

:hourglass:

:hourglass_flowing_sand:

¿Te diste cuenta qué pasó? Funcionó para el primer tablero, porque tenía una bolita, pero hizo _BOOM_ para el segundo, porque estaba vacío, claro.

Ahora probá esta segunda versión, que agrega un `if`. No te preocupes por la sintaxis, ya te lo vamos a explicar. :smile:

```puppet
program {
  if (hayBolitas(Negro)) {
    Sacar(Negro)
  } 
}
```