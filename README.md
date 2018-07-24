# Project planning repo
- feature requests
- bugs
- user issues
- etc.. 

## Is My Thing a Epic (a.k.a. Feature) ?

Here are a few rough heuristics.

An epic is anything for which *any* of the following applies:

- would be part of release notes
- a blog post could be written about it after the release of the Platform
- requires multiple parties/repos participating to complete (backend, webapp, UX, API,...)
- needs significant effort or changes the platform in a significant way (ex. something that would take 10 person-weeks to implement, introduce or redesign a system component, or introduces API changes)
- impacts the UX or operation of the Platform substantially so that users would need guidance on how to take advantage of it

It is unlikely an epic if it is:

- adding/fixing a  test
- refactoring code
- performance improvements, which are only visible to users as faster API operations, or faster control loops
- adding error messages or events

These examples should probably be tracked directly in the repo where the code change is happening.


***

# To suggest a new feature or dataset for inclusion

- [Search the existing issues](https://github.com/opentargets/roadmap/issues) to see if the feature has already been suggested. Make sure you look at closed issues too.
- If no similar issue exist, [create a new issue](https://github.com/opentargets/roadmap/issues/new). Please be as descriptive as possible. In particular, it should describe what the value for a Open Targets Platform user should be.
- Add the `QUESTION` label to the issue.
- If you are suggesting a new data source, please also add the label `DATASOURCE` to the issue

Once you have done this, please await review and some consensus building from the Open Targets team or directly on github from other users.

# It's a good suggestion. How do I physically put it in the roadmap?
*The piece below is intended for the Open Targets dev team or any code contributors.*

Thanks for wanting to add a feature to Open Targets!  You will be responsible for guiding your feature through completion, and asking the right people for approvals.  

Use the following process when an issue or suggestion has already been discussed within the Open Targets team or on the issue tracker and some consensus has been reached that that the problem you are trying to solve is worth solving at this time.

To put a new feature on the roadmap:

1. create a new issue in this repository
2. add the `FEATURE` label
3. reference previous issues or suggestion if applicable. This will allow the person who originated the suggestion to keep track of progress.
4. Fill the template (**description is the absolute minimum requirement**)
