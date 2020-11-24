---
description: Errors is the way JavaScript has to tell us something wrong has occurred
---

# Errors

Errors are objects that JavaScript engine or ourself as developers throw when something wrong occurs.

## Types of Error

There is a generic Error object. However, there are this specific types.

* [`EvalError`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/EvalError)Crea una instancia que representa un error que ocurre con respecto a la función global [`eval()`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/eval).
* [`InternalError`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/InternalError)Crea una instancia que representa un error que ocurre cuando se produce un error interno en el motor de JavaScript. Por ejemplo: "demasiada recursividad".
* [`RangeError`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/RangeError)Crea una instancia que representa un error que ocurre cuando una variable numérica o parámetro está fuera de su rango válido.
* [`ReferenceError`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/ReferenceError)Crea una instancia que representa un error que ocurre cuando se quita la referencia a una referencia no válida.
* [`SyntaxError`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/SyntaxError)Crea una instancia que representa un error de sintaxis.
* [`TypeError`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/TypeError)Crea una instancia que representa un error que ocurre cuando una variable o parámetro no es de un tipo válido.
* [`URIError`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/URIError)Crea una instancia que representa un error que ocurre cuando [`encodeURI()`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/encodeURI) o [`decodeURI()`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/decodeURI) pasan parámetros no válidos.

## Properties of Error

* [`Error.prototype.message`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Error/message)Mensaje de error.
* [`Error.prototype.name`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Error/name)Nombre del error.

## How to debug Errors

### The stack

The stack tells us where the error comes from



















