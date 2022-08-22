# Converting Variable Types

---

Go back:    [The Basics](../The%20Basics%20f90e1521060e4f4da6383c736ae2e894.md) 

Below is a super simple addition script, somewhat like a calculator!

```python
inp1 = input('First number: ')
inp2 = input('Second number: ')

FinalNumber = inp1 + inp2

print(FinalNumber)
```

If we run this, we don’t get what we want back, 

<aside>
<img src="https://www.notion.so/icons/command-line_lightgray.svg" alt="https://www.notion.so/icons/command-line_lightgray.svg" width="40px" /> $python3 file.py
First number: 1
Second number: 3
13

</aside>

We *technically* get what we told the computer to do, but we wanted to add them together as numbers, not as text. In this case, we need to convert our text values to number values!

This is how we do it:

```python
inp1 = input('First number: ')
inp2 = input('Second number: ')

FinalNumber = int(inp1) + int(inp2)

print(FinalNumber)
```

When adding “int(<var>)” ( and replacing <var> with our variable, in this case “var1” ) it changes our previous value into an integer (int) AKA a number.

This technique can be used in many different ways!

More examples:

```python
#different type conversion
a = int(4.3)
b = float(12)
c = int('3')
d = str(9)
 
#print result
print(a)    # Returns: 4
print(b)    # Returns: 12.0
print(c)    # Returns: 3
print(d)    # Returns: 9
```