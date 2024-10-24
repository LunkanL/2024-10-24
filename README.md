# 2024-10-24
## Variables
`Var`

### const

`const` is also a keyword for creating variables. It stands for 'constant' which means it is supposed to be constant. It means we shouldn't change this variable after it has been created.

```js
const age = 39;
console.log(age)

age = 45;
```
### let
`let` This is the last keyword we can use to create variables. It is very similar to `const` but we are allowed to re-assign a `let`-variable.

```js
let streetName = "Televägen";
streetName = "Drottninggatan";
```
This is fine, but we can also change the data type if we would like to.

```js
let id = "jaskjasf";
id = 853208050;
```
[Back to top](#2024-10-24)

---

## If Statements

An if statement is just a way for the application to decide which way to go. Simply put. Depending on certain conditions that we define, the application can do one thing or the other. Usually an appliccation consist of hundreds of condition in different combinations, so it's an essential tool to know about when coding.

What a statement means is also a good thing to know. It just means a set of instructions that the computer will follow.


### Basic if-syntax

```js
if (condition) {
    //code to be executed if the condition is true.
}
```
`if` is the keyword that tells the compiler than an if check is declared. The condition is a value that can be evaluated to either `true` or `false`. The code block contains the code that is executed when the condition is true.

```js
const age = 20;


if (age > 18) {
    console.log ("You are an adult.")
}
```

If you want to 


### Comparison operators

To evaluate our conditions we need to use what is called a comparison operator.

`>, <` - Greater then, or less then

`=>, <=` - Greater then or equal, or less then or equal.

`==` - equal (not strict)

`===` - equal (strict)

`!=` - not equal (not strict)

`!==` - not equal (and strict)



### Logical operators

`||` - or
 
`&&`- and

`!` - not



[Back to top](#2024-10-24)
