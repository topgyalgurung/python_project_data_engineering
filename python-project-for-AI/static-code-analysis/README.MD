Install the pylint package
$ pip3 install pylint==2.11.1


Run pylint
Open a terminal
run the below command
pylint sample1.py
Pylint goes through every line of code and gives you a list all the non-compliant lines.
Pylint gives you a compliance score (10 being maximum).

sample1.py gets 0/10 score 
sample1.py:7:0: C0304: Final newline missing (missing-final-newline)
sample1.py:1:0: C0114: Missing module docstring (missing-module-docstring)
sample1.py:1:0: C0116: Missing function or method docstring (missing-function-docstring)
sample1.py:4:0: C0103: Constant name "num1" doesn't conform to UPPER_CASE naming style (invalid-name)
sample1.py:5:0: C0103: Constant name "num2" doesn't conform to UPPER_CASE naming style (invalid-name)
sample1.py:6:0: C0103: Constant name "total" doesn't conform to UPPER_CASE naming style (invalid-name)
sample1.py:7:6: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)

sample_cleaned gets 10/10 score
