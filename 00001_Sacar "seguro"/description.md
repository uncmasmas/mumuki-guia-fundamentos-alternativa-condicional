Vamos a hacer un programa que saque una bolita de manera "segura": no tiene que producirse un _BOOM_, aún cuando no haya ninguna bolita en la celda actual.

Por ser la primera vez que hacés esto, simplemente te vamos a pedir que copies el siguiente código y veas cómo resuelve el problema:

```puppet
program {
  if (hayBolitas(Negro)) {
    Sacar(Negro)
  } 
}
```

Para que nos creas, lo vamos a ejecutar primero en un tablero con una bolita negra y luego en una sin... ¡y no se va a romper!