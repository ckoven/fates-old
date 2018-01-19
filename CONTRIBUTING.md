# How to contribute

Thank you for considering contributing to the development of FATES. There are a few guidelines that we need contributions to follow.

## Read and Understand the FATES license:

https://github.com/NGEET/fates/blob/master/LICENSE.txt


## Getting Started

Those who wish to contribute code back FATES, must have those changes integrated through the developer repository NGEET/fates.  Changes that make it to public releases must go through this repository first, as well.  Here are some basic first steps.

* All developers should create a fork of the NGEET/fates repository into their personal space on github
* Each set of changes should have it's own feature branch that encapsulates your desired changes, following the conventions outlined here: https://github.com/NGEET/fates/wiki/Feature-Branch-Naming-Convention
* Follow the developer work-flow described here: https://github.com/NGEET/fates/wiki/FATES-Development-Workflow
* The work-flow will lead you eventually to submit a Pull-Request to NGEET/fates:master, please follow the template in the Pull Request and communicate as best you can if you are unsure how to fill out the text
* It is best to create an issue to describe the work your are undertaking prior to starting.  This helps the community sync with your efforts, prevents duplication of efforts, and science is not done in a vaccuum.
* Expect peers to interact, help, discuss and eventually approve your submission (pull-request)


## Things to Remember

* Make commits in logical units (i.e. group changes)
* Changes that are submitted should be limited to 1 single feature (i.e. don't submit changes to the radiation code and the nutrient cycle simultaneous, pick one thing)
* Check for unnecessary whitespace with `git diff --check` before committing
* We have no standard protocol for commit messages, but try to make them meaningful, concise and succinct.
* You will most likely have to test (see workflow above), see: https://github.com/NGEET/fates/wiki/Testing-Protocols


## Coding Practices and Style

Please refer to the FATES style guide: https://github.com/NGEET/fates/wiki/Coding-Practices-and-Style-Guide


## Trivial Changes

If changes are trivial, its possible testing will not be required, conversations via the Pull Request will address if tests are not needed

## Documentation

Yes please!  If you are creating new code, fixing existing code, anything.  Please add comments in the code itself.  Please also follow the style guide for comments.  Also, please create and/or modify wiki documentation on this stuff too.


## Additional Resources

* [General GitHub documentation](https://help.github.com/)
* [GitHub pull request documentation](https://help.github.com/articles/creating-a-pull-request/)
* [FATES Wiki](https://github.com/NGEET/fates/wiki)