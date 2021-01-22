# Make decisions

**A decesion-making contructor evaluates a condition before the instructions are executed**

There are various types of decision making in Typescript

1. if statement
2. if-else statement
3. if-else-if lader

## if

**A 'if' statement consists of a Boolean expression followed by one or more statements**

It is used to decide whether a certain statement or block of statements will be executed  or not

### Syntax
if(condition)
{
    
    // Set of statement which has
    // to be executed if condition
    // is satisfied

}
## if else
**An if else condition includes two block -if block and an else block is executed**
### Syntax 
`if(conditon)`
`{` 
 
 // code to be executed

`}else{`
    
    // code to be executed
`}`

## if-else-if
**It ladder is usefull to test multiple conditions.**

**When the condition gets true, it execute the associated statement, adn the res of the condition is bypassed. If it does not find any condition true, it returns the final else statement**

The else if statement can be used after the if statement.

The if..else if statement can have one or more else if branches buy only one else branch

### Syntax
if(boolean_expression1){
    
    //statements if the expression1 evaluestes to

true

}

else if(boolean_expression2)
{
    //statements if the expression2 evaluestes to
true

}

else{
    
    //statements if theexpression1 evaluestes to
false
}