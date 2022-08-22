# If Else Loops

---

Go back:    [The Basics](../The%20Basics%20f90e1521060e4f4da6383c736ae2e894.md) 

When we want to apply logic to our code, we can add If Else loops in order to get our code to change according to different data!

Lets start with a basic ‘if True:’ loop:

```python
if True:
	print('Success')
if False:
	print('Fail')
```

Each loop ends when a new un-indented line starts, like this:

![Untitled.png](If%20Else%20Loops%2002f36b36d5fe463c86c523586d7d0bfc/Untitled.png)

What do you think will appear when we run this code?

Using logic, we can predict that the “if True:” loop will run because of the obvious statement of “if True”; the same is with the “if False:” loop.

So we get an output of:

<aside>
💡 $python3 file.py
Success

</aside>

Great! You’ve learnt If loops, now onto else loops!

If Else loops are just advanced If loops!

Heres an example:

```python
var1 = True
if var1 == True:
	print('True')
elif var1 == False:
	print('False')
```

When we run this, the computer will go through the first if loop:

```python
var1 = True
if var1 == True:
	print('True')
```

The first loop checks if var1, our variable, is equal to true, then if it is, it does whatever is in the indented space below! So therefore, it prints ‘True’!

Now the next loop, is our first if else loop, AKA else if, AKA elif.

```python
elif var1 == False:
	print('False')
```

Now this does a very similar thing to our previous loop, it checks if our variable, var1 is False, instead of True! Then if it is False, it will do what is indented below it, which is printing ‘False’!

The difference between two ‘if’ loops and one ‘if’ and one ‘elif’ loop is quite small, but provides a huge advantage!

When we get more advanced in our scripts, we might need to run one if loop until one returns True! It’ useful if you need to only get one result back, to prevent from getting your computer to overwhelmed from receiving to much inputs!