---
description: >-
  An exception is what happens when something didn't work well. An error is an
  object describing that.
---

# Exceptions and Errors

An exception is what happens when something didn't work well. An error is an object describing that.

## Throwing exceptions

### When do I have to throw an exception?

You can throw an exception when you encounter an unexpected scenario. For example, when trying to access an array and that array is missing. 

However, that depends on how you are implementing your code. Implementing custom exceptions is completely optional.

You can throw an exception in any point of your code using throw. **This will stop the script execution.**

```javascript
throw "couldn't connect to server"
```

You can throw anything. Usually, we use the Error object:

```javascript
throw new Error("couldn't connect to server")
```

## Catching exceptions

An exception stops the script execution, **unless you catch it**

```javascript
try {
    // code that could potentially cause an exception
} catch (e) {
    // this will be executed when an exception gets catched
    // from this point, your script will continue executing
}
```

## Types and properties of Error

{% embed url="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global\_Objects/Error" caption="Error object in JavaScript" %}

## Examples

Throwing a custom error and catching it 

{% embed url="https://jsfiddle.net/albertvazquezm/824br7sc/8/" %}

## Exceptions in promises

Promises executors and handlers have an invisible "try...catch" wrapping your code. **Any exception is treated as a rejection**

{% embed url="https://javascript.info/promise-error-handling" %}

{% embed url="https://jsfiddle.net/albertvazquezm/xpg3qs5f/" %}

\*\*\*\*













