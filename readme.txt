Bounded Queue Implementation (SP2) version 1.0 09/09/2018


---------- AUTHORS ----------
Prateek Sarna - pxs180012
Nirbhay Sibal - nxs180002


---------- PREREQUISITES ----------
Java Development Kit (This program was compiled using jdk 8)
A Java IDE such as Eclipse (Optional)
Java Environment Variables should be set correctly (For Command Line)


---------- FILES INCLUDED ----------
BoundedQueue.java


---------- RUN IN AN IDE ----------
To run the program in an IDE such as Eclipse, simply unzip the folder and import the files into the IDE.


---------- COMPILE AND RUN ON THE COMMAND LINE ----------
Since we have our class inside a package, the scope of this class is inside the package. Hence, navigate to the directory where the package directory (pxs180012) is present. Run the following command on Command Line to compile the java files-
	javac pxs180012/BoundedQueue.java
			or 
	javac pxs180012/*.java

The program should compile successfully. You can then run the program using the command - 

	java pxs180012.BoundedQueue


----------NAVIGATION INSIDE THE PROGRAM ----------
Size can be passed as a parameter when you run the program to specify size of the queue. If size is not provided, the default value would be 10. Once you run the program, enter 
'1' into the console to add elements in the queue (Offer), 
'2' to remove an element from the queue (Poll), 
'3' to display the element at front of the queue (Peek), 
'4' to display size of the queue, 
'5' to check if the queue is empty,
'6' to clear the queue, and
'7' to fill user supplied array with the elements of the queue, in queue order