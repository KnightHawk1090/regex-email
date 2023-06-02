# Regex Email Tutorial

Regular Expression, or as it is more commonly known Regex, is a great tool that is used for extracting specific information from strings that are based on predined patterns. The characters within a regex represent a rule that helps define the desired pattern. Regex is also used to validate input fields such as usernames, passwords, and email addresses.

## Summary
This tutorial will explore the Regex (regular expression) provided below. This particular Regex is designed to search for email addresses:

` /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ `

Each component of this Regex plays a specific role to ensure that the email address matches the desired criteria. Through this tutorial, we will break down each Regex component and describe its purpose. First, let's start with a brief description of literal and meta characters. 

Literal characters are as the name describes. They will literally be what is typed in. An uppercase C will equal and upper case C and a lowercase x would equal a lowercase x. 

Metacharacters are a bit more difficult. They will represent a possible sequence of characters or pattern. 
Some examples of Metacharacters are: 
-```.``` - any character
-```\d``` - any numer
-```*``` - 0 or more
-```.*``` - wildcard

## Table of Contents 
- [User Story](#User-Story)
- [Acceptance Criteria](#Acceptance-Criteria)
- [Anchors](#anchors)
- [Quantifier](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [OR Operator](#or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## User Story 
```
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
```


#### Acceptance Criteria
```
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile
```
