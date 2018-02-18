# Dawgma's Development Repository for 2018 Power Up

This repository serves to hold the code for Dawgma's 2018 Power Up robot (yet to be named).

It may be a little bit confusing since there is another repository for that also. So I will clarify here. This original repository is a good bit messy and the other mentors and I have many concerns about its reliability (and other "ilities") as we go forward. There was a lot of trial and error prototype code in that repository, and a lot of code that does not work in there. So this repository shall be a more controlled and refined repository for code that we know works and that we will be using in competition.

## Organization of this Repository:
There are a few top level folders currently, and I may be adding more:
  * Robot-Project starts with a blank command and control LabVIEW robot project.
  * Dashboard-Project starts with a blank LabVIEW Dashboard project.
  * Shared holds code that is used by other projects.
  * Support starts empty and holds a number of projects which are not directly run in competition, but are used tangentially, for example: to generate an auto-routine. Any files created by these projects will be saved in the project's folder. 

## Branching and Workflow on this Repository
This project shall follow the following workflow:

The master branch is considered the stable branch of this project. It may only be updated via pull request from dev, and then only with Mentor approval. Merges onto the master branch should always be "fast forward merges" meaning that no merging what so ever is required, newer commits are simply copied onto the branch.

The dev branch is the main working branch. It may only be updated by pull request from uncontrolled branches.

For regular development each developer shall create a "feature branch" this is a branch named in the convention: "feature/name" or "bugfix/name". These are for new features and for bugfixes, respectively.

When work starts on a new feature, its branch will be made off of the latest version of dev, and all development will occur on the branch. When the feature is considered ready, it will be merged onto the dev branch. When merging, automatic merging, LV Merge tool merging, or simply copying and pasting of code fragments may be necessary.

## Issue Management
This repository shall use the GitHub issue tracker. New issues will be opened, and can be attached to a new branch or an existing branch. only when the branch is merged to dev (after a pull request) will the issue be closed.
