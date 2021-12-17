# RegEx-Tutorial

# Email Regex Tutorial

## Regex Description 
Regex stands for regular expression which is a series of characters that specify search pattern or validation criteria for a particular piece of code.  See challenge for more details
Create a repo and add this as my readme

## Table of Contents

- [Anchors](#anchors)
- [Characters](#characters)
- [Capture Group](#capture-group)
- [Bracket Expressions](#bracket-expressions)
- [Quantifiers](#quantifiers)



## Summary
Regex for email is used to check the validity of an email address input in routes and databases. 

An example of a regular expression for email:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Breakdown of email regex components
* Regex email is opened with a forward slash "/" and closed by a forward slash "/".


### Anchors
* There's an up arrow "^" at the start of the expression and it concludes wiht a dollar sign "$" in order to show that the input is a string.  These are examples of anchors:

### Capture Group 
* Opening and closing parentheses "()" indcates the capture group which compartmentalizes each regex section

### Characters
* Must include the "@" character "\." to specify the need for a "." in between a regex section

### Bracket Expressions
* A bracket expression defines what characters can be present in a specific section of an email
* For example, "[a-z0-9_\.-]" this shows the email can contain letters A - Z, numbers 0 through 9, and then _|.- at the end means they can have either of these characters within the username.
* The bracket expression for email server criteria must follow this pattern: "[\da-z\.-]" which means it can contain any digit and any letter in the range "a" to "z" and end with a dot or a dash.
* [a-z\.]{2,6} this bracket expression can contain A through Z and a dot that must be between 2 and 6 characters.

### Quantifiers
* As shown above, "{2,6}" is an example of a quantifier requiring a string of 2 -6 characters

## Author

Sarita Thomas with the support of Top 15 Commonly Used Regex by Niket Pathak (https://digitalfortress.tech/js/top-15-commonly-used-regex/)

- [Link to Github](https://github.com/yourgithubname)
- [Link to LinkedIn](https://www.linkedin.com/in/yourlinkedinname)