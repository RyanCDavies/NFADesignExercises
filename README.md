# NFA Design Exercises #1
## Problems
NFAs that had multiple possible kinds of accepted strings gave me an issue on question number 8. Ideally, I could have just split the strings using epsilon to cover both cases.
The questions I chose were the first 5 because I'm not creative and just worked until I was done. Maybe I could have done some of the more complex ones but I didn't really have a reason to challenge myself here since we already went over the exercises in class.
I asked ChatGPT for some help concerning what a "gold-str-ing" was. Apparently it's a string that describes some aspect of the NFA.

## Gold Strings
I had a few "gold-str-ings" that threw me off. The two main ones were "010" for question #10 and "10001010010" for question #8.
For question 10, I failed to set the initial state as an accepting state. For question #8, I completely neglected the case where the "1" was both a part of the starting substring "01" and the ending string "10". Next time, I'll remember I can just add an additional state transition for the epsilon value to cover the missing state.
