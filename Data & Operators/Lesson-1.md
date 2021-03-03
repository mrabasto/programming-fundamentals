Lesson 1: Constants and Variables:
===================================
<p align="center">
	<img src="https://media.giphy.com/media/3oEdvcXYvGxhkOZD3O/giphy.gif" alt="boxes">
</p>


## TL; DR
'pag sinabing **Constant** = hindi nagbabago ang value, 'pag **Variable** naman = maaring magbago or pa-bago bago, kagaya ng mahal mo. Chour!

## Overview
A **constant** is a value that cannot be altered by the program during normal execution, i.e., the value is constant. When associated with an identifier, a constant is said to be *“named,”* although the terms *“constant”* and *“named constant”* are often used interchangeably. This is contrasted with a **variable**, which is an identifier with a value that can be changed during normal execution. [(*source*)](https://press.rebus.community/programmingfundamentals/chapter/constants-and-variables/ "Constants & Variables")


## Further chika

Medyo kumplikado ba bes? Kalmahin mo muna sarili mo dahil madali lang to hehe xd.

Bago ang lahat, may tinatawag tayo na **literal constant** or value na na inaaccept, itinatype, inilalagay mo sa iyong program whenever it is needed. Examples:

	'A'	<- Isang letter A, sa alpabetong ingles
	21	<- Number, maaring edad ng crush mo, or monthsary nyo ng ex mo. oof.
	75.6	<- Number na may decimal, grade ko sa math noong elementary hayst
	"Hi pwede mag hello?"	<- Sentence na sinend mo kay crush tapos binlock ka HAHAHA UMAY
	false	<- Boolean value na true or false, more on this in later lessons
	null	<- null value, more of on this in later lessons

Above where examples of different values na maaring kailanganin ng program natin, and ang tawag sa kanila ay **literal constants** , or just a **literals**, or most of the time **values** lang. For now, tawagin muna natin silang **items** in order for the next example to make sense.

**Fact: Computers are dumb machines.**

That's right, imbento ko lang yang fact na yan. lol. Pero in reality may katotohanan rin naman yan. When we make programs and write codes, we are essentially **writing a list of instructions** for the computer to follow, similar to cooking recipes where we list down all ingredients and steps on how to produce a meal.

Sa isang recipe, mayroong **1. Ingredients 2. Cooking steps/directions**.

For now we will look at the Ingredients, gaya ng dineclare natin kanina Computers are dumb. Dumb enough na kahit sabihin mong may binili kang ingredient, hindi niya automatic na malalaman kung **saan mo ito inilagay**. This is where **constants or variables** comes into play.

> A constant is a data item whose value cannot change, a variable is the opposite of it; a data item whose value can or may change.

Imagine for a second, na ang **constant** and **variable** ay special container/box na pwede mong lagyan ng value. Let's say you have a variable named *Vegetable*, this means maari mong lagyan itong ng *values* na gusto mo, para kapag kinailangan mo, alam na ni computer kung saan nakalagay ang *ingredient* (value) na kailangan mo.

Example pseudocode 1.1:

	DECLARE variable vegetable;
	ASSIGN vegetable = 'kangkong'

Sa example natin sa itaas, nag-declare tayo ng isang *variable* or gumawa ng isang lalagyan na may pangalang `vegetable` at iniligay dito ang *value* or *item* na `'kangkong'`. Because of this we already have a proper way to store values na maari nating magamit sa ating program. ***Think of the process above as writing down the ingredients, then telling the computer where it is currently located***.

Example pseudocode 1.2:

	// Writing down the ingredients
	
	DECLARE variable vegetable;
	ASSIGN vegetable = 'kangkong'
	
	
	// Doing something with the ingredients
	
	prepare(vegetable)	<- a Function, or an action na ginawa natin. More on this in later lessons.
	cook(vegetable)	<- another Function, basically ang ibig sabihin lang nito is marami tayo pwedeng gawin values natin na nakalagay sa variable and/or constant.

In our above example na-introduce tayo sa medyo advance but simple concept, `Function`. Basically set of instructions lang yan or action na pwede mong gawin, for example: `maligo(), kumain(ulam), magchatKayCrush(crushMo)`. Ipinakita lang natin dito na **na kapag nasa proper lalagyan ang value natin, madali natin itong maa-access**. Consider the example below:

Example pseudocode 1.3:

	// Writing down the ingredients
	
	'kangkong'	<- ligaw na value dahil walang lalagyan
	
	
	// Doing something with the ingredients
	
	prepare(vegetable)	<- Error, dahil hindi ka gumawa ng lalagyanan na may pangalang 'vegetable'
	cook(vegetable)	<- Error, hindi alam ni computer na may 'vegetable' na lalagyan dahil hindi mo naman sinabi (declare) sa kanya

Another important thing to remember, **Constants are forever**, and **Variables changes**. Ibig sabihin lang nito, pag na-declare mo na ang value ng isang constant, 'di mo na ito maaaring baguhin. The opposite of a variable, once declared, maari mo parin  baguhin ang value nito whenever you need it to be.

Example pseudocode 1.4:

	DECLARE const PI
	ASSIGN PI = 3.14
	
	DECLARE variable color
	ASSIGN color = 'red'
	
	ASSIGN PI = 1234		<- Error, dahil constant ito, hindi na ito maaring baguhin
	ASSIGN color = 'blue'	<- Good, dahil ito ay variable, maari itong baguhin
	

So which one is better? It really depends kung anong kailangan ng program mo. Variables offer flexibility, while Constants give assurance na same parin ang value gaya ng iniisip mo.

## Summary para di na sumakit ulo mo
So ayun na nga po ano, tapos na ang una nating lesson at ito ang mga nalaman natin:

- Mayroon tayong tinatawag na **literal constants** or **literals** or values na ginagamit ng ating program/application in order to produce meaningful result e.g credit card number, a letter, a sentence, name ng crush mo, number ng utang mo. etc.
- In order for our computers to know where these values are currently located, mayroon naman tayong tinatawag **constants** and **variables** na kung saan pwede nating ilagay ang *items* or values natin.
- **Ang isang Constant, once declared, ay forever at hindi nagbabago, or hindi maaring baguhin. Parang love ni Lord sa'yo <3.**
- **Ang isang Variable naman ay maaring palitan ang laman at magbago ang value.**


<p align="center">
	<img src="https://media.giphy.com/media/l41lUjUgLLwWrz20w/giphy.gif" alt="ok">
</p>
