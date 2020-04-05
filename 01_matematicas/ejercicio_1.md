<h2>Ejercicio</h2>

Resolver la siguiente ecuación:

$\int\ {x^2} e^{-x+3} dx$

<h2>Resolución 1:</h2>
    
Al poseer una función algebraica ($x^2$) y la segunda función es exponencial ($e^x$) se realiza mediante la integración por partes:
    
Para la <b>primera</b> parte: Se determina $du$ derivando $u$

$ u = x^2 $ 

$ du = 2x dx $


Para la <b>segunda</b> parte: Se determina $v$ integrando

$ dv = e^{-x+3} $

$ v = -e^{-x+3} $


Se integra por partes reemplazando:

$ uv - \int v {du} $

$ x^2 (-e^{-x+3}) - \int (-e^{-x+3}) {(2x dx)} $

$ -x^2 e^{-x+3} + 2 \int {x e^{-x+3}dx} $

A la integral se le vuelve a integrar por partes:

Se tiene lo siguiente:

$ \int {x e^{-x+3}dx} = -x e^{-x+3} - e^{-x+3} $

Reemplazando:

$ -x^2 e^{-x+3} + 2 (-x e^{-x+3} - e^{-x+3}) $

Factorizando nos queda:

<h3 style="color:red"><b>$ -e^{-x+3} (x^2 + 2x + 2) + c $</b></h3>


<h2>Resolución 2:</h2>

Mientras $u$ sea algebraica puede utilizarse el método de tabulación:

Se derivan la columna $u$, se integra la columna $dv$:

| $u$ | $dv$ |
| :---:|:-----:|
| $x^2$  | $e^{-x+3}$ |
| $2x$ | $-e^{-x+3}$ |
| $2$  | $e^{-x+3}$ |
| $0$  | $-e^{-x+3}$ |

Se multiplica en diagonal:

$ (x^2) (-e^{-x+3}) - (2x)(e^{-x+3}) + (2)(-e^{-x+3}) + c$

$ -x^2 e^{-x+3} - 2x e^{-x+3} - 2 e^{-x+3} + c $

$ e^{-x+3} (-x^2 - 2x -2 ) + c $

<h3 style="color:red"><b>$ -e^{-x+3} (x^2 + 2x + 2) + c $</b></h3>
