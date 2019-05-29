Download the Assignments.Zip, unzip it and import in Eclipse as "Existing project to Workspace"
configure the java version in build path to Java 1.8

There are 3 programs in the project Assignment
  1.ListMax
  2.MinimunArea
  3.ShortestSubstring
  
  Used java 1.8 for running all the java classes 

_______________________________________________________________________________________________________________________
1.ListMax

you will start with an array initialized to zeros with
indexes starting at 1. You will then be given a series of operations to
perform on segments of the list. Each operation will consist of a starting
and ending index within the array, and a number to add to each element
within that range.
For example, start with an array of 5 elements: [0, 0, 0, 0, 0]. The
variables a and b represent the starting and ending indexes inclusive.
Another variable k is the addend. The first element is at index 1.
  a   b   k       list
              [ 0, 0, 0, 0, 0]
  1   2   10  [ 10, 10, 0, 0, 0]
  2   4   5   [ 10, 15, 5, 5, 0]
  3   5   12  [ 10, 15, 17, 17, 12]
The maximum value in the resultant array is 17. That is the value to be
determined.

Input:
  The first line contains an integer, n, the size of your array
  The second line contains an integer, o, the number of operations
  The next line contains the integer 3, the number of elements used to define each operation
  o lines follow, each containing 3 space-separated integers, a, b, and
  k: the starting index, ending index and value to add

Sample Input:
            7
            5
            9   
            5
            3
            3
            1 2 100
            2 5 100
            3 4 100
Sample Output:
            200
______________________________________________________________________________________________________________________            
2. MinimunArea

Given a list of points described by their (x,y) coordinates on a two
dimensional plane, construct a square surrounding at least a given
number of points within the area enclosed. That area should be minimal
and the square must meet the following conditions:
  1.The x-coordinates and y-coordinates of the points should be integers.
  2.The sides of the square should be parallel to coordinate axes.
  3.At least k of the given n points should lie strictly inside the square drawn. Strictly inside means that they cannot lie on a side of the square.

For example, given n=3 points (1,1), (1,2) and (2,1) and k=3, surround
all three points. The minimum area square is 9 units, going from the
origin (0,0), to (3,3).

Input:
  The first line contains an integer n, the size of the array x.
  Each of the next n lines contains an integer x[i] where 0 ≤ i < n.
  The next line contains the integer n, the size of the array y.
  Each of the next n lines contains an integer y[i] where 0 ≤ i < n.
  The last line contains the integer k.
 
 Sample Input :
              2
              0
              2
              2
              0
              4
              2
Sample Output :
              36
_______________________________________________________________________________________________________________________________________
3.Shortest Substring

Given a string comprised of lowercase letters in the range ascii[a-z], 
determine the length of the smallest substring that contains all of the
letters present in the string.

For example, given the string s = dabbcabcd, the list of all characters in
the string is [a, b, c, d]. Two of the substrings that contain all letters are
dabbc and abcd. The shortest substring containing all the letters is 4 characters long, abcd.

Sample Input :
              bab
Sample Output :
              2
