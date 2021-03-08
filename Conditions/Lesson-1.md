Lesson 1: Control Structures
============================
<p align="center">
	<img src="https://media.giphy.com/media/E1Bs4Ml7VJtsY/giphy.gif" alt="bird-branch">
</p>

## TL; DR
Ang **Control Structures** ay feature ng isang programming language which allows the program to perform different process or actions depending on what is needed during the execution of the program. We have two (2) common control structure **if control structure** and **case control structure**.

## Overview
In selection **control structures**, conditional statements are features of a programming language which perform different computations or actions depending on whether a programmer-specified Boolean condition evaluates to true or false. [(source)](https://press.rebus.community/programmingfundamentals/chapter/selection-control-structures/)

## Further chika
This is just a very simple concept so without further ado, bi-basican lang muna natin ang mga bagay bagay. Let's start with the `if` statement.

**IF STATEMENT**

```
	// Here's the very obvious pattern pagdating sa if statements
	// Most of the programming language na may selection control structure
	// ganito ang pattern ng if statement
	
	if <condition>
		<body / block of codes>
	else
		<body / block of codes>
	end
	
	// So kagaya ng sinabi natin kanina, most of the programming language
	// na maaring ma-encounter nyo is ganito ang format/pattern
```

Above is a pseudocode showing an example of an `if` statement. Basically, ang nangyayari dito is, mayroon tayong `condition` which is any expression na nagreresult sa isang `Boolean` value, `true` or `false`. Kung ang `condition` natin ay nagresult as `true`, mag-rarun ang blocks of codes natin na nakapaloob sa `if` statement natin.

```
	// We can also add another branch of the if statement
	
	if <condition>
		<body>
	else if <condition>
		<body>
	else
		<body>
	end
	
	// using an 'else if' statement
```

Above example shows multi-way `if` statement na kung saan maraming paths ang maaring puntahan ng ating program execution based sa ating `condition`. Another important thing to take note is paano nag-rarun ang ating program through this `if` statement.

```
	// our program runs from top to bottom
	// so from top to bottom isa isang ini-evaluate ng ating program
	// ang bawat condition sa ating if statement
	
	if <condition>		<- This condition gets evaluated first, if this results to false it will jump to the next if or else if statement
		<body>
	else if <condition>	<- This condition will be evaluated if the condition above is false
		<body>
	else				<- If none of the condition above is false, the else block will run
		<body>
	end
	
	// from top to bottom, whichever condition results to true first
	// its body will run, then mag end na kaagad yung if statement
```


**SWITCH CASE STATEMENT**

Ang **Switch or Case** statement is another form of selection control structure na maari nating gamitin to introduce choices of paths within our programs. **Switch or Case** statement compare a given value with specified constants and take action according to the first expression to match. [(source)](https://press.rebus.community/programmingfundamentals/chapter/selection-control-structures/)


```
	// Here's the pattern na madalas mong maeencounter
	// in different programming languages
	
	switch <value>
		case CONSTANT_1:
			<body>
			break
		case CONSTANT_2:
			<body>
			break
		case CONSTANT_3:
			<body>
			break
		default:
			<body>
			break
	
	// As we can see almost same mechanics lang din ito compared
	// sa if statement. So which one should you use?
	// For me, kung mas papasimplehin nito ang iyong code at mas mabilis mong mababasa
	// then go for that approach
```

Above is a common form of a **Switch or Case statement** in most programming language. Basically what happens here is meron tayong *value* na icocompare natin sa mga *cases* na nasa loob.

```
	// Parang multiple choice lang to mga lodi
	// let's say meron kang varible na choice
	
	DECLARE string variable choice
	ASSIGN choice = "A"
	
	// then dito sa switch case statement natin
	// gagamitin yung choice mo
	
	switch choice:
		case "A":
			// do something inside this block
			break
		case "B":
			// do something ...
			break
		case "C":
			// do something ...
			break
		default:
			print("None of the above choices")
	
	// now if one of the case constants above nag match
	// yung body or code block ng case na yun ang mag-eexecute
```

Kung mapapansin niyo, every time na may `case` mayroon tayong `break` na statement. Now ang purpose po nyan is kapag nag run ang isa sa mga `case` natin, kapag na-reach na ng compiler or intrepeter ng programming language na gamit natin ang `break` statement, mag-eexit na siya sa `switch` or `case` statement natin at hindi na itutuloy ang pag-read sa next cases. Personally, di ko alam ang technical term para sa ganyang pangyayari lol. pero ang tawag ko dyan is *waterfall*, dahil kapag walang `break` statement mag-rarun ang program natin pababa sa lahat ng case hanggang may makita siyang `break` statement.

```
	switch choice:
		case "A":
			// do something ...
		case "B":
			// do something ...
		case "C":
			// do something ...
		default:  
			// do something
			
		// What will happen here is magrarun lahat ng cases natin until
		// mareach nya ang isang break statement or ang default case natin
```

It's good to practice both of these para mas ma-gets natin kung *kailan* at *saan* natin gagamitin ang `if` or `switch`. *Practice makes a better programmer*.

## Summary para di na sumakit ulo
- **Control Structures** are features of a programming language that allows us to create different branches our paths in our programs based on values or inputs currently set.
- an `if` statement is a control structure where we evaluate a condition or an expression that produces a `Boolean` value; `if true` then do the statement's body/code block, `if false` then proceed to the next statement.
- a `switch` or `case` statement is a control structure where we compare a value to different `constants` that we have set.

<p align="center">
	<img src="https://media.giphy.com/media/l2Je6sbvJEn1W9OWQ/giphy.gif" alt="puzzle">
</p>