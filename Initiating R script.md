---
editor_options: 
  markdown: 
    wrap: 72
---

# Make the function remind_me()

    remind_me <- function() {
      birthday <- "1998-08-26"
      return(birthday)
    }

    remind_me()

# Make the function cheat()

    cheat <- function(x) {

    if (x == 1) {

    return("final_grade <- rnorm(63, mean = 75, sd = 5) hist(final_grade)")

    }

    if (x == 7) {

    return("ggplot(ChickWeight, aes(x = Time, y = weight)) +
    geom_smooth(method = lm)")

    }

    if (x == 17) {

    return("#short cut to automatically format hightlighted Rcode (for MAC):
    Command + Shift + A")

    }

    else{

    return("Sorry the question you asked is not on this cheatsheet")

    } } 

# Make the function make_art()

    make_art<-function(seed=NULL){ if(is.null(seed)==FALSE){ set.seed(seed) }

    x = seq(runif(1, min = 0, max = 4), 2*pi, by=.1) 
    plot\<-plot(x-pi/4,sin(x), type="l", col = 'red') 
    lines(x, sin(x), col='orange')
    lines(x+pi/4, sin(x), col='yellow') 
    lines(x+pi/2, sin(x), col='green')
    lines(x+(3*pi)/4, sin(x), col='blue') 
    lines(x+pi, sin(x), col='purple')
    return(plot) }

    make_art()
