# Learning Takeaways

## Overview

This project helped me practice how multiple Python concepts work together in one interactive program.

## Key Skills I Practiced

- I used lists and dictionaries to organize trivia questions and their categories.
- I created a function that accepts a question, checks the user's response, and returns `True` or `False`.
- I used `input()` to collect user responses.
- I used `.strip()` and `.lower()` to make answer comparisons more flexible.
- I used `if` and `else` statements to control program behavior.
- I used `try` and `except` to handle missing input without crashing the program.
- I used a `for` loop to move through the question list.
- I used a `while` loop so the user could continue selecting categories.
- I used `break` to exit the loop when the player was finished.
- I tracked the number of correct answers and the number of questions attempted.
- I used `datetime` to add a timestamp to the game results.
- I practiced debugging indentation, loop structure, and program flow.

## Most Important Lessons

One of my biggest takeaways was learning how functions can simplify a program by handling one responsibility and returning a result that can be used elsewhere.

I also learned how important indentation is in Python because it determines which statements belong to loops, conditions, and functions.

Another important lesson was avoiding repeated code. Once my `ask_question()` function handled the user's answer and returned `True` or `False`, I did not need to ask for the same input again in the main loop.

## Future Improvements

In the future, I could improve the project by:

- Adding more questions to each category
- Preventing repeated questions
- Randomizing question order
- Adding difficulty levels
- Saving scores to a file
- Building a graphical user interface
