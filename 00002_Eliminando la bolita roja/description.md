Analicemos el procedimiento del ejercicio anterior:

```puppet
procedure SacarAzulConMiedo() {
  if (hayBolitas(Azul)) {
    Sacar(Azul)
  } 
}
```

Como notarás, introdujimos una nueva estructura de control: el **if**, que en castellano significa _si_; entendiendo al _si_ como **condicional** ("_si_ tuviera hambre me comería una empanada") y no como afirmación ("_sí_, yo rompí el teléfono").

Entonces, lo que le estamos diciendo a la computadora es _"si hay bolitas azules, sacá una bolita azul"_, que dicho así suena un poco tonto ¡y lo es!. Ya te dijimos que la computadora sólo sabe cumplir órdenes.

> Probá vos ahora: modificá el procedimiento que te dimos para que saque una bolita roja, sólo _si_ hay alguna.