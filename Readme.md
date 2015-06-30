---
tags: cssi, javascript
level: 1
languages: javascript
---
#Variables and Assignment
The interpreter has been great for doing little calculations, but it doesn't remember values from line to line. To help it remember, we will tell it we're making a variable.

You’re probably familiar with variables from your high school math classes.

We can think of a variable like a bucket. Inside of the bucket we can store data. The bucket has a name we declare, and we assign data(a value) to it using an '=' sign.

Our variable names should be specific and relevant to so that it is easy for other developer to understand what goes inside.

You need to declare variables explicitly in JavaScript with the var keyword like this:
```
>var color = "blue"
```
`var` lets JavaScript know that you've just made a variable!

Try typing your own variable. Give it a value, ask for that value, then change the value and as again, something like this:
```
>var color = "red"
>color
>var color = "green"
>color
```

Don't worry about the "undefined" you get from the "var" lines; the interpreter is just telling you that variable assignment itself doesn't evaluate to anything. It doesn't need to: the point is that the value is remembered for later.

The value returned by the console for the variable changes as we reassign the value of the var. We can change what’s in the bucket by putting something new in, we can change our variable by simply changing the value. That why they are “variables.” They store data, but that data can be reassigned with the = sign.

In mathematics this means equality, but in programming languages it means assignment. We're "assigning" a value to the label, attaching the sticker.)

Try playing some more with variables:
```
> var humanLegs = 2
> var catLegs = 4
> humanLegs
> catLegs + humanLegs
> color + catLegs
```
What happens?
```
> HumanLegs
```
Note that variable names are case-sensitive, which means capital letters matter.

For variable names consisting of multiple words you should use camelCase or snake_case (camelCase is generally what JS developers use by convention and is called that becauseTheLettersMakeHumpsInTheName)

You can make one variable out of one or more other variable values:
```
> var frankenLegs = humanLegs + catLegs
> frankenLegs
```

##Shorthand Operators
Languages often have shortcuts for the most commonly used expressions - we have contractions in english (don't for do not, it's for it is, y'all for you all). In javascript, there are some convenient shortcuts for doing an operation and an assignment at the same time. To increase a variable x by 2, I know that I can use x = x + 2. With the shortcut, it's as easy as x += 2.

Here's a list!
| shortcut | original  |
|----------|-----------|
| x += y   | x = x + y |
| x -= y   | x = x - y |
| x *= y   | x = x * y |
| x *= y   | x = x * y |
| x /= y   | x = x / y |
| x %= y   | x = x % y |
