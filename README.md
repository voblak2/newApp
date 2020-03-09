# newApp
My first C# app

Lesson 1 Hands-On

Directions
For your Lesson 1 Hands-On, you will be practicing your new C# skills writing variables with data types as well as if statements. In this Hands-On exercise, you will create a program which will test your newly acquired knowledge of C# programming. This Hands-On will be graded, so be sure you complete all three parts listed below. Follow the below steps for setup.

Setup
Open up your command prompt/terminal.
Run the following to navigate to your Desktop
cd desktop
Navigate into the ProgrammingC# folder:
cd ProgrammingC#
Next, the following command is the CLI command to create a new project:
dotnet new console -o lesson1HandsOn
Once the process is complete, navigate into the lesson1HandsOn directory:
cd lesson1HandsOn
Lastly, run the following to open your new project in VS Code:
code .
For this Hands-On, you will be working within the Program.cs file. Good luck!

Part 1
For this Hands-On, you are going to be writing variables and if-else statements to inform the user if they need to wear sunglasses or not.

Create a variable named isSunny with the value of true.
Define this variable with the correct data type.
Hint! What data type is set to either true or false?

Create two new variables:
wear which should be set to the string value "Wear sunglasses!"
dontWear which should be set to the string value "You don't need to wear sunglasses."
Convert the following statements into the necessary C# if-else statements:
If it is sunny outside, print "Wear sunglasses!". If it is anything else, print "You don't need to wear sunglasses."
You must use each of the three variables created.
Hint! Each of the examples within this lesson "print" to the console.

Run this within your integrated terminal. The console output should look like the following:
Wear sunglasses!
Part 2
Create an additional variable named atBeach that is set to true and has the correct data type.
Create two new variables:
sunblock to contain the sentence "Sunblock is a good idea."
noSunblock to contain the sentence "Sunblock isn't needed."
Add another if-else statement that will execute if the variable isSunny is true (you already created that if-else statement in Part 1). If isSunny is false, this new if-else will not be executed. This new if-else statement will check if the variable atBeach is true/false.
If it is true, print "Sunblock is a good idea."
If it is false, print "No need to wear sunblock."
You must use each of the above variables.
Run the program and your console output should look like the following:
Wear sunglasses!
Sunblock is a good idea.
Part 3
Change the value of the isSunny variable to false.
Create three new variables:
goAnyway that is set to true.
going to contain the sentence "Awesome! Glad you don't mind clouds!"
nextTime to contain the sentence "No worries! Hopefully next time we will have some sun!"
Add another if-else statement that will execute if the variable isSunny is false. This new if-else statement should check if the variable goAnyway is true.
If it is true, print "Awesome! Glad you don't mind clouds!"
If it is false, print "No worries! Hopefully next time we will have some sun!"
Use the above variables.
Change the definition of isSunny such that its value is false.
Run the program. You should now see the following:
You don't need to wear sunglasses.
Awesome! Glad you don't mind clouds!