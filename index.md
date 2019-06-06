---
layout: lesson
---

# Overview

This module will cover creating environments for reproducible science

## Target Audience/prerequisites

Audience may have little or no experience with programming, but may be proficient at button clicking. (mostly coming from psychology/neuroscience phd programs)

- expected size of audience: (10-20)
- time investment (25 hours?) + 4 hours in the brainhack

## Student Profile

Battlestar Galatica is a second year graduate student measuring the weight from two groups of rats on a weekly basis.
One group of rats has aperol spritz with every meal, and the other has water.
After each week, she types the data into a excel sheet, gets descriptive statistics of the samples for that week/overall and runs a t-test at each of the time points.
she already has an excel sheet that auto-populates the fields, but she is thinking about doing more advanced analyses of the data (longitudinal mixed effects models).
She has not worked with python/R before, and would like to start out small to replicate her excel workflow in R/python, with a longer term eye on implementing the more advanced model.

## Overall objective

- learn computational vocabulary
- use fundemental tools
- interact with people with different backgrounds

## Schedule

I will be hosting a weekly flipped classroom for 5 weeks prior to the workshop.
I will ask the participants to begin to think about what repetitive tasks or analysis steps they perform in excel and write down (and share) their goal for using shell/python/R to (partially) automate the task.
I will assign the lesson for the participants to go through on Monday, and host in-person
office hours on Friday (3:00-5:00pm).
At the office hours, participants can ask about roadblocks they had in the lessons, or in their automation goal.
Throughout the week, those that have registered will have access to a mattermost(?)
channel/or direct messages to ask questions to me/each other as they engage with the lessons.

| Week | Topic             | objectives                                                                                               | module                                                          |
|------|-------------------|----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| 1    | shell/installfest | (move/rename/cp/rm files) (install github-desktop/appropriate bash environment/conda/R)                  | http://swcarpentry.github.io/shell-novice/                      |
| 2    | git/github        | (understand conceptually what git accomplishes) (syntax for adding/commiting/pushing/forking)            | http://swcarpentry.github.io/git-novice/                        |
| 3    | python            | (interacting with tabular data numpy/pandas) (create conda environment) (some data structures/for loops) | http://swcarpentry.github.io/python-novice-inflammation/        |
| 4    | R                 | (interacting with tabular data) (some data structures/for loops)                                         | http://swcarpentry.github.io/r-novice-inflammation/             |
| 5    | hpc               | (how to submit jobs to cluster) (use a singularity container)                                            | (make some material) https://hpc-carpentry.github.io/hpc-shell/ |


After week five, we will be hosting a 2-day brain hack with two 2-hour tutorials.
While the participants will have say in what exactly is covered, my plan if no preference
is indicated:

- creating environments (dockerfile/singularity)
  - use the hpc?
  - http://www.repronim.org/module-reproducible-basics/03-packages/
  - http://www.repronim.org/module-dataprocessing/04-containers/

- testing your analysis (travisci/circleci)
  - http://www.repronim.org/module-dataprocessing/06-testing/
  - http://www.repronim.org/module-reproducible-basics/01-shell-basics/

## Measure(s) for success

- They create a script that solves their problem (potentially as a personal project at the brain hack)
  - the script is version controlled
  - the script is on github
  - the script has a test
  - the script runs in a container
  - the script is automatically tested
- They interact with people outside their field (by attending the brain hack and acting as a source of a user profile for a tool developer)
- they become interested in reproducible (efficient) practices

## Drawacks

- do I introduce a text editor/which one do I introduce?
- what debugging strategies should I introduce?
