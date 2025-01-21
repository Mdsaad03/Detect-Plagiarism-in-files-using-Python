# Detect-Plagiarism-in-files-using-Python
In this project we are going to discuss how to check the plagiarism between the contents present in two different text files. In python this can be done using predefined package difflib but we are going to check it manually. Let’s get into it….
•	Description: Developed a Python-based plagiarism detection tool that reads and compares text from two files to calculate the percentage of similar content. The project involved data processing, extracting common words, and applying a formula to compute the plagiarism percentage. Used a graphical interface with Tkinter to display results visually with color-coded warnings based on similarity levels.
•	Technologies Used: Python, Tkinter, Set Operations, File Handling, Text Processing.
Get the code from above i uploaded [myfile1]
# Code Explanation :
1. First we read the contents of two files using open() method
2. We read the contents of lines using read() function which return as string.
So we splitted that string into list of words by excluding punctuation marks(,).
3. We extacted the common words from two lists by conveting them to sets.
4. Next we calcualted the length of plagarised words and total words present in two files.
5. Finally we applied a formual there to calculate the plagarised content from two files and printed it on the screen
#OUTPUT
![image](https://github.com/user-attachments/assets/9fc4d0e2-6441-4b7c-aa2d-7fc03c0facb8)
