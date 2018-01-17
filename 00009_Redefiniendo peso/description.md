¡¿400 kilos una `Bicicleta`?! ¡¿Cómo hacés para trasladarla?! :muscle: 

Algo en nuestro modelo falló: como la `Bicicleta` tiene dos ruedas, y es un `MedioDeTransporte`, su peso se calcula como 200 multiplicado por 2. ¡Pero no puede pesar tanto!

Sin embargo, no queremos que deje de heredar de `MedioDeTransporte`. Lo que podemos hacer es **redefinir** el método: si `Bicicleta` **implementa** el método `peso`, es _ese_ el que se va a evaluar en lugar del de su superclase.

En lugar de que `MedioDeTransporte` realice el cálculo, le agregamos a la propia `Bicicleta` el método `peso`, que lo calculará como la cantidad de ruedas multiplicado por 5.

> Veamos si se entiende: hacé que `Bicicleta` implemente el método `peso`.