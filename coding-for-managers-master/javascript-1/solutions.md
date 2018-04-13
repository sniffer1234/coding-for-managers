# Solutions

## Javascript Basic

- [Exercise 1](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-1.php)
- [Exercise 2](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-2.php)
- [Exercise 3](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-3.php)
- [Exercise 4](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-4.php)
- [Exercise 5](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-5.php)
- [Exercise 6](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-6.php)
- [Exercise 7](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-7.php)
- [Exercise 8](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-8.php)
- [Exercise 9](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-9.php)
- [Exercise 10](http://www.w3resource.com/javascript-exercises/javascript-basic-exercise-10.php)


## Functions

### The Fortune Teller

```js
function tellFortune(jobTitle, geoLocation, partner, numKids) {
    var future = 'You will be a ' + jobTitle + ' in ' + geoLocation + ' and married to ' +
   partner + ' ' + ' with ' + numKids + ' kids.';
    console.log(future);
}

tellFortune('bball player', 'spain', 'Shaq', 3);
tellFortune('stunt double', 'Japan', 'Ryan Gosling', 3000);
tellFortune('Elvis impersonator', 'Russia', 'The Oatmeal', 0);
```

### The Puppy Age calculator
```js
function calculateDogAge(age) {
    var dogYears = 7*age;
    console.log("Your doggie is " + dogYears + " years old in dog years!");
}

calculateAge(1);
calculateAge(0.5);
calculateAge(12);
```

### The Lifetime Supply calculator
```js
function calculateSupply(age, numPerDay) {
  var maxAge = 100;
  var totalNeeded = (numPerDay * 365) * (maxAge - age);
  var message = 'You will need ' + totalNeeded + ' cups of tea to last you until the ripe old age of ' + maxAge;
  console.log(message);
}

calculateSupply(28, 36);
calculateSupply(28, 2.5);
calculateSupply(28, 400);
```

### The Geometrizer
```js
function calcGeometry(radius) {
  var circumference = Math.PI * 2*radius;
  console.log("The circumference is " + circumference);
  var area = Math.PI * radius*radius;
  console.log("The area is " + area);
}
```

### The Temperature Converter
```js
function celsiusToFahrenheit(celsius) {
  var celsiusInF = (celsius*9)/5 + 32;
  console.log(celsius + '°C is ' + celsiusInF + '°F');
}

function fahrenheitToCelsius(fahrenheit) {
  var fahrenheitInC = ((fahrenheit - 32)*5)/9;
  console.log(fahrenheit + '°F is ' + fahrenheitInC + '°C');
}
```
