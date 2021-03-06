# Advanced Data Structures & Algorithms with Python

## Course Schedule

**Course Dates:** Monday, March 20 – Friday, May 12, 2017 (7 weeks)

**Class Times:** Monday, Wednesday, Friday 1–3pm (21 class sessions)


### Class 1: Monday, March 20 – Number Bases

**Topics:**
  - review exponents, logarithms
  - [number bases slides] decimal, binary, hexadecimal
  - [negative integer representations] signed magnitude, ones' complement, two's complement

**Challenges:**
  - practice conversions on [number bases worksheet]
  - implement base conversion functions for positive numbers using [starter code](source/bases.py) and [unit tests](source/test_bases.py)
  - stretch: implement base conversion for negative binary numbers
  - stretch: implement base conversion for fractional numbers

[number bases slides]: slides/NumberBases.pdf
[number bases worksheet]: slides/NumberBasesWorksheet.pdf
[negative integer representations]: https://en.wikipedia.org/wiki/Signed_number_representations


## Working with this GitHub repository

This repository (located at `https://github.com/MakeSchool-18/Data-Structures`) is the course's _origin_ repository which will contain course materials including links, slides, and challenges.
Note that you cannot commit or push to the origin repository.
However, you can _fork_ it to maintain your own version of it and push your code there. Here's an overview of what your repository setup should look like:

![Repository Overview](repository-overview.png "Repository Overview")

Follow these steps to set up your own course repository:

1. Clone this repository on your computer:
`git clone git@github.com:MakeSchool-18/Data-Structures.git`

2. Fork this repository on GitHub to create your own version of this repo on your GitHub account, which should also be named `Data-Structures`

3. Add your GitHub repository as a _remote_ to the local one on your computer (note: you need to give a name to the remote, e.g. your first name):
`git remote add <first-name> git@github.com:<github-user>/Data-Structures.git`

4. Link the local repo to your remote GitHub repo:
`git push -u <first-name> master`

5. When you want to access new course materials, just pull from the origin remote repo:
`git pull origin master`

6. When you've completed a challenge and want to share it for code review, commit your work and push it to your own remote repo with:
`git push`
