# Creating New Practice Tests
Just so that you don't forget how to do this.

## Folder Creation
First, Create a new folder (e.g. "2012B") in the practiceAMC12 folder. In this folder, add three things: "home.md","answers", and "test.html".
In home.md, just create a sort of homepage that directs people to the results/test. You can copy the home.md of a previous test and just change the title.
In answers, put in the answers to the test.
In test.html, put in the testing interface. Feel free to copy the test.html from a previous test, but make sure you change the questions in the form (plug the source code from AoPS into your C++ compiler at NovicePacket2020/GetAMCProblems). Don't forget to add in the images with <img> tags.

Also be sure to upload any pictures/geometry diagrams in the test into the folder so that your <img> tags actually do something.

## results.html
Afterwards, go to results.html and add a form there with the test title (ex. "2011B"). Put in a read-only form. (plug the source code from AoPS into your C++ compiler at NovicePacket2020/GetAMCProblems).

## testTable.html update
The second (and last thing) you have to do is go to testTable.html and update some stuff there. This includes (but might not be limited to):
Adding to testAnswers
Adding to testFolderName
Adding the id number for a specific test (e.g. 10a=0, 10b=1)
Adding to testName
Adding to testCode

## And that's it!

...Hopefully! :)
