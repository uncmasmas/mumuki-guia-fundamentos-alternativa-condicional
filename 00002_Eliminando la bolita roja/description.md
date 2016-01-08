Analicemos el programa del ejercicio anterior:

```puppet
program {
  if (hayBolitas(Negro)) {
    Sacar(Negro)
  } 
}
```

Como notarás, introdujimos una nueva estructura de control: el **if**, que en castellano significa _si_; entendiendo al _si_ como **condicional** ("_si_ tuviera hambre me comería una empanada") y no como afirmación ("_sí_, yo rompí el teléfono").

Entonces, lo que le estamos diciendo a la computadora es _"si hay bolitas negras, sacá una bolita negra"_, que dicho así suena un poco tonto ¡y lo es!. Ya te dijimos que la computadora sólo sabe cumplir órdenes.

> Probá vos ahora: modificá el programa que te dimos para que saque una bolita roja, sólo _si_ hay alguna.