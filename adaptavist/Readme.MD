ADAPTAVIST - SYSOPS ENGINEER - TECHNICAL ASSESSMENT

This assessment requires a python script as well as command-line application taking the path to the target file as an argument.

I have provided the archived python script, 2 images showing the file structure before and after extraction and 2 input txt files that have the same words but the paragraphs have been reveresed to allow testing of the script within the same directory. 

To run this code, you will require:
1. An IDE like VS Code,
2. Python installed on the machine,
3. Git installed and configured correctly on the IDE.

Running the code:
1. Open your terminal, 
2. Navigate to your project directory,
3. Clone this repository using: "git clone https://github.com/rosinaoa/adaptavist.git"
4. CD into the adaptavist directory,
5. Run this command to extract the archive file: "tar -xzvf count.tar.gz",
6. That should now show the "count.py" python file in the directory,
7. Run this command to test the code with input_1.txt: "python count.py input_1.txt" and you should get the print output on the terminal,
8. Run this command to test the code with input_2.txt: "python count.py input_2.txt" and you should get the print output on the terminal.

The python script prints each word in the file along with its count, sorted by the count in descending order.

If you want to archive the python file you can use this command to archive it: "tar -czvf count.tar.gz count.py"

In using this file always make sure to use the correct path to the file you are working with.