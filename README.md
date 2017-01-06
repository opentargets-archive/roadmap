# Feature Tracking and Backlog

Feature tracking repo for Open Targets releases

This repo only contains issues. These issues are umbrellas for new features to be added to Open Targets. A feature can take one to multiple releases to complete. 

## Is My Thing a Feature?

Here are a few rough heuristics.

A feature is anything that:

- would be part of release notes
- a blog post could be written about after its release 
- requires multiple parties/repos participating to complete (backend,webapp,ux,api,...)
- needs significant effort or changes the platform in a significant way (ex. something that would take 10 person-weeks to implement, introduce or redesign a system component, or introduces API changes)
- impacts the UX or operation of the platform substantially so that users would need guidance on how to take advantage of it

It is unlikely a feature if it is:

- adding/fixing a  test
- refactoring code
- performance improvements, which are only visible to users as faster API operations, or faster control loops
- adding error messages or events

These examples should probably be tracked directly in the repo where the code change is happening.


***

# To suggest a new feature or dataset for inclusion

- [Search the existing issues](https://github.com/opentargets/features/issues) to see if the feature has already been suggested. Make sure you look at closed issues too.
- If no similar issue exist, [create a new issue](https://github.com/opentargets/features/issues/new). Please be as descriptive as possible. In particular, it should describe what the value for a Open Targets Platform user should be.
- Add the `question` label to the issue.
- If you are suggesting a new data source, please also add the label `datasource` to the issue

Once you have done this, please await review and some consensus building from the Open Targets team or directly on github from other users.

# It's a good suggestion. Can we put in the roadmap?
This piece is intended for the OpenTargets dev team and any code contributors.

- Create a new issue, using the [feature template](https://github.com/opentargets/features/blob/master/FEATURE_TEMPLATE.md)
- Follow the guidelines in the template
- Then head to the [roadmap](https://github.com/orgs/opentargets/projects/3) and move it to the backlog (at least).
- At our monthly planning meeting we will decide if it can be moved from the backlog to another column.
