# CSC-401
Project 1: Preliminaries of Javascript and HTML:
Look at https://www.cs.miami.edu/home/burt/learning/Math119/js-NumberBuild.html Number
Build (Number Build). Make a webpage like Number Build using Javascript, except that if a user
marks the numbers summing to the year that University of Miami was founded, then the program
displays a photo of the campus (of your choice). 

Project 2: Do an algorithm animation of Randomize-In-Place (we discussed in CSC317 class; see
           pseudocode in CLRS book, Chapter 5, p 126):
RANDOMIZE-IN-PLACE(A)
1. n=A.length
2. for i = 1 to n
3. swap A[i] with A[Random(i,n)]
The algorithm should display the pseudocode and line by line highlighting through the code,
along with the resulting array. Test your algorithm to see that it works as you expect it to. For an
example of an algorithm animation (which is different than the above assignment, but shows a
full example of implementing an animation of another algorithm we learned in class), see
Partition Algorithm Animation:
(http://www.cs.miami.edu/~burt/learning/Csc517.101/workbook/partition.html). Feel free to
modify the style of your animation to your liking.


Project 3: Implement a double hashing animation. See linear probing example: http://www.cs.miami.edu/home/burt/learning/Csc517.101/workbook/hashing_linear.html
Make the table size 16. Set the first hash function as: 𝐻1 = 𝑘𝑒𝑦 𝑚𝑜𝑑 16; and the second hash function as:
𝐻2 = 2 (𝑘𝑒𝑦 𝑚𝑜𝑑 4) + 1. Try to illustrate the collisions and skips to new slots in the table. Recall: In double hashing, the slot is determined by (𝐻1 + 𝑖 𝐻2) 𝑚𝑜𝑑
16, in which 𝐻1 is the first hash function and 𝐻2 is the second hash function. Here 𝑖 multiplies 𝐻2, and initially 𝑖 is set to 0; then if there is a collision we
set 𝑖 to 1; then if there is still a collision we set 𝑖 to 2; and so on.
