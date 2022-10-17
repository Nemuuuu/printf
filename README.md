## The first Team project given by ALX SE Program
## Project Title
Create your own Printf
## Description
This code contains manual _printf fucnction which performs like printf available in stdio.h and which writes output to stdout. This is done by collaboration between Neima Nesru and Akrem Beker who are Software Engineering students studying at ALX SE School.
What you would learn from this project:

	The use git in a team setting

	Applying variadic functions to big projects

	The complexities of printf

	Managing a lot of flies and finding a good workflow
## Prototype
int _printf(const char *format, ...);
## Tasks
0. write output to stdout, the standard output stream
format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
	c
	s
	%
1. Handle the following conversion specifiers:
	d
	i
2. Handle the following custom conversion specifiers:
	b: the unsigned int argument is converted to binary
3. Handle the following conversion specifiers:
	u
	o
	x
	X
4. Use a local buffer of 1024 chars in order to call write as little as possible.
5. Handle the following custom conversion specifier:
	S : prints the string.
6. Handle the following conversion specifier: p.
7. Handle the following flag characters for non-custom conversion specifiers:
	+
	space
	#
8. Handle the following length modifiers for non-custom conversion specifiers:
	l
	h
	Conversion specifiers to handle: d, i, u, o, x, X
9. Handle the field width for non-custom conversion specifiers.
10. Handle the precision for non-custom conversion specifiers.
11. Handle the 0 flag character for non-custom conversion specifiers.
12. Handle the - flag character for non-custom conversion specifiers.
13. Handle the following custom conversion specifier:
	r : prints the reversed string
14. Handle the following custom conversion specifier:
	R: prints the rot13'ed string
15. All the above options work well together.
## Acknowledgement
Special thanks to Denis Ritch, inventor of c and founders of ALX SE program who gave us this golden opportunity to challenge our mind.
## Authors
Neima Nesru neimanesru34@gmail.com

Akrem Beker akremmuktar332@gmail.com

