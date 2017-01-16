## Description
**What is the problem this feature would answer?**  
*Replace this text with a description here. Think of it as the 1-paragraph blog post you would write once the feature is released on the Open Targets platform*

### Design & Prototyping
#### Design proposal
**How are we going to solve the problem?**  
*Paste here google doc link or link to markdown file, if already written somewhere else*
 
#### Readme
**What does the solution look like?**  
During development of the feature, it's best to keep a README/documentation up-to-date.   
In it, sketch the architecture of the feature.  
Describe the desired experience of the feature and how someone can try the feature in its current state.  
Think of it as the README of your new feature and a skeleton for the docs to be written before the Open Targets release.  

*** 

## Progress Tracker
- [ ] Description complete
- [ ] Proposal drafted 
- [ ] This feature's code will be checked into:  *link to repo(s) here*
- [ ] README drafted *Paste here google doc link or link to markdown file, if not included as part of a PR already*

### Subtasks
*paste here the issue number of subtasks, if any*
 - [ ] subtask 1
 - [ ] subtask 2

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
