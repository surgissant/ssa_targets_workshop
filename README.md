# Working smarter with Targets

A half-day introduction to the {targets} framework for R projects.

## Summary

This workshop is for useRs interested in smarter, faster, and more reproducible
data analysis project workflows. You will learn about the R package `{targets}`
and why it is one of the most important tools for 'getting stuff done' with R
since the `{tidyverse}`. The objective of this session is to jump start your
`{targets}` knowledge, and walk through the process of refactoring an existing
project to take advantage `{targets}`.


## Target audience

Participants should have prior experience working through at least one
challenging data analysis project using R.

## Presenter

Miles McBain is a Data Scientist and R package developer who has been using `{targets}` since release for large data analysis projects in the Public and Not-for-profit sectors.

# Structure of workshop

|time       | topic                                                                                   |
|-----------|-----------------------------------------------------------------------------------------|
|   TBA     | Motivating Targets: Strengths and weaknesses of typical R project workflows             |
|   TBA     | Pure functions and their benefits as units of work                                      |
|   TBA     | The {targets} plan and the two kinds of reproducibility                                 |
|   TBA     | Long vs Wide processes                                                                  |
|   TBA     | New debugging access panels                                                             |
|   TBA     | Divide and conquer with branching                                                       |
|   TBA     | Things that may go wrong and where to get help                                          |
|   TBA     | Advanced topics: Meta-programming, Tarcheytypes, Multi-plan projects, Cloud computing    |

As we step through each topic we'll refactor our starter project using our new knowledge.

# Getting started

1. You should have a reasonably up to date version of R (e.g. 4.3+), and a text editor setup you feel comfortable being productive with (E.g. RStudio, VSCode, ESS + Emacs, Vim + NvimR). It's going to be less typing if you can use the `{rstudioapi}` via either RStudio or VSCode.

2. Make sure you have these packages installed:

```
install.packages(c("targets", "tarchetypes", "tidyverse", "conflicted", "galah", "here", "sf", "h3jsr", "ggspatial"))
```

If you're a Linux user `sf` might give you some challenges (but you're used to that, right?). Be sure to study their README.

3. Our example project is going to pull data from the _Atlas of Living Australia_, so create an account with a valid email address, here:
https://auth.ala.org.au/userdetails/registration/createAccount


