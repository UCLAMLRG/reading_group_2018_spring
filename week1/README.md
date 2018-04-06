# Week 1

## Getting Started

- Introduction to git, conda, jupyter notebooks: https://github.com/UCLAMLRG/Basics
- Introduction to SciServer (see below)
- Sign up for slack channel at https://uclaml.slack.com

## Quick-Getting started with SciServer Compute
SciServer.org is a computational cloud environment that Johns Hopkins University (IDIES group) has generously allowed us to use for our projects. Jupyter notebooks/terminal are the interfaces to access datasets such as SDSS. Here's how to clone this github repo into your SciServer account:
1. Create an account at alpha02.sciserver.org and go to Compute
2. Create a new container (Docker container), choose the type to be Python, and a container Jupyter notebook interface will be created.
3. On the right hand side, go to New-> terminal and a black terminal interface will appear.
4. In this order in the terminal, type each of these at a time (separated by a comma) and hit enter:
5. ls, cd home, ls, cd idies, cd workspace, cd persistent, ls, git clone url-of-git-repository-here
6. the repository will now be in your folder.

**NOTE**: Only data stored in `persistent` will be saved!
