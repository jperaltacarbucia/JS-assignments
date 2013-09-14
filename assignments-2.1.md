ANSWERS

1. Find at least three different methods getting the date for today, tomorrow 
   and yesterday using the date object.
        a. Date() - Shows todays date
        b.
        c.

2. What does the Math.ceil() built-in function do?  What is the default return 
   value?  What are some other built-in functions that do something similar?
        a.Returns the smallest integer greater than or equal to a number.
        b.

3. What is the Nan type in Javascript and what does it stand for? When would you
   encounter it?
        a. Nan is a property of the global object. It is the return value when a
        math function fails and is not a number.
        b. It stands for Not-A-Number.
        c. when a math function fails and is not a number. (ie. parseInt("I'm 
        not a number, duh.") <-- This is trying to parse an integer, but sadly 
        is not a number, therefore Nan.)

4. How would I find the largest possible value that can be represented in 
   Javascript? What about the smallest?
    a. Values depends on the numbers, therefore the largest possible number 
       would be infinity, so the largest possible value that can be represented 
       in Javascript is infinity and is written just like that. There is also a 
       max value approximated to be 1.79E+308. (But now that I think about it
       values can also be colors? or I'm probably confused.)
    b. 

5. Calculator

<CENTER>
<FORM NAME="Calc">



<TABLE BORDER=4>
<TR>
<TD>
<INPUT TYPE="text"   NAME="Input" Size="16">
<br>
</TD>
</TR>
<TR>
<TD>
<INPUT TYPE="button" NAME="one"   VALUE="  1  " OnClick="Calc.Input.value += '1'">
<INPUT TYPE="button" NAME="two"   VALUE="  2  " OnCLick="Calc.Input.value += '2'">
<INPUT TYPE="button" NAME="three" VALUE="  3  " OnClick="Calc.Input.value += '3'">
<INPUT TYPE="button" NAME="plus"  VALUE="  +  " OnClick="Calc.Input.value += ' + '">
<br>
<INPUT TYPE="button" NAME="four"  VALUE="  4  " OnClick="Calc.Input.value += '4'">
<INPUT TYPE="button" NAME="five"  VALUE="  5  " OnCLick="Calc.Input.value += '5'">
<INPUT TYPE="button" NAME="six"   VALUE="  6  " OnClick="Calc.Input.value += '6'">
<INPUT TYPE="button" NAME="minus" VALUE="  -  " OnClick="Calc.Input.value += ' - '">
<br>
<INPUT TYPE="button" NAME="seven" VALUE="  7  " OnClick="Calc.Input.value += '7'">
<INPUT TYPE="button" NAME="eight" VALUE="  8  " OnCLick="Calc.Input.value += '8'">
<INPUT TYPE="button" NAME="nine"  VALUE="  9  " OnClick="Calc.Input.value += '9'">
<INPUT TYPE="button" NAME="times" VALUE="  x  " OnClick="Calc.Input.value += ' * '">
<br>
<INPUT TYPE="button" NAME="clear" VALUE="  c  " OnClick="Calc.Input.value = ''">
<INPUT TYPE="button" NAME="zero"  VALUE="  0  " OnClick="Calc.Input.value += '0'">
<INPUT TYPE="button" NAME="DoIt"  VALUE="  =  " OnClick="Calc.Input.value = eval(Calc.Input.value)">
<INPUT TYPE="button" NAME="div"   VALUE="  /  " OnClick="Calc.Input.value += ' / '">
<br>
</TD>
</TR>
</TABLE>
</FORM>
</CENTER>