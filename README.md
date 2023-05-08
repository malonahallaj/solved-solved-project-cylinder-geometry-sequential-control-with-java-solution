Download Link: https://assignmentchef.com/product/solved-solved-project-cylinder-geometry-sequential-control-with-java-solution
<br>
Objective To type a simple Java program, execute ( run ) the program for some particular values, observe the output and then modify the program.

PROJECT DESCRIPTIONType, compile and run the simple Java program that is shown within Figure 1 , which follows. Then compile and run your program, observe the output and then modify the program.

Information About This Project

For this course you can use Eclipse which is an application development environment or ( IDE ) which include a text editor that you can use to write, compile and execute source code written in Java.

Business application software development often involves creating programs involving geometry. Such programs can be utilized by architects and other professionals.

This project has you create and modify a program that computes the volume and surface area of a right circular cylinder given the height of the cylinder and its base radius.

The formulas for these computations are:

Volume V of a Right Circular Cylinder

V = π r 2 h ( with π ≈ 3.1416 , h is the height and r is the base radius )

Surface Area S of a Right Circular Cylinder

S = 2 π r h + 2 π r 2 ( with π ≈ 3.1416 , h is the height and r is the base radius )

The Input, Process and Output ( IPOS ) requirements of this project are:

Input the user name, the cylinder height and the cylinder base radius

Process the volume of the cylinder and the surface area of the cylinder

Output the user name, the volume of the cylinder, computed in cubic length units and the surface area of the cylinder, computed in square length units

The course code for the volume program is given and you will modify it to include the surface area.

Steps To Complete This Project

STEP 1 Open Eclipse, JCreator or Similar Java Development Environment

Open Eclipse or similar Java text editor. Here are the steps to create a Java project for this assignment using Eclipse for Windows.

Using Eclipse

From the Eclipse main menu, click File , point to New and point to and click on Java Project . When the New Java Project dialog box opens, select and fill the settings as follows:

Set the project name : Lab 00

Set the workspace location : ( use the default location )

PROJECT Introduction to the Java Programming Language

Click Finish to close the New Java Project dialog box.

Now ensure that the Eclipse Project Explorer window is open by selecting the main menu item Window , point to Show View and click Project Explorer .

Navigate to the Project Explorer, as shown below.

Double – click the project name ( Lab 00 ) to reveal the src ( source ) folder.

Right – click the src folder and select New from the menu and point to and click on Class . When the New Java Class dialog box opens, name the source file as: Cylinder

Into the Code window, shown below, copy the program code shown in Figure 1 , which follows, exactly as it appears, except substitute your own name in place of Sammy Student. Notice that the class name in the source code must match the file Java name.

PROJECT Introduction to the Java Programming Language

Figure 1 Source Code for the Volume Program

/*

Program to calculate the volume of a right circularcylinder.

Programmer: Sammy Student, File Name: Cylinder.java

*/

// package for Scanner class objects

import java.util.Scanner;

public class Cylinder

{

public static void main(String args[])

{

// introduce a Scanner class object

Scanner sc = new Scanner(System.in);

// declare and initialize the variables

double height = 0, radius = 0, volume = 0;

String strName = “”;

// greet the program user

System.out.println(“Welcome to the Volume Program!”);

// prompt user for their name

System.out.println(“please enter your name”);

// read the user name

strName = sc.nextLine();

//display the name back to the user

System.out.println(“hello ” + strName);

// input: assign values to the variables

System.out.print(“Please enter the radius. “);

radius = sc.nextDouble();

System.out.print(“Please enter the height. “);

height = sc.nextDouble();

// process: compute the required quantity

volume = 3.1416 * radius * radius * height;

// output: display the output to the user

System.out.print(“The volume of the cylinder is: “);

System.out.print(volume);

System.out.println(” cubic length units “);

// dismiss the Scanner class object

sc.close();

}

}

PROJECT Introduction to the Java Programming Language

STEP 2 Build, Compile and Run the Program

From the Eclipse Project menu, ensure that the option Build Automatically is selected. This will indicate that Eclipse will automatically build your project when you run it.

Now select Run on the menu bar, point to Run As and then point to and click

on Java Application .

If you do not have any errors, proceed to the next step, otherwise read the error messages and make any necessary corrections by comparing your screen code to

the original code shown within Figure 1 . Then run your program again.

STEP 3 Test the Program

Once you have successfully compiled your program, enter the following information, when prompted, into the output Console window of Eclipse.

Name of Program User : ( enter your own name )

The Base Radius : 2.0

The Cylinder Height : 10.0

STEP 4 Verify Your Output

When you enter the above information the Console window should show your program output, similar to the following screen snapshot.

Your program has just computed the volume of a right circular cylinder whose base radius is 2.0 and whose height is 10.0 . ( Note: the volume of a cylinder is the product of p times the base radius squared times the height, where p is approximated as 3.1416 )

PROJECT Introduction to the Java Programming Language

STEP 5 Modify Your Program

Close the console output screen to return to the Eclipse Code window. Within the Code window, modify your original program code such that the program will calculate the surface area of the cylinder in addition to the volume of the cylinder.

To modify your program, first change your program comment statement to indicate that your program will also compute the surface area of the cylinder, i.e. use:

/*

Program to calculate the volume and surface area of aright circular cylinder.

Programmer: Sammy Student, File Name: Cylinder.java

*/

Next, modify your variable declaration statement to include any necessary newly required variables.

double area = 0, height = 0, radius = 0, volume = 0;

Also, modify the process proportion of your program by locating the following line of code

// process: compute the required quantity

volume = 3.1416 * radius * radius * height;

and directly below the above line, assign variable area an expression that will compute the surface area of the cylinder according to the formula listed previously.

Finally, locate your output statement block, shown below.

// output: display the output to the user

System.out.print(“The volume of the cylinder is: “);

System.out.print(volume);

System.out.println(” cubic length units “);

Copy the above code segment and paste it directly blow this code block.

Then modify this new output block segment to display the information regarding the output of the surface area of the cylinder.

STEP 6 Re – Compile and Run Your Program

Next re – compile your program by repeating the steps from STEP 2 .

If your program has compiled without syntax errors, proceed to the next step, otherwise scroll through the error window to view any error messages. Make any necessary corrections. Then recompile your program.

PROJECT Introduction to the Java Programming Language

The program run, with the previous sample data, for your modified program should generate an output as shown in the screen snapshot given below.

STEP 7 Verify the Program’s Numerical AccuracyTo verify your program’s output correctness you can open MS Excel for Windows and construct a simple worksheet, such as that given below, that will verify the output computations for your sample program run.Your program’s values may differ slightly from the above worksheet since it uses the Excel intrinsic PI() function instead of our program’s 3.1416 approximation.

STEP 8 Simulate a submission of your Project

Once you have determined that your modified program is correctly computing the volume and surface area of a given right circular cylinder, complete the submission process as follows:

PROJECT Introduction to the Java Programming Language

Open MS Word and type a heading for a new document that includes your full name, course number, lab number and date.

Within the document label and paste your completed program code that you can copy from your Eclipse file.

After you paste your source code, paste a snapshot of your program’s output showing the required computations. Label the snapshot.

You can use the Windows Snipping Tool, which is part of the Windows Accessories Group, to capture your Eclipse Console window.

Your score for each lab project when it will actually count, will generally be based upon the following factors: output correctness, content, organization, style and creativity.

Starting with Lab 1 you will submit your MS Word document similarly to how you worked this sample lab to the appropriate area on Blackboard.