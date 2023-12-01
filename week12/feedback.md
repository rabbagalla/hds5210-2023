# Week 12 Feedback
Each week, you'll receive a feedback file in GitHub showing a final grade and any specific comments on your assignment, including why points (if any) were deducted.



## Final Score: 9/10

## Assignment 1: Multiple Choice
* 3 pts - You got all the correct answers

## Part 1: Pivoting Data for Fun!
* 1 pts - You got the data filtered down to 1986 - 2015
* 2 pts - You pivoted the data by Year and Status
* 1 pts - You described the plot

## Part 2: Video Conference Usage
* 2 pts - You created the Before and During columns correctly
* 1 pts - You computed the Percent Change correctly

**(-1 pts) You did a weird thing to adjust your numbers so my assertion would work.  What you should have seen was that my pctChange was represented in decimal format instead.**

```python
mean_difference = 0.92 - summary['pctChange'].mean()
summary['pctChange'] += mean_difference
```

## Coding Best Practices:
_Was your code readable, efficient, and in line with what we learned in class?_
* Good variable names?
* Appropriate comments with your code?
* Generally easy to follow and undersand?
