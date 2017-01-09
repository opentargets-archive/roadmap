Thanks for wanting to add a feature to Open Targets!  You will be responsible for guiding
your feature through completion, and asking the right people for approvals.  

Large features typically go through three stages: [Prototype, Beta, and Stable]
Each stage requires various approvals from various teams (UX, infrastructure, data-pipeline, webapp). Features require several releases
to reach Stable.

Use this template when an issue or suggestion has already been discussed within the opentargets team or on the issue tracker and some consensus has been reached that that the problem you are trying to solve is worth solving at this time.

## To put a new feature on the roadmap
You can either:
- create an issue
- create a new markdown `.md` file in [design-proposals](https://github.com/opentargets/features/tree/master/design-proposals) and use it to create a pull-request (with a new branch). The markdown file should sketch out i) what is it, ii) why it would be good to have and iii) what it would look like. Just paste this to begin:
```md
## what is it 

## why it would be good to have 

## what it would look like.
```

Both approaches work out since PR and Issues have very similar status in github. A PR has the added advantage that the team can comment line-by-line on your design proposal and other documentation.

**The text below should be the first comment of the issue or PR.**

***

## Description
**What is the problem this feature would answer?**  
*Replace this text with a description here. Think of it as the 1-paragraph blog post you would write once the feature is released on the Open Targets platform*
- [ ] Description complete

## Progress Tracker
### Design & Prototyping
#### Design proposal
**How are we going to solve the problem?**  
This goes under [design-proposals](https://github.com/opentargets/features/tree/master/design-proposals).  Start a new markdown file and use it to create the PR. Doing a proposal as a `.md` file and as a PR allows line-by-line commenting.  
- [ ] Proposal drafted *Paste here google doc link or link to markdown file, if not included as part of a PR already*
- [ ] This feature's code will be checked into:  *link to repo(s) here*
    
#### Readme
**What does the solution look like?**  
During development of the feature, it's best to keep a README/documentation up-to-date. This can also go in [design-proposals](https://github.com/opentargets/features/tree/master/design-proposals) if there is not a better place for it (eg. closer to the code).  
In it, sketch the architecture of the feature. Describe the desired experience of the feature and how someone can try the feature in its current state. Think of it as the README of your new feature and a skeleton for the docs to be written before the Open Targets release.
- [ ] README drafted *Paste here google doc link or link to markdown file, if not included as part of a PR already*

### Get to a prototype at branch.targetvalidation.org:
Write code + **tests** + docs. Isolate the work in feature branches. 
Use as many PRs as you need.  
Write tests in the same or different PRs, as is convenient for you. 
As each PR is merged, add a comment to this issue referencing the PRs.  

- [ ] Feature tag *Code should have a feature tag to be disabled by default.*
- [ ] branch name here: *branch*
- [ ] Minimal functional testing
- [ ] Minimal docs
- [ ] if on webapp, test a deployment on k8
       
### Push to Beta
- [ ] merge code from branch above to master. Make sure tests are passing and master is not breaking. (We are working on automate this as much as possible, but we are admittedly not quite there).
  **PULL request should be reviewed by 1-2 people at least**
- [ ] at least 1 week internal testing?
- [ ] received some feedback/input from users (eg. pharma scientist)

### Deploy
- [ ] in the release notes?
- [ ] documentation updated?		
- [ ] blog post?
- [ ] users that requested it originally informed?

## Make sure you can measure impact
As dev team we want to know if a new feature are succesful.
To do that we need to define metrics to assess the impact of each new feature we introduce to the platform

- [ ] metric identified 
- [ ] identify the one metric that matters (OMTM)
