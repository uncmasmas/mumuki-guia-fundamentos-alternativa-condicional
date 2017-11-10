En todos los problemas que hicimos hasta ahora, siempre preguntamos si una cierta condición se cumplía: ¿hay alguna bolita roja? ¿me puedo mover al Este? ¿hay más de 3 bolitas azules?

Algo que también se puede hacer es **negar** una condición, algo que en castellano puede sonar medio raro pero que en programación se hace un montón. Los ejemplos anteriores quedarían: ¿**no** hay alguna bolita roja? ¿**no** me puedo mover al Este? ¿**no** hay más de 3 bolitas azules?

¿Y cómo se hace en Gobstones? Fácil, se agrega la palabra clave `not` antes de la expresión que ya teníamos.

|Original|   |Negada|
|:------:|:-:|:----:|
|`hayBolitas(Rojo)`|<i class="fa fa-arrow-right"></i>|`not hayBolitas(Rojo)`|
|`puedeMover(Este)`|<i class="fa fa-arrow-right"></i>|`not puedeMover(Este)`|
|`nroBolitas(Azul) > 3`|&nbsp;&nbsp; <i class="fa fa-arrow-right"></i> &nbsp;&nbsp;|`not nroBolitas(Azul) > 3`|

&nbsp;

> Escribí un programa que se asegure que en la celda actual hay al menos una bolita verde. Esto es: si ya hay bolitas verdes no hay que hacer nada, pero si **no** hay tendría que poner una.