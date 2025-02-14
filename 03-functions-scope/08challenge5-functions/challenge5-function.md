# Function Challenges

Now that you know the basics of how functions work, let's try a few challenges.

## Challenge 1

**Instructions:**

Create a function called `getCelsius()` that takes a temperature in Fahrenheit as an argument and returns the temperature in Celsius.

For bonus points, write it as a one-line arrow function.

**Expected Result:**

```JavaScript
console.log(getCelsius(32)); // 0
```

You can make the output look prettier by putting it into a string. You can even add `\xB0` (degrees) and a `C` in front of the Celsius temperature.

```JavaScript
console.log(`The temperature is ${getCelsius(32)} \xB0C`);
// The temperature is 0 °C
```

**Hints:**

The formula for Fahrenheit to Celsius is `(F - 32) * 5 / 9`. Read more about the formula [here](https://www.cuemath.com/fahrenheit-to-celsius-formula/) if needed.

<details>
  <summary>Click For Solution</summary>

```JavaScript
// Solution Here
```

</details>

---

## Challenge 2

**Instructions:**

Create an arrow function called `minMax()` that takes in an array of numbers and returns an object with the minimum and maximum numbers in the array.

**Expected Result:**

```JavaScript
console.log(minMax([1, 2, 3, 4, 5]));
// { min: 1, max: 5 }
```

You can make the output look prettier by putting it into a string. You can even add `\xB0` (degrees) and a `C` in front of the Celsius temperature.

```JavaScript
console.log(`The temperature is ${getCelsius(32)} \xB0C`);
// The temperature is 0 °C
```

**Hints:**

1. You can use `Math.min()` and `Math.max()` to get the min and max of a list of numbers.
2. You can use the Spread `...` operator to spread the values of an array into separate arguments.

<details>
  <summary>Click For Solution</summary>

```JavaScript
// Solution Here
```

</details>
