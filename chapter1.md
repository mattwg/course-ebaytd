---
title       : Connecting to Teradata at eBay
description : This course will help you familiarise yourself with connecting R to Teradata in order to run SQL queries and get data into R dataframes.
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf

--- type:VideoExercise lang:r xp:50 skills:1 key:f76c47fe1d
## Inspire me!

*** =video_link
https://www.youtube.com/watch?v=YTtl5n-Tk-g

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:0433ded88f
## Where do you get the latest version of the ebaytd package?

*** =instructions
- github.com
- CRAN
- wiki
- the hub

*** =hint
It is on an internal eBay site - there are only two in that list!

*** =sct
```{r}
# The sct section defines the Submission Correctness Tests (SCTs) used to
# evaluate the student's response. All functions used here are defined in the 
# testwhat R package

msg_bad <- "That is not correct!"
msg_success <- "Exactly! This is an eBay specific package and is only available from the wiki - search for ebaytd to find the page."

# Use test_mc() to grade multiple choice exercises. 
# Pass the correct option (Action, option 2 in the instructions) to correct.
# Pass the feedback messages, both positive and negative, to feedback_msgs in the appropriate order.
test_mc(correct = 3, feedback_msgs = c(msg_bad, msg_success, msg_bad, msg_bad)) 
```

