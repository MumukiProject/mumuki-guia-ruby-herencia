¡Muy bien! Implementar **métodos abstractos** en una clase abstracta nos permite decir:

_"Las clases que hereden de mí tienen que hacer esto, pero que ellas decidan **cómo**"._

Por eso, `volar!` en `Ave` es **abstracto**, pero tiene implementaciones **concretas** en `Halcón` y `Cóndor`. Cada una de las aves tiene su propia forma de `volar!`, pero no hay una forma genérica que podamos ver en la clase `Ave`.