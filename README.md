# Roadmap repository
- feature requests
- enhancement requests


## Is My Thing a Epic (a.k.a. Feature) ?

Here are a few rough heuristics.

An epic is anything for which *any* of the following applies:

- would be part of release notes
- a blog post could be written about it after the release of the Platform
- requires multiple parties/repos participating to complete (backend, webapp, UX, API,...)
- needs significant effort or changes the platform in a significant way (ex. something that would take 10 person-weeks to implement, introduce or redesign a system component, or introduces API changes)
- impacts the UX or operation of the Platform substantially so that users would need guidance on how to take advantage of it

It is unlikely an epic if it is:

- adding/fixing a test
- refactoring code
- performance improvements, which are only visible to users as faster API operations, or faster control loops
- adding error messages or events

These examples are tracked directly in the product repo where the code change is happening e.g. 

https://github.com/opentargets/platform/issues

or 
https://github.com/opentargets/genetics/issues

and therefore, should be reported in the appropriate repository in the first instance.


***

# To suggest a new feature or dataset for inclusion

- [Search the existing issues](https://github.com/opentargets/roadmap/issues) to see if the feature has already been suggested. Make sure you look at closed issues too.
- If no similar issue exist, please email your request with a specific use case to elaine@ebi.ac.uk (Platform Project Manager).
- Alternatively, please open an issue in the https://github.com/opentargets/roadmap/issues and assign the label "Kind: Question" and importantly assign to ElaineMcA.

Please be as descriptive as possible. In particular, suggestions should describe what the value for an Open Targets Platform user should be and where in the platform you would expect this feature or enhancement to appear.

- If you are suggesting a new data source, do not open an issue here!  Please use the following link to submit your request with context/ details: http://bit.ly/ot-suggest-data-form

Once you have done this, please await review and some consensus building from the Open Targets team or directly on github from other users.

# It's a good suggestion. How do I physically put it in the roadmap?
*The piece below is intended for the Open Targets dev team or any code contributors.*

Thanks for wanting to add a feature to Open Targets!

Once confirmed as prioritised and part of the roadmap, the issue will be elevated to EPIC status within the repository and updated accordingly by the Project Manager as detailed below:

1. create a new issue in this repository
2. add the `FEATURE` or "ENHANCEMENT'label
3. reference previous issues or suggestions where applicable. This will allow original suggestions to be tracked if/when grouped under broader epic topics.
4. Suggestions raised will be triaged by the OT core team and prioritised in collaboration with consortium partners.

