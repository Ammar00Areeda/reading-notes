## Control the flow

This is the sequence in which a script is executed by a computer.


Unless the computer encounters (very frequent) structures that modify the control flow, such as conditionals and loops, code is run in sequence from the first line in the file to the final line in the file.



Envisagez un script qui vérifie les données d'un formulaire d'un site online. However, if a necessary field is left blank, the script encourages the user to fill up that field. So that different code executes depending on whether the form is filled out correctly, the script utilizes a conditional structure or if...else.

## JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

syntax

function myFunction(p1, p2) {
  return p1 * p2;   }

  ## Function Return

  When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":