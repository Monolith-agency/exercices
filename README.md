# Exercices

> *No Third party tool !*

## Rewrite `Array.reduce` without using any Array function

```js
/**
 * Reduce
 * @param {[any]} array Array of any data
 * @param {function} cb Callback function executed each iteration
 * @param {any} init Inital value of the accumulator
 * @returns {any} The final accumulator value
 */
const reduce = (array, cb, init) => {}
```

## Using the following documentation: https://dog.ceo/dog-api/documentation, create a function that fetch one doggo image by breed

```js
/**
 * @returns {[string]} An array of image URL
 */
const getDoggos = () => {}
```

## Using the following documentation https://pokeapi.co, create a function that the first 20 pokemons and group them by type in an object

```js
/**
 * @return {object} Pokemon grouped by type
 */
const getPokemons = () => {}
```

## Modify the previous function to make sure there is a 3 seconds interval between each fetch. Any consecutive function call should queue.

> **Example:**
> ```js
>  // The following code should trigger 3 fetch, one right away,
>  // one in 3s, and one in 6s.
>  getPokemonsDelayed()
>  getPokemonsDelayed()
>  getPokemonsDelayed()
> ```

```
/**
 * @return {object} Pokemon grouped by type
 */
const getPokemonsDelayed = () => {}
```
