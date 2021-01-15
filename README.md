# Cpp-Setup-for-Sublime-Text
Setup a comfortable environment to code on Sublime text.

Steps -
1. Download and install Sublime Text.
2. Create a folder "code" or give it any name you wish.
3. Open sublime text, create a sample C++ program and save as 1.cpp in the folder you just created.
4. Press Alt + Shift + 3 to divide the window in 3 parts and drag the other two to adjust as per your needs.
5. Bring the cursor to the 2nd part and save as "inputf.in" in the same folder you created before.
6. Repeat step 5 just changing input to "outputf.in" for the 3rd part
7. Make sure the compiler is setup correctly by opening a powershell window in the same folder and executing the following - "g++ --version" (without the double qoutes).
If some error shows up, google how to add g++ as an environment PATH variable.
8. Now open Sublime text and goto Tools -> Build System -> New Build System...
9. Copy the code from c++14-build-system-windows and paste it in there and save as "c++14" and select the same from the sub context menu of Build System.
10. Restart Sublime text and Happy Coding!!!
