# Lab 1

Include your writeup for the Lab 1 questions here. Use correct
Markdown markup. For more details, start with the article
https://help.github.com/articles/github-flavored-markdown

## Scala Basics: Binding and Scope
1. Q1
	1. Line 3. Because pi is declared in the same scope at line 3. 
	2. Line 1. There is no declaration in the same scope, therefore pi is bound at line 1.
2. Q1
	1. Line 2. Because x is the parameter of method f.
	2. Line 2. There is no declaration in the same scope, therefore it is bound by the parameter of the method.
	3. Line 2. Although there is a declaration of x at line 8, they are not in the same scope. Therefore it is bound at line 2.
	4. Line 1. They are in the same scope.

### Scala Basics: Typing
1.
(b, 1): ((Int, Int), Int) because
	(x, 3): (Int, Int) because
		x: Int
		3: Int
	1: Int

(b, a+2): ((Int, Int), Int) because
	(x, 3): (Int, Int) because
		x: Int
		3: Int
	a+2: Int because
		a: Int
		2: Int
Therefore, the return type should be ((Int, Int), Int)