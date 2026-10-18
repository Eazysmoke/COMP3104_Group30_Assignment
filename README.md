# COMP3104 Group 30 Assignment

## Contributor
- Mechel Fernando — 101352126
- GitHub: https://github.com/Eazysmoke
- Branch: 101352126-Mechel

## Project Description
This assignment practises Git, GitHub, branches, pull requests, and continuous integration.

## Setup
Clone the repository and switch to my branch:

```bash
git clone https://github.com/Eazysmoke/COMP3104_Group30_Assignment.git
cd COMP3104_Group30_Assignment
git checkout 101352126-Mechel
cat > README.md <<'EOF'
# COMP3104 Group 30 Assignment

## Contributor
- Mechel Fernando - 101352126
- GitHub: https://github.com/Eazysmoke
- Branch: 101352126-Mechel

## Project Description
This assignment practises Git, GitHub, branches, pull requests, and continuous integration.

## Setup
Run these commands:
git clone https://github.com/Eazysmoke/COMP3104_Group30_Assignment.git
cd COMP3104_Group30_Assignment
git checkout 101352126-Mechel

Only Git is needed. There are no additional dependencies.

## Assignment Files
- 101352126_gb.txt: George Brown College information.
- 101352126_devops.txt: DevOps course information.
- 101352126_sdlc.txt: DevOps in the software development lifecycle.

## CI Pipeline
The workflow is in .github/workflows/ci.yml.
GitHub Actions runs on pushes and pull requests using ubuntu-latest.
It checks that the three required text files exist and contain content.

## Branching Strategy
My work is committed locally on 101352126-Mechel.
Changes are submitted to main through a pull request.
After merging, the local branches are updated from main.
