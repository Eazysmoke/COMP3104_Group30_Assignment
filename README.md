# COMP3104 Group 30 Assignment

## Contributor
- Mechel Fernando - 101352126
- GitHub: https://github.com/Eazysmoke
- Branch: 101352126-Mechel

## Project Description
This assignment practises Git, GitHub, branching, pull requests, and continuous integration.

## Setup
Clone:
git clone https://github.com/Eazysmoke/COMP3104_Group30_Assignment.git

Enter the repository:
cd COMP3104_Group30_Assignment

Switch to my branch:
git checkout 101352126-Mechel

Only Git is required. There are no additional dependencies.

## Assignment Files
- 101352126_gb.txt: George Brown College information.
- 101352126_devops.txt: DevOps course information.
- 101352126_sdlc.txt: DevOps in the software development lifecycle.

## CI Pipeline
.github/workflows/ci.yml runs on pushes and pull requests.
It uses ubuntu-latest and checks that all three text files contain content.

## Branching Strategy
I commit locally on 101352126-Mechel and submit changes to main through a pull request.
After merging, I pull main and update my local branch.
