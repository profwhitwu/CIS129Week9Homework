# Week 9 Homework: Objects and Classes

### NOTE: This homework does not have any unit tests, and is setup to run as a console app.  Be sure to run your app prior to submission to ensure your code is working as expected.

1. Create a new class (in a separate file) called Car.  Make this class publically accessible.

2. Define the following fields for your Car class.  Pick an appropriate data type for each field and make them private.
    - Make
    - Model
    - Year
    - Color
    - IsSedan
    - IsAutomatic

3. Create a constructor that assigns values to all fields defined above.  You should be able provide a value for each field upon initialization.  

4. Create a constructor that only defines the make, model, and year.  You should be able to provide a value for each of these fields upon initialization. 

5. Create a public method, called `Honk`, that prints "Honk Honk" to the screen.

6. Create a private method, called `IsValidDirection`, that takes a direction as an argument and verifies that it is either "left" or "right".  If a valid direction is given, return true.  Otherwise, return false.

7. Create a public method, called `Turning`, that takes a direction as an argument. Call your `IsValidDirection` method here to verify that the direction provided is valid. If so, print "Turing --directionHere--" to the console.  Otherwise print "invalid direction" to the console. 

8. In your `Program.cs` file, create 5 different (3 objects using the constructor from question 3, and 2 objects using the constructor from question 4) car objects.  Each object should do the following:
    - Turn left
    - Turn right
    - Honk
    - Attempt to turn in an invalid direction (i.e. not left or right)

9. In a separate file, create a static class, called `DayOfWeekHelper.cs`.

10. In `DayOfWeekHelper.cs`, create a static method, called `PrintDayOfWeek`. This method will take a DateTime object as an argument.  Extract the day of week NAME  (not number) from the DateTime object and print it to the console.  This will likely require some Googling on your part, and there is a MS C# Doc our there that shows you how to do this.    

11. In your `Program.cs` file, call your `PrintDayOfWeek` method and provide it with a valid DateTime object.  
