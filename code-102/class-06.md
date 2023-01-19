# JavaScript Introduction Notes  

[JS Introductory Paragraph](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  

[JS Intro and Examples](https://code-maven.com/introduction-to-javascript)  

## 4 Ways to Declare a JavaScript Variable  

* Using var  

* Using let  

* Using const  

* Using nothing  

## Variables

> Variables are declared using the words listed above.  

An example of a variable would be

> var x = 5;
> var y = 6;
> var z = x + y;

To use JavaScript in older browsers, use "var", const and let were added in 2015 so may not work.  

If you want a general rule: always declare variables with const.

If you think the value of the variable can change, use let.

In this example, price1, price2, and total, are variables:

> const price1 = 5;
> const price2 = 6;
> let total = price1 + price2;  

The two variables price1 and price2 are declared with the const keyword.

These are constant values and cannot be changed.

The variable total is declared with the let keyword.

This is a value that can be changed.  

Variables are containers for storing values.

### JavaScript Identifiers  

**All JavaScript variables must be identified with unique names.**

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

> * Names can contain letters, digits, underscores, and dollar signs.
> * Names must begin with a letter.
> * Names can also begin with $ and _ (but we will not use it in this tutorial).
> * Names are case sensitive (y and Y are different variables).
> * Reserved words (like JavaScript keywords) cannot be used as names.  

**In JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.**

This is different from algebra. The following does not make sense in algebra:

**x = x + 5**
In JavaScript, however, it makes perfect sense: it assigns the value of x + 5 to x.

(It calculates the value of x + 5 and puts the result into x. The value of x is incremented by 5.)

**The "equal to" operator is written like == in JavaScript.**

### Data Types  

> JavaScript variables can hold numbers like 100 and text values like "John Doe".
>
> In programming, text values are called text strings.
>
> JavaScript can handle many types of data, but for now, just think of numbers and strings.
>
> Strings are written inside double or single quotes. Numbers are written without quotes.
>
> If you put a number in quotes, it will be treated as a text string.  

**Example**
const pi = 3.14;
let person = "John Doe";
let answer = 'Yes I am!';  

**Creating a variable in JavaScript is called "declaring" a variable.**

You declare a JavaScript variable with the var or the let keyword:

var carName;
or:
let carName;  

**After the declaration, the variable has no value (technically it is undefined).**

To assign a value to the variable, use the equal sign:

carName = "Volvo";
You can also assign a value to the variable when you declare it:

let carName = "Volvo";
In the example below, we create a variable called carName and assign the value "Volvo" to it.

Then we "output" the value inside an HTML paragraph with id="demo":

Example
<p id="demo"></p>

<script>
let carName = "Volvo";
document.getElementById("demo").innerHTML = carName;
</script>  

[JavaScript Variable Notes Link](https://www.w3schools.com/js/js_variables.asp) 