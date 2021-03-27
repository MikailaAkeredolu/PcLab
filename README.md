# Assesmble a PC system (UML required)

 - Before you start coding - Create your UML first. Don't forget that a UML is required !!!

### Part 1 - Create the following classes:
- Create a PC class that HAS a Case , Motherboard and a Monitor
- Create a **parameterized constructor** for PC containing all of its instance variables
- Create a **drawLogo()** method that is private , that takes and returns nothing butinside the method,**invokes/calls the drawPixel(x,y,z)** method on the monitor instancevariable in the PC class
- Create a public method called **description()** that takes and returns nothing butprints out the description of the case, monitor and motherboard but starting with themessage “Welcome to worst buy below is the description of the pc on sale today”

- Make sure all objects can be printed using the **String representation of an object**
- Create a **powerUp()** method that is public and returns nothing but inside the methodinvoke/call  the **pressPowerButton() method  on theCase** and after that it calls/invokethe **drawLogo()** method then right after that it invokes the​ loadProgram() method on themotherBoard ​ivar

### Part 2 - Monitor class:
- Create a **Monitor class that HAS** a **Resolution ** and consist of a model andmanufacturer as well.(All instance variables)
- Create a **void drawPixel(int x, int y, String color)** with the followingparameters and simply **print out "Drawing pixel at " + x + "," + y + " " + " in color "+ color**. (use this code inside the method)

### Part 3 - Resolution class:
- Create a Resolution class with these two properties width and height.Private int width; int height;
Make sure you add all that is necessary, getters, settres etc..

### Part 4 - MotherBoard class:
- Create the following instance variables, fields or propertiesprivate String model; String manufacturer, int ramSlots; int cardSlots; String bios;Create a loadProgram*( method that returns nothing and accepts a parameter calledprogramName as an argument. Inside the method just print out - programName is nowrunning by using the programName argument passed to it

### Part 5 - Case class:
- Create the following private properties/ivars as well as getters  String model; String manufacturer; String powerSupply; Dimensions dimensions;
- Create a **pressPowerButton()** method that returns nothing but prints out the text "PowerButton Pressed

### Part 6 - Dimension class:
- Create the following properties/instance variables as well as getters, constructors...int width; int height; int depth;

### Part 6 - Main class:
- Create an instance/Object of Type PC
- Call the description() method on the pc object3 
- Invoke the powerUp() method method on the pc object

