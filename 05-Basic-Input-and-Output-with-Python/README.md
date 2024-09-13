#Basic Input and Output

Print() function sends the output to the Standard Output which is usually the terminal. 
Where it gets interesting is when you redirect outputs to files, printers, websites or anyother source destination you have the desire to sent it to
Print() can take parameters suchs as Object, Sep, End, and File
While Python can change certain objects into string literals it is best practice is to convert the object you want to print into a string literal since the print function doesn't know how to convert everything into a string literal
# Print Parameters
Object - The Thing(s) to be printed
Sep - How to separate in the instance of multiple objects
End - What to print at the end
File - Redirect to a file on the file system

The Input() function collects data from an interactive user. Remember that all data is returned as a string. So if you want it to be a number you'll need to cast it as such.
When casting an input() from an interactive user it is a must to perform error handling. For instance if a user types in their name when you cast a value to an integer the code will error out.
Make sure to provide a prompt to the user as to what to input

Formating your string outputs can be accomplished in several wazys. You have % formating str.format() and F-strings. While you can utilize % of str.formating, in best practices it is best to use F-strings. F-strings is dynamic and makes for good looking good. However it is important to know all outputting formats because you could be working with legacy code as F-strings didn't come out until Python 3.6



