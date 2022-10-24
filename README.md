## Java I

**Assign 04 - The Clock**

**Date assigned:**

**Program due:**

**Points:**

**This is an individual assignment.**

**Goals:**

1.  Using UML, design the solution to a problem that uses composition and inheritance

2.  Implement the design one class/method at a time

3.  Use basic exception handling for error checking

**The Problem**

Time can be displayed in standard time using a <b>12-hour am-pm clock</b>
or in military time using a <b>24-hour military clock</b>. You are to
implement a clock that is capably of displaying time using either
format. A nice table showing both formats can be found at
<a href="https://www.ontheclock.com/convert-military-24-hour-time.aspx">
Standard vs Military Time</a>

Here is exactly what your program is to output (asterisks and all), and
user input is in **bold**. The clock has run for 4 seconds.

<pre>
Set Clock To S)tandard Time M)ilitary Time: <b>S 00:00:00 am</b>

Standard Time Clock
     00:00:04 am

</pre>

**Error Handling**

1. Make sure the input string can be correctly parsed. If the input
string is incorrect, throw a ParseException with an appropriate
string indicating the error in the string. For example, if the
user enters <b>S 30:00:00 PM</b>, you are to throw an error like
<b>Standard Time Out Of Range</b>. This through all of the possible
errors and provide exceptions for each kind of error.

**Deliverables**

1. Using UMLet, you are to design the necessary classes that handle any 
logic relating to <b>The Clock</b>. A proper design will show each class
necessary to solve the above problem and will also use composition and 
inheritance.

2. Implement your design from 1.

**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**

    a.  You are to click on the Assign03 Link to accept this
        assignment. Once accepted, code up a
        complete solution to the above assignment specification. Your
        complete solution is to be pushed to GitHub no later than the
        date and time specified above for your specific section. I will
        only grade your solution from the proper location on GitHub.

    b.  Pay attention to the example output above. Your program's output
        must look **exactly** like the example output! The spacing and
        newlines in your output must match exactly.

    c.  Make sure that your program compiles and runs correctly with no
        errors and no warnings. If you get any errors, double check that
        you typed everything correctly. Be aware that C++ is
        case-sensitive.

2.  **An electronic copy of your program (punetidAssign03Protein.pdf) is to be emailed to ryandj@pacificu.edu**
