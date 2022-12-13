## Replit

1. Go to the [following link](https://replit.com/@InstructorCODED/2-String-Interpolation-MadLibs#main.py).
2. Fork the task **2. String Interpolation - Mad Libs**.
3. Open `main.py` and solve the task.
4. Once you're done call an instructor.


## Task

In this task, the user should be given a story with gaps that the user should fill to complete the story. So basically a game of mad libs.

This is an example of what the output should like:

```
Mad libs where libs get mad.
Start below:

Enter a number from 1 to 12: 6
Enter a noun (plural): dolls
Enter a name: stephen sedoll
Enter any sentence: the future is made of dolls
Enter a verb: shake my head

The story goes...

It was 6 o'clock when I heard a knock at the door.
I opened the door and there was a box full of dolls with a note saying "From Mr. Stephen Sedoll."
Just as I closed the door I heard a scream "THE FUTURE IS MADE OF DOLLS."
I froze in place and all I could do was shake my head.
```

The user enters the number `6`, the plural noun `dolls`, the name `stephen sedoll`, the sentence `the future is made of dolls`, and the verb `shake my head`. Then the story at the end is generated automatically based on the user's input.

### Task Steps

- Use the story in the example above for the user to complete. The variables that need to be filled by the user's input are:
  - `time`
  - `items`
  - `name`: When printing the name to the user, the first letter of each word should be capitalized. See the example above.
  - `scream`: When printing the scream to the user, all the letters in the scream have to be capitalized. See the example above.
  - `action`
- Add the file `madlibs.py` to the git repository, commit changes, and push your code to the remote repository.

Hint: You will need [string methods](https://www.w3schools.com/python/python_ref_string.asp).
