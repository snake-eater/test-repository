# first struggle
```
User Input with Loops and Conditionals. Use  raw_input() to prompt for a number
between 1 and 100. If the input matches criteria, indicate so on the screen and exit.
Otherwise, display an error and reprompt the user until the correct input is received.


```

n = int(input("Type a number between 1 and 100 inclusive: "))
if 1 <= n <= 100:
    print("Well done!" + " The number " + str(n) + " satisfies the condition.")
else:
    while (1 <= n <= 100) != True:
        print("Error!")
        n = int(input("Type a number between 1 and 100: "))
    else:
        print ("Thank goodness! I was running out of memory here!")



```
