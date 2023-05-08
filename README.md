Download Link: https://assignmentchef.com/product/solved-solved-create-a-package-named-cs520-hw5
<br>
Create a package named cs520.hw5 SolutionCreate a package named cs520.hw5. Using this package, create the following classes.

Create a class named Student as follows. The class keeps track of the student’s homework grades. This is a modification of HW4 using arrays.The instance (or member) private variables – name (String), homeworks (an integer array).A static public integer variable, NUM_HOMEWORKS, initialized to 6.A single constructor with name as its argument. Also, allocate the space for the homeworks array to hold NUM_HOMEWORKS valuesThe public get and set methods for the name instance variable.A void setHomeworkGrade method which takes two arguments – a zero based index of the homework and the corresponding homework grade. In the body of the method, store the homework grade into the corresponding array location.A public computeAverage method which takes no arguments and returns a double showing the average homework grade for this student. You should use a for loop to add the homework grades and then compute the average. This code should be independent of the length of the homework array.Override the toString method to return the string representation of this object in the format “The &lt;studentName’s average grade is

Create a Test class to test the following functionality in its main method.a.Declare and initialize an empty ArrayList of Student objects named studentList.

b.Declare and initialize an empty HashMap named studentMap. The keys will be the names of the students and the entries in the map will be the corresponding student objects.

c. Use the BufferedReader class to read the data.txt file. The contents of the file are shown below. Create the data.txt file in HW5_lastName.

d.Read the contents of the text file one line at a time using a loop. The program should work for any number of input lines. In this loop,

Invoke the processInputData method for each line read. This method returns the corresponding Student object.Add this Student object to the studentList.Insert this Student object into the studentMap using the student’s name as the key.e.After the loop is processed, do the following.

Create an iterator for the studentList. Iterate over each element in the list using this iterator. Display each element to the console.Access the keys of the studentMap and assign them to an appropriate variable. Create an iterator over the keys. Iterate over each key in this set and display the associated object in the map to the console.

Write a private method processInputData with return type Student which processes its string input argument and returns the corresponding Student object as follows.

Tokenize the string argument using the StringTokenizer class using the comma as the delimiter.Extract the name token. Create a Student object and assign to the variable currentStudent.Use a counter variable, initialized to 0, to keep track of the homework index.Using a while loop, read the next homework grade token. Use the setHomeworkGrade method on the student object to set the homework grade for this homework. Make sure to increment the counter in the loop.Display the string representation of the currentStudent object to the console.The method should return the currentStudent object.Sample Input data.txt file:

Alice,44,79,85,72,77,57

Bob,79,94,70,71,71,51

Charlie,95,99,41,55,65,50

Dave,87,89,88,55,74,63

Ed,82,51,44,67,73,49