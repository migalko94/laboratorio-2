# Laboratorio Tipos de datos y Operadores

> Aquí describimos la resolución del problema expuesto en el Módulo 2

## Planteamiento

### Cena de cumpleaños entre amigos

Tienes un grupo de 6 amigos y quieres invitarlos a cenar por tu cumpleaños.

- Solo puedes permitirte invitar a las bebidas, ya que estás un poco ajustado de dinero.

- Tienes un ticket de cena que cuesta 120 € y en el que ya se incluyen las bebidas por un valor de 18 €.

- Calcula cuánto tendría que pagar cada comensal para dividir los costos de manera equitativa.

- Utiliza JavaScript para hacer el cálculo y mostrar el resultado por consola.

## Solución

### Tienes un grupo de 6 amigos y quieres invitarlos a cenar por tu cumpleaños

Si tengo un grupo de 6 amigos y voy a cenar con ellos por mi cumpleaños, somos 7 comensales.

A efectos de un reparto equitativo y sencillo, finalmente, me excluiré del pago de la comida, ya que abono las bebidas.

### Solo puedes permitirte invitar a las bebidas, ya que estás un poco ajustado de dinero + Tienes un ticket de cena que cuesta 120 € y en el que ya se incluyen las bebidas por un valor de 18 €

Entiendo que el ticket de cena es la cuenta que nos traen.

La cuenta es de 120 € y las bebidas costaron 18 € de esos 120 €. Yo sólo puedo permitirme pagar las bebidas, pero las pago. Pago los 18 € de las bebidas.

La cuenta sin las bebidas son 120 - 18 = 102 €.

Entonces,

**120-18**

### Calcula cuánto tendría que pagar cada comensal para dividir los costos de manera equitativa

La equidad dicta que al menos pague yo las bebidas (+18 € que pago yo).

Aquí vemos, dos opciones:

**Opción A** Si la cuenta restante se divide entre 6 (sin contarme a mí), da 17 euros por cabeza: 102€/6 personas= 17. En este caso, yo invité a las bebidas, pero mis amigos me invitaron a la comida.

Así pues,

**(120-18)/6**

**Opción B** Si la cuenta restante se divide entre 7 (contándome a mí), da un número muy extenso de 14, 5714286 € (redondeado 14,58 €): 102 €/7 personas.

En este caso, cada uno paga su comida.

Yo finalmente acabaría pagando los 18 € de las bebidas + 14, 5714286 € (mi parte de la comida). Esto en total da 32, 5714286 € (32,58 € aproximado). Mis amigos pagarían cada uno 14, 5714286 € (redondeado 14,58 €).

Ellos pagarían **(120-18)/7**

Yo pagaría **((120-18)/7) + 18**

Realmente los decimales nos acabarían dando problemas y no se llegaría a 120 euros justos. Además, no parece equitativo.

### Mi alternativa

Optamos por la **Opción A**. Yo pago las bebidas (18€) y mis amigos pagan la comida (17€ por cabeza). Yo pagaría sólo un euro más que ellos, pero así evitamos cifras irrepartibles y parece justo.

### Utiliza JavaScript para hacer el cálculo y mostrar el resultado por consola

Lo hacemos así:

`console.log((120-18)/6);`

Lo hacemos con el _Sandbox_ de _JavaScript_ y también con el de _TypeScript_.

En ambos casos, nos devuelve `17`.

En el laboratorio que subimos, lo expresamos con dos archivos:

**1. cenamigoscuenta.js**

Archivo de JavaScript: _.js_

**2. cenamigoscuenta.ts**

Archivo de TypeScript: _.ts_

> Fin del laboratorio

**Resubimos el laboratorio con la sandbox de TS, en cuyo main implementamos la solución.**
