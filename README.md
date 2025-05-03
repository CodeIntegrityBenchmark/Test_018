# Test_018
This project is part of a benchmark / test suite used to check the different git histories created through different development processes. The test suite is meant to be processed by SPHA-Code-Integrity.

## Textual Description
Expected Commits against integrity rules :
* Initial Commit.
* Initial Commit On The Feature-1 Branch.
* Commit Updating ReadMe on Main Branch.
* Second Commit On the Feature-1 Branch.
* Feature-1 into Main merge commit.
* Final Readme Update Commit On The Main Branch.

## Changes Made In This Repo

* Create a feature-1 branch from main and make a commit on that branch.
* Create a second commit on the main branch.
* Create a feature-2 branch based on the main branch and make a commit on the feature-2 branch
* Make a commit on the feature-1 branch.
* Make a commit on the main branch.
* Merge the feature-1 branch with the main branch without PR.
* Make a commit on the feature-2 branch.
* Make a commit on the main branch.
* Update the feature-2 branch with the expected results JSON.
* Now merge the feature-2 branch with the main branch using a PR.
