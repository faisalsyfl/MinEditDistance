## Description
Minimum Edit Distance &amp; Levensthein Distance in JavaScript  
This is an example of Edit distance calculation and Levenshtein distance calculations.  
I use HTML as a matrix interpretation in the table.  
## Function

Please see the ```src/MinEditDistance.js``` for the function.  
The Following function can be used:

    MED();
    LED();
    backTrace();
    
## Installation
1. Clone repo using Git
``` shell
# clone repository into your dir
git clone https://github.com/faisalsyfl/MinEditDistance.git 
```
2. Double click ```index.html```

## Getting Started
``` js
/* Your first string */
var string1;
/* Your second string */
var string2;

matrixMED = MED(string1,string2);
matrixLED = LED(string1,string2)
console.log(matrixMED);
console.log(matrixLED);

seqOperationMED = backTrace(matrixMED);
seqOperationLED = backTrace(matrixLED);
console.log(seqOperationMED);
console.log(seqOperationLED);

```

## Documentation
![alt text](https://s1.postimg.org/2xeoni799b/image.png "Input")  
![alt text](https://s1.postimg.org/10bktu5mcf/image.png "Matrix & Backtrace")
![alt text](https://s1.postimg.org/1lxzubdftr/image.png "Matrix & Backtrace")


