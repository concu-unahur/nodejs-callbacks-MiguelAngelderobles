# Operaciones con callbacks

En `operacionesCallbacks.js` hay definidas tres funciones.
* ¿En alguna función hay un _callback_?
*  Completá `res1` para que valga 15.
* Completá `res2` para que valga 30.
* Averiguá cuánto vale `res3`.


# Esperando que algo termine para mostrarlo o usarlo, con calbacks

En `arreglarCallback.js` hay definida una función `suma`. Corré el código así cómo está.
* ¿Por qué el `console.log` da `undefined`.
* Completá la función `sumaBien` para que, mediante un callback, el `console.log` comentado más abajo muestre el resultado esperado.


# Haciendo mi propio `map`
Muchas lenguajes tienen la función `map`, que lo que hace es recibir un array y a cada elemento aplicarle un función, y devolver el nuevo array. Por ejemplo si mapeo el array `[2,6,10]` contra la función sumar 1, me devuel el array `[3,7,11]`.

Mediante un callback, hacete tu propia función `map` completando en `mapCallback.js` la función `miMap`.