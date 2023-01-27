# PIPS2023
# PIPS2023 Contains three function that I made for PIPS 2023 Assignment 3.2R

# remind_me
This function contains a reminder of my friend's birthday.

## Example use:
### remind_me()
[1] "1998-08-26"


# cheat
This function tells user the correct answer to Question 1, 7, 17 in Assignment 3.1
## Example use：
### cheat(7)
[1] "ggplot(ChickWeight, aes(x = Time, y = weight)) +\n  geom_smooth(method = lm)"

### cheat(3)
[1] "Sorry the question you asked is not on this cheatsheet"


# make_art
This function allows user to make random rainbow-colored wave line graph art. It contains an optional argument that is used as a random seed to make the images reproducible.
## Example use:
### make_art(seed = 123)
This would return a reproducible image with the seed set as 123
or
### make_art()
This would generate different image every time you run
