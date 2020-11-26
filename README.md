# EECS281-TestBashScript
Bash script to automate testing of all files for EECS281 Fall 2020 Projects  
Usage: Navigate to directory containing script and test files and use command ```./batch_script```

# Project test files naming convention
Project 1 (Letterman) : test-n-start-end-flags.txt  
Project 2A (Mine Escape) : test-n-flags.txt  
Project 3 (SillyQL) : test-n-table-commands.txt  
Project 4 (AmongUs): test-n-mode.txt

# Output text file
Default is batch_output.txt, can be modified by changing ```output="batch_output.txt"```

# Check difference with pre-saved expected output file
Copy and paste content of generated output (batch_output.txt) to new text file (expected_output.txt).  
Replace generated content in expected_output.txt with expectations.  
Find difference using ```sdiff batch_output.txt expected_output.txt```
