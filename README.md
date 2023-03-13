# Code Refactoring in Python

## What is code refactoring?

In computer programming and software design, code refactoring is the process of restructuring existing computer code—changing the factoring—without changing its external behavior. Refactoring is intended to improve the design, structure, and/or implementation of the software, while preserving its functionality

## How it done in python?

It is done byy using Sourcery module.

## What is Sourcery module?

It instantly reviews your Python code and refactors it, making it cleaner and more readable. It's like having a pair programmer always working next to you. Install into PyCharm, VS Code, or your GitHub repos in 1 minute.

## How to refactor python code using Sourcery?

**Step 1 :-** Open Windows Powershall/CMD ,then type **"pip install sourcery"**.

Wait to install module.

**Step 2 :-** Login/signup in sourcery by typing **"sourcery login"** in terminal.

**Step 3 :-** Refactor your code my typing **"sourcery review --in-place Python_file_name.py"**.

after executing this command Sourcery module scan your code and refactor it.

You can find output/refactor code in your python file.

### Example:-

#### Before Refactoring

```py
def is_special_number(number):
    if number == 7:
        return True
    elif number == 18:
        return True
    else:
        return False
``` 
#### After Refactoring

```py
def is_special_number(number):
    return number in [7, 18]
```

#### To know more about Sourcery module [click here](https://docs.sourcery.ai/Welcome/).
