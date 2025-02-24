Download Link : https://programming.engineering/product/university-member-lab/

# University-Member-Lab
University Member Lab

Introduction:

This lab will create a class, University Member (UnivMember), which will contain and use the ID and Name classes you built previously, adding a Role.

Instructions:

Create the UnivMember class holding at least:

UnivID

UnivName

Role (Prof, Student or Admin). For now, Role is a string

Each person’s name will be read from a file

The format is the same as before: last,first

Note: The first name is everything to the right of the comma

Please build and use a helper function inside of Name that will remove any trailing blank chars at the end of the first name.

Note: You can most easily generate the name for a UnivMember with:

UnivName = Name(fullname);

Read the file: CSProfNames.txt Find this file and the one below on Blackboard

Create a vector of University Member references, where the Role is set to “Prof”.

Read the file StudentNames.txt

Add these to the University Member references, where the only difference is that Role is set to “Student”.

Finally, print all the University Members, with their Role, Name (first then last) and ID on the next line. Be sure to create a function inside UnivMember for this.

Strategy: You might consider testing the format of the output from the CSProfNames before building the StudentNames version.

Be sure to build all constructors, destructors, getters and setters (accessors and mutators).

Note: This lab does not yet use inheritance, but we will be soon! Feel free to start creating it after this is working.

Example Output:

Prof: Abdullah Al Hayajneh

ID: A10000000

Prof: Robert Alpert

ID: A10000001

Prof: Tamer Aly

ID: A10000002

Prof: Mohammad Ruhul Amin

ID: A10000003

Prof: Silvio Balzano

ID: A10000004

Prof: Zakirul Alam Bhuiyan

ID: A10000005

Prof: Sharang Biswas

ID: A10000006

… other profs here…

Prof: Yijun Zhao

ID: A10000043

Prof: Martine M. Zilversmit

ID: A10000044

Student: Miley Cyrus

ID: A10000045

Student: Lady Gaga

ID: A10000046

Student: Ariana Grande

ID: A10000047

Student: Alicia Keys

ID: A10000048

Student: Bruno Mars

ID: A10000049

Student: Ed Sheeran

ID: A10000050

Student: Harry Stiles

ID: A10000051

Student: Taylor Swift

ID: A10000052
Solution
