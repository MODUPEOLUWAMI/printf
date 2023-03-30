PROJECT NAME: 0x11. C - printf

DESCRIPTION: A Group Project
"printf" is the name of one of the main C output functions, and stands for "print formatted". printf format strings arecomplementary to scanf format strings, which provide formatted input .The functions in the printf() family produce output according to a format.

TASKS:
0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
Write a function that produces output according to a format.

Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)
write output to stdout, the standard output stream
format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
-c
-s
-%

1. Education is when you read the fine print. Experience is what you get if you don't
Handle the following conversion specifiers:
-d
-i

2. With a face like mine, I do better in print
3. What one has not experienced, one will never understand in print
Handle the following conversion specifiers:
-u
-o
-x
-X

4. Nothing in fine print is ever good news
Use a local buffer of 1024 chars in order to call write as little as possible.

5. My weakness is wearing too much leopard print
Handle the following custom conversion specifier:
S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value inhexadecimal (upper case - always 2 characters)

6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
Handle the following conversion specifier: p.

7.  The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:
-+
-space
-#
8. Sarcasm is lost in print
Handle the following length modifiers for non-custom conversion specifiers:
-l
-h
Conversion specifiers to handle: d, i, u, o, x, X

9. Print some money and give it to us for the rain forests
Handle the field width for non-custom conversion specifiers.

10.  The negative is the equivalent of the composer's score, and the print the performance
Handle the precision for non-custom conversion specifiers.

11.  It's depressing when you're still around and your albums are out of print
Handle the 0 flag character for non-custom conversion specifiers.

12.  Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
Handle the - flag character for non-custom conversion specifiers.

13.  Print is the sharpest and the strongest weapon of our party
Handle the following custom conversion specifier:
r : prints the reversed string

14. The flood of print has turned reading into a process of gulping rather than savoring
Handle the following custom conversion specifier:
R: prints the rot13'ed string
15. *
All the above options work well together.


STEPS INVOLVED:
1. create Repository: printf
2. invite team mate for collaboration
3. create README.md
4. create main.h file
5. copy the main.c file
6. create the remaining 15 tasks
Note: the 15 tasks should be shared between team mates . mate A can create the first task and mate B can then git pull the task and add or create changes in the task. then mate B should create the second task and the above step can take place.the tasks should be shared between team mates in the ratio 60:40 or 40:60 manner.
7. dont forget to git add and git push to your remote repo after each code has been written in the text editor also run or use betty style in your codes.
8. THE END.
