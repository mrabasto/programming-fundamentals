Lesson 2: Identifier Names
==========================
<p align="center">
	<img src="https://media.giphy.com/media/9PqOegBqgBnMHvERV3/giphy.gif" alt="name-tag">
</p>


## TL; DR
**Identifier Names** in programming were descriptive names given to items or values to make the code more meaningful to us programmers. Similar to how *label* works. Kaya bago ka magselos, check mo muna kung may **Identifier Name** kayo. (gets mo? Identifier Name ta's Label? k bye.).

## Overview
Within programming a variety of items are given descriptive names to make the code more meaningful to us as humans. These names are called **“Identifier Names”**. Constants, variables, type definitions, functions, etc. when declared or defined are identified by a name. These names follow a set of rules that are imposed by:

1. the language’s technical limitations
2. good programming practices
3. common industry standards for the language

[(source)](https://press.rebus.community/programmingfundamentals/chapter/identifier-names/)

## Further chika
There's not much to say about this topic because it's very basic. But still it's important to know how can we name our values properly we our code will become more meaningful to us, and also future developers that will read our code.

**Mga bagay na dapat tandaan:**

- May iba't ibang set of rules ng allowable characters ang different programming language na pwede natin gamitin sa pagbibigay ng identifier names:

```
// Sa programming language na PHP, required na may dollar sign ($) sa unahan
// ng isang identifier name:

	$myName = 'Mathew Rabasto';

// Sa Javascript naman, hindi pwede mag-start sa numeric value ang identifier name:
	var 123myVariable = "something";	<- Error
	var myVariable123 = "something";	<- Ok.
	
// Marami pang naming rules ang meron sa iba't ibang language, so if you're learning
// a new programming language, always check these stuff
```

- May mga tinatawag na **reserved words** sa mga programming languages na di mo pwede gamitin as identifier name, dahil magko-cause ito ng error. **Note:** You can easily Google kung anong reserved words or keywords ang mayroon ang language na ginagamit mo. e.g. PHP reserved words/keywords, Javascript reserverd words/keywords. etc.

**Good Naming Techniques**:

Sundan mo lang ang mga to at magiging naming ninja ka in no time:

- Use **meaningful, concise, and easy to remember** names.

```
	// Make it short and simple
	// Pseudocode:
	
	// Avoid!
	DECLARE variable i	<- Hmmm, what does 'i' even mean??
	DECLARE variable thatVariable	<- What is 'that'??
	DECLARE variable x	<- If this is a math equation, this will more useful
	
	// Do!
	DECLARE variable firstName		<- very straightforward
	DECLARE variable userCreditCard	<- meaningful, already tells us what this is
	DECLARE variable productBrand	<- another concise, easy to remember name
```

- Be **case consistent**. There are different types of casing standards:
	+ camelCase -- each word is capitalized except first word, with no intervening spaces
	
	```
		firstName
		lastName
		userCreditCard
		employeeId
		studentIdNumber
	```
	+ PascalCase -- each word capitalized including the first word, with no intervening spaces
	
	```
		SecretFormula
		IsBlockedByCrush
		SadboiNgPinas
		CovidVaccineBrand
	```
	+ snake_case -- each word is lowercase with underscores separating words
	
	```
		movie_title
		last_name
		utang_ng_kaklase				
	```
	+ kebab-case -- each word is lowercase with dashes separating words

	```
		hak-dog
		hacker-man
		password-ng-jowa-ko
		wala-akong-jowa 
	```
	
This conventions depends on which language you are using, does not really affect the performance of your program or application but it does affect the readability of your code. C++, Java, Javascript typically uses camelCase, with PascalCase reserved for libraries and classes, while Python on the otherhand uses snake_case for most identifiers. In addition, following rules may apply:

- Do not start with an underscore (most of the time used in technical programming)
- CONSTANTS IN UPPER CASE (often UPPER\_SNAKE\_CASE)

Most of the time these rules are decided by the industry, kung saan ka currently nagtatrabaho, or those who have influence in the programming languages that we are using.

## Summary para di na sumakit ulo mo
Today we learned:

- **Meaningful, concise and easy to remember** names ang dapat natin ipangalan sa mga values natin when declaring variables or constants
- There were **reserved words** in different programming languages na hindi natin maaring gamitin when creating identifier names
- Mahirap ang walang label. xd.

<p align="center">
	<img src="https://media.giphy.com/media/VbnUQpnihPSIgIXuZv/giphy-downsized.gif" alt="mad-cat">
</p>
