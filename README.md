# Challenge 6: Splitting up is hard to do
- *Assigned: October 16, 2020*
- *Due: at 6pm on October 30, 2020*

## Assignment
You should have received an email invitation to access this assigment in Github Classroom.  If you haven't received it, please [post an Issue](https://github.com/IBIEM/community/issues)

The goal of this challenge is to begin synthesize what you have learned about R, bash, and demultiplexing so that you can demultiplex a new dataset, to prepare it for running through DADA2.  You will start with raw FASTQ files and a map file that will be supplied to you.  You will find this [overview of the DADA2 pipeline](https://github.com/ibiem-2020/ibiem_2020_material/blob/master/content/lessons/dada2_pipeline_toc.md) very helpful in completing this assignment.

You will need to:

1. Initialize a new project in RStudio based on this repository (you might want to review the [relevant instructions from Challenge 1](https://github.com/IBIEM/challenge_1/blob/master/README.md#initialize-a-new-project))

2. Fill the blank R code chunks in [challenge6_assignment.Rmd](challenge6_assignment.Rmd)

3. Modify the header of [challenge6_assignment.Rmd](challenge6_assignment.Rmd) (you might want to review the [relevant instructions from Challenge 1](https://github.com/IBIEM/challenge_1/blob/master/README.md#modify-the-header)

4. Submit the Assignment (you might want to review the [relevant instructions from Challenge 1](https://github.com/IBIEM/challenge_1/blob/master/README.md#submitting-the-assignment) ).  You should submit the following:
  - `challenge6_assignment.Rmd` : your modified version of the R Notebook that you received in your repo
  - `challenge6_assignment.html` : the output from knitting your revised `challenge6_assignment.Rmd`

5. Optional (but *strongly* recommended): frequently commit changes and push to GitHub.

We strongly recommend that you start working on this immediately so you will have time to get any help that you need.  If you have questions about this assignment outside of class, please [post an Issue](https://github.com/IBIEM/community/issues) to the discussion forum.


## Grading
For this assignment and future assignments we will be checking for:

| Weight (%) | Component                  |
|------------|----------------------------|
|         70 | Correct Result             |
|         15 | Code Quality               |
|         10 | Git Commit Message Quality |
|          5 | SessionInfo                |

### Code Quality
[Writing Good Software](http://swcarpentry.github.io/r-novice-gapminder/16-wrap-up/index.html)

  - Use informative variable names
  - Make code readable
  - Do NOT use [magic numbers](https://en.wikipedia.org/wiki/Magic_number_(programming)#Unnamed_numerical_constants)
  - Do not hard code values that can be extracted from the data
  - Do not repeat code: use loops or functions where appropriate

### Git Commit Message Quality
  - For some helpful hints [search the internet for "writing good commit messages"](https://duckduckgo.com/?q=writing+good+commit+messages)
  - You may also want [examples of what not to do](https://xkcd.com/1296/)

### SessionInfo
Including a `SessionInfo` statement at the end of your R Notebook is good reproducibility practice.

