# General Knowledge Questions:

Please write your answers in the code blocks.

**NOTICE:** Some (but not all) questions may be easier to answer with code or pseudocode. As an example, all of these are an acceptable answer to the question "How do you iterate a variable in PHP?"

```
$number++;
```

```
num = num + 1
```

```
variable "num" now equals "num" + 1
```

-----------------------------------------------------------------------

## Section: PHP

1. How do you get information from a form that is submitted using the "get" method?

```
$_GET['your variable']
```

2. What is the correct way to create a function in PHP?

```
function(){

}
```

3. Name a method to output an array?

```
Print_r();
```

4. Which operator is used to check if two values are equal and of same data type?

```
===
```

5. Which superglobal variable holds information about headers, paths, and script locations?

```
$_SERVER
```

6. Explain how `static function` works in PHP class methods.

```
Although they are in the class, they are not part of the class. You can not use $This in the function.
```


7. What is the commonly used library for database connections?

```
PDO
```

8. What is the commonly used library for making requests?

```
cUrl
```

9. What is PHP function strlen?

```
string length 
```


## Section: SQL

For the below questions, assume you are using this table (named `Persons`):

| Id | FirstName | LastName  |
|----|-----------|-----------|
| 1  | Peter     | Jackson   |
| 2  | Adam      | Savage    |
| 3  | Linus     | Sebastian |
| 4  | Brent     | Spiner    |
| 5  | Doom      | Guy       |

1. How would you select just the first record and only the column `FirstName`?

```
select `FirstName` from Persons
```

2. How would you select all the records where the `FirstName` is "Peter" and the `LastName` is "Jackson"?

```
select * from Persons where `FirstName` = "Peter" and `LastName` = "Jackson"
```

3. How would you select all the records where the `LastName` starts with an "s"?

```
select * from Persons where `LastName` like "s%"
```

4. How would you select all the records where the `FirstName` is alphabetically between "Brent" and "Linus"?

```
select * from Personsn where `FirstName` between ("Brent" and "Linus") order by `FirstName` asc
```

5. How would you insert the name "David Tennant"?

```
insert into Persons (`FirstName`,`LastName`) values ("David", "Tennant")

```

6. How would you change all the records where the `FirstName` is equal to "Peter" into "Samuel"?

```
update Persons
set 'FirstName' = 'Samuel'
from Persons
Where 'FirstName' = 'Peter'
```

7. How would you delete the records where the `LastName` is "Sebastian"?

```
delete from Persons
Where 'LastName' = 'Sebastian'
```

8. How would you get the number of records in the `Persons` table?

```
select count(id) from Persons
```

9. Give an example of how would you join 2 related tables together?

```
select TB1.name,TB2.name from Table1 as TB1
join Table2 as TB2
on TB1.id = TB2.id
```


## Section: Vanilla Javascript

1. How do you create a function in JavaScript?

```
function updateFunction(){

}
```

2. How do you call a function named "myFunction"?

```
myFunction();
```

4. How to write an IF statement for executing some code if "i" is NOT equal to 5?

```
if(i != 5){

}
```

5. How does a WHILE loop start?

```
while(X != 0){

}
```

6. How does a FOR loop start?

```
for(i; i<6;i++){

}
```

7. How do you round the number 7.25, to the nearest integer?

```
math.round()
```

8. What will the following code return: Boolean(10 > 9)
true

## Section: jQuery

1. Can jQuery animate() method can be used to animate ANY CSS property?

```
no
```

2. Which jQuery method is used to hide selected elements?

```
.hide
```

3. Which jQuery method is used to perform an asynchronous HTTP request?

```
.ajax
```

4. Look at the following selector: $("div p"). What does it select?

```
all 'divs' with a 'P' tag
```


## Section: React

1. What is JSX?

```
javascript syntex for react
```

2. What triggers a render cycle?

```
reactDOM.render()
```

3. What is a React Hook?

```
functions that access componets without using classes
```

4. Which method in a React Component should you override to stop the component from updating?

```
shouldComponentUpdate
```

5. Which method in a React Component is called after the component is rendered for the first time?

```
componentDidMount
```

6. What happens when you call setState() inside render() method?

```
error or infinte loop
```

