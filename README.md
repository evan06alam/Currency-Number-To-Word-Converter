# Currency-Number-To-Word-Converter
A very simple yet useful helper class for PHP Currency Number to Word Converter

# Features
Support any number<br/>
Support decimal number

# Install
Step 1: Download this library file form [Link](https://github.com/evan06alam/Currency-Number-To-Word-Converter/archive/master.zip)<br/>
Step 2: Extract from Zip Folder.<br/>
Step 3: Copy lib folder and paste it into your project directory<br/>

# Usage
Use this PHP code 
```
<?php 
require_once('{your parent Directory}/lib/class.numberToWord.php');
?>
```
Then Use this PHP Code as following with your parameter.

```
$mynumber=398;
$currencyName='dollar';
$decimalName='cent';
new NumberToWord($mynumber, $currencyName, $decimalName);
```

# Feedback
All bugs, feature requests, pull requests, feedback, etc., are welcome. E-mail me at evanpab@gmail.com

# Credits
Copyright (c) 2018 - Programmed by Evan Alam. [Facebook](https://www.facebook.com/evan06alam)

# License
Released under the MIT License. See [LICENSE file](https://github.com/evan06alam/Currency-Number-To-Word-Converter/blob/master/LICENSE).
