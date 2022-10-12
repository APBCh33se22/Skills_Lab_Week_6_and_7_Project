# Purpose

Code accepts user input for name and age, determines if user is eligable to vote in the United States (18+ years of age), and returns result. It's just that simple.

# Installation Details

For usage, simply download zip file, unpack, and modify the "Something-code.ipynb" file to use the ".py" extension. From there, we recommend using one of the any popular dedicated Python IDEs, such as MuPython, to open and run the code.

For modification, follow standard GitHub clone procedure. Under our license, any and all users are permitted to modify the code we have created. Have fun with it and don't be malicious, see code of conduct for details.

# Usage Instructions

User input for age accepts integer values only, float input will result in fatal error. Just don't.

```python
if (age > 120 or age <= 0):
        print("That is not a valid age!")
    elif (age >= 18):
        print("You are eligible to vote!")
    else:
        print(f"You will be able to vote in {18-age} years.")
