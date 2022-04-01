# Javascript-Spread-Operators

The `Spread operator` allows us to join array elements  or object properties into another array or object

```
const personsFirstInformation = {
  name: "Thembi",
  surname: "Ndou"
};

const personsSecondInformation = {
  age: 25,
  gender: "Female"
};

const personsFullInformation = { ...personsFirstInformation, ...personsSecondInformation };

console.log(personsFullInformation);
/// Will print:
/// { name: 'Thembi', surname: 'Ndou', age: 25, gender: 'Female' }
```
```
const firstFiveNumbers = [1, 2, 3, 4, 5];

const secondFiveNumbers = [6, 7, 8, 9, 10];

const fullTenNumbers = [...firstFiveNumbers, ...secondFiveNumbers];

console.log(fullTenNumbers);
/// Will print:
/// [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```
