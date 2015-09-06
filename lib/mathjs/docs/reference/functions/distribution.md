# Function distribution

Create a distribution object with a set of random functions for given
random distribution.


## Syntax

```js
math.distribution(name)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`name` | string | Name of a distribution. Choose from 'uniform', 'normal'.

### Returns

Type | Description
---- | -----------
Object | Returns a distribution object containing functions: `random([size] [, min] [, max])`, `randomInt([min] [, max])`, `pickRandom(array)`


## Examples

```js
var normalDist = math.distribution('normal'); // create a normal distribution
normalDist.random(0, 10);                     // get a random value between 0 and 10
```


## See also

[random](random.md),
[randomInt](randomInt.md),
[pickRandom](pickRandom.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->