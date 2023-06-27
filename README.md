printf



Description



The printf() function prints formatted text to the console. A custom _printf() function was developed by Nicks and Musa Parsanka for learning purposes. The _printf() function's format string is a text string that tells the function how to format the text. Arguments are placed in the format string using the percentage (%) symbol.

For example, the following format string would print the value of the variable x as an integer:

Code snippet

     "The value of x is %d"

The %d symbol tells the _printf() function to format the argument as an integer. The value of the variable x would be substituted into the format string, and the _printf() function would print the formatted text to the console.



Resources



	.https://www.academia.edu/10297206/Secrets_of_printf_
	.https://intranet.alxswe.com/concepts/111
	.https://intranet.alxswe.com/concepts/130


Authorized functions and macros



	   . write (man 2 write)
	   . malloc (man 3 malloc)
	   . free (man 3 free)
	   . va_start (man 3 va_start)
	   . va_end (man 3 va_end)
	   . write (man 2 write)
	   . va_copy (man 3 va_copy)
	   . va_arg (man 3 va_arg)



Compilation



The code must be compiled this way:

*$ gcc -Wall -Werror -Wextra -pedantic .c

As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)







Authors ©



	. Aziddine
	. omorakwant