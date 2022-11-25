# dice-roll

```js
/*
* @param totalRolls int - amount of times you wish to roll a dice
* @param dice int - amount of dice you wish to roll each time
*
* @return int - sum of the results of all rolls
* /
const sumDice = (totalRolls, dice = 1) => {
    const rollDice = () => Math.ceil(Math.random() * 6);

    var sum = 0;
    for(let rolls = 0; rolls < totalRolls; rolls++) {
        for(let diceNumber = 0; diceNumber < dice; diceNumber++) {
            sum += rollDice();    
        }
    }
    return sum;
}

// rolls 1 die a million times
// the result should always approach the number 3,500,000
sumDice(1000000, 1);


// rolls 2 dice a hundred times
// the result should always approach the number 7000
sumDice(1000, 2);


// rolls 3 dice a hundred times
// the result should always approach the number 105000
sumDice(10000, 3);
```

