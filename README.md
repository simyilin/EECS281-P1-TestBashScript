# EECS281-P1-TestBashScript
Bash script to automate testing of all files for EECS281 Fall 2020 Project 1 (Letterman)

# Test files naming convention
test-n-start-end-flags.txt

# Output text file
Default is batch_output.txt, can be modified by changing ```output="batch_output.txt"```

# Check difference with pre-saved expected output file
Copy and paste content of generated output (batch_output.txt) to new text file (expected_output.txt)
Replace generated content in expected_output.txt with expectations
Find difference using ```sdiff batch_output.txt expected_output.txt```
