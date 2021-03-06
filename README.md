
#Variables and Assignment
The interpreter has been great for doing little calculations, but it doesn't remember values from line to line. To help it remember, we will tell it we're making a variable.

We can think of a variable like a bucket. Inside of the bucket we can store data. The bucket has a name we declare, and we assign data(a value) to it using an '=' sign.

You need to declare variables explicitly in JavaScript with the var keyword like this:
```
>var students = 30
```
`var` lets JavaScript know that you've just made a variable!

See the value of the variable by calling its name
```
>students
30
```

Variables store data, and that data can be reassigned with the = sign.
```
>var instructors = 4
>instructors
4
>var instructors = 6
>instructors
6
```

An "undefined" msg is the  the interpreter telling you that variable assignment itself doesn't evaluate to anything. 

We can put strings into variables:

```
> var cssi = "Google Computer Science Summer Institute"
> var description = "A program for awesome rising college freshmen"
> cssi
"Google Computer Science Summer Institute"
> description
"A program for awesome rising college freshmen"
```
And we can use the variables in expressions - they act as if the value stored inside them is in the expression instead:
```
> students + instructors
36
> cssi + " - " + description
"Google Computer Science Summer Institute - A program for awesome rising college freshmen"
```
We can assign variables to the results of expressions too:
```
>var humansInRoom= students + instructors
>var info = cssi + " - " + description
>humansInRoom
36
>info
"Google Computer Science Summer Institute - A program for awesome rising college freshmen"
```

Note that variable names are case-sensitive, which means capital letters matter.
```
>info
"Google Computer Science Summer Institute - A program for awesome rising college freshmen"
>Info
ERROR!!
```
JavaScript thinks that 'info' and 'Info' are different things - the capitalized one is not defined!

Our variable names should be specific and relevant to so that it is easy for other developers to understand what goes inside.
```
var x = 30; // pretty unintelligible
var number = 30; // what does the number mean?
var studentCount = 30; // this one is pretty clear!
```
For variable names consisting of multiple words, we can use camelCase or snake_case. Usually, JavaScript developers use camelCase (called camelCase  becauseTheLettersMakeHumpsInTheName).

Consistency in coding style is very important to maintain code readability in large projects. You can read Google's own style guidelines for Javascript and other languages here: http://google.github.io/styleguide/ .




<p data-visibility='hidden'>View <a href='https://learn.co/lessons/cssi-2.2-variables-and-assignment' title='Variables and Assignment'>Variables and Assignment</a> on Learn.co and start learning to code for free.</p>
