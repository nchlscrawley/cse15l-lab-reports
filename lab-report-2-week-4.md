# *Lab Report 2 - Week 4*
**Written by Nicholas Crawley**

## Code Change 1
* *Code Change Diff*
![Image](lab-3-part-1-1.png)
* [*Test File Link*](https://nchlscrawley.github.io/cse15l-lab-reports/test-file2.html)
* *Symptom*
![Image](lab-3-part-1-2.png)
* This program is intended to print links, not files with image references. The new code has it looking for an exclamation point at the beginning of the line and displays an error message.

## Code Change 2
* *Code Change Diff*
![Image](lab-3-part-2-1.png)
* [*Test File Link*](https://nchlscrawley.github.io/cse15l-lab-reports/test-file3.html)
* *Symptom*
![Image](lab-3-part-2-2.png)
* The link in the test file has a closing parenthesis in an unexpected location, resulting in memory running out. The new code looks for a closed parenthesis at the end of the line, then prints the link.

## Code Change 3
* *Code Change Diff*
![Image](lab-3-part-3-1.png)
* [*Test File Link*](https://nchlscrawley.github.io/cse15l-lab-reports/test-file4.html)
* *Symptom*
![Image](lab-3-part-3-2.png)
* When encountering nothing between the parentheses, the program displays nothing between the brackets. The new code looks for something between the parentheses. If there is nothing, an error message is printed.
