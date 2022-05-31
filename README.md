Regex Date Statement
This Regex Statement will match a 12 hour time string.

Summary
The Regex will have 2 digits for each section, and will end with either AM or PM. This example contains grouping and classing.

(\d{2})\:(\d{2})\:(\d{2})(AM|PM)

Table of Contents
OR Operator
Character Classes
Grouping and Capturing
Regex Components
This expression contains groups matching the hours, minutes and seconds of a 12 hour time string, complete with AM and PM.

OR Operator
Represented in the expression with (AM|PM), the expression is looking for either of those at the end of the string, following the hours, minutes and seconds.

Character Classes
Represented in the expression with /d{2}, the expression is looking for exactly 2 digits to fill in the hours, minutes and seconds. This will precede the (AM|PM).

Grouping and Capturing
Represented in the expression with (/d{2}) and (AM|PM). The first three capture groups are looking for the hours, minutes and seconds. The four capture group is looking for either AM or PM at the end to ensure a proper timestamp syntax.

Author
All your base are belong to us.

I'm a learning Full Stack Developer. Explore my github at this address. https://github.com/The-Coding-Bat
