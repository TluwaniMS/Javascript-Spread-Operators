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
{ name: 'Thembi', surname: 'Ndou', age: 25, gender: 'Female' }
```
