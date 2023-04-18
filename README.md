## Making a PC

### Part 1 - Create the following classes:
- Create a **PC class** that has-A Case , Motherboard and a Monitor
- Create a **parameterized constructor** for PC containing all of its instance variables/ properties/fields/attributes
- Create a **drawLogo()** method that is private , that accepts no parameters and returns nothing inside the Pc class.
- Inside the drawLogo()method, **invoke/call the drawPixel(x,y,z)** method on the monitor's instancevariable. (Hint: See monitor class)
- Create a public method called **description()** that accepts no parametrs and returns nothing but prints out the description of the case, monitor and motherboard by concatenating them to the message “Welcome to worst buy below is the description of the pc on sale today”
- Make sure all objects can be printed using the **String representation of an object**
- Create a **powerUp()** method that is public and returns nothing but inside the method do the following:
- invoke/call  the **pressPowerButton() method  on theCase** 
- Calls/invokethe **drawLogo()** method then right after that the pressPowerButton method.
- Invoke the loadProgram() method on the motherBoard's instance variable/property after calling the drawLogo method. You are now done with the pressPowerButton.

### Part 2 - Monitor class:
- Create a **Monitor class that has-A** : **Resolution ** modelNumber and manufacturerName as well.(All instance variables)
- Create a method named **drawPixel(int x, int y, String color)** with the following parameters as seen.
- Inside the drawPixel method, simply print **Drawing pixel at " + x + "," + y + " " + " in color "+ color**. (use this code inside the method)
- Ensure that you have a string representation of the object.

### Part 3 - Resolution class:
- Create a Resolution class with these two properties width and height.Private int width; int height;
- Make sure you add all that is necessary, getters, setters etc..
- Ensure that you have a string representation of the object.

### Part 4 - MotherBoard class:
- Create the following instance variables, fields or propertiesprivate String model; String manufacturer, int ramSlots; int cardSlots; String bios;
- Create a **loadProgram()** (method that returns nothing but accepts a parameter named programName)
-  
- Inside the loadProgram method concatenate and print out - "Photoshop is now running..."   Photoshop will be the argument to pass to it when invoked.
- Ensure that you have a string representation of the object.

### Part 5 - Case class:
- Create the following private properties/ivars inside the class:  String model; String manufacturer; String powerSupply; Dimensions dimensions;
- Create a **pressPowerButton()** method that returns nothing but literarily just prints out the text "Power Button Pressed". 

### Part 6 - Dimension class:
- Create the following properties/instance variables as well as getters, constructors...int width; int height; int depth; ensure you have all you need to be able to create a Dimension Object in main when needed. 
- Ensure that you have a string representation of the object.

# Sigh - Time to work inside our main method (PSVM)

### Part 7 - Main class (psvm):
- Create an instance/Object of Type PC
- Call/Invoke the description() method on the pc instance/object
- Invoke the powerUp() method method on the pc object
- Run your program!!!

## Below is a sample of the expected output to help!

```
Welcome to worst buy below is the description of the pc on sale today 
Monitor{resolution=Resolution{width=50, height=50}, modelNumber='HP24m', manufacturerName='HP'} 
Case{model='Windows xp', manufacturer='Microsoft', powerSupply='220 volts', dimensions=Dimensions{width=200, height=200, depth=100}} 
MotherBoard{model='sony23', manufacturer='Sony', ramSlots=2, cardSlots=4, bios='sony-bios'}
power button pressed
Drawing pixel at 10,10  in color Purple
Photoshop is now running....

```

