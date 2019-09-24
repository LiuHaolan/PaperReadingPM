# Bill Griswold's Paper Reading Template

## Basic Information
Title: Closing the Performance Gap Between Volatile and Persistent Key-Value Stores Using Cross-Referencing Logs

Authors: Yihe Huang, etc

Published in: ATC'18

## Main Point
What is your take-away message from this paper?

### What is Cross-Referencing Logs? Why need it and how it works?


## Motivation
What is the motivation for this work (both people problem and technical problem), and its distillation into a research
question? Why doesn’t the people problem have a trivial solution? What are the previous solutions and why are they
inadequate?

## Solution
What is the proposed solution (hypothesis, idea, design)? Why is it believed it will work? How does it represent an
improvement? How is the solution achieved?

### Four key optimization
1, fully decoupled Put()

2, Non-blocking Gets()

3, write-load 

4, opportunistic Put collapsing

## Evaluation
What is the author’s evaluation of the solution? What logic, argument, evidence, artifacts (e.g., a proof-of-concept
system), or experiments are presented in support of the idea?

## Your idea
What is your analysis of the identified problem, idea and evaluation? Is this a good idea? What flaws do you perceive
in the work? What are the most interesting or controversial ideas? For work that has practical implications, ask
whether this will work, who would want it, what it will take to give it to them, and when might it become a reality?

## Contribution
What are the paper’s contributions (author’s and your opinion)? Ideas, methods, software, experimental results, experimental techniques...?

## Future Work
What are future directions for this research (author’s and yours, perhaps driven by shortcomings or other critiques)?

## Confusions
What questions are you left with? What questions would you like to raise in an open discussion of the work (review
interesting and controversial points, above)? What do you find difficult to understand? List as many as you can.

