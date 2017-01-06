Use this template when an issue or suggestion has already been discussed within the opentargets team or on the issue tracker and some consensus has been reached that
  that the problem you are trying to solve is worth solving at this time.

BEFORE YOU CLICK CREATE ISSUE:

- Put a 2-3 sentence description of your feature under the **Description** heading below.
- Delete from the top of this text down to the **Description** heading.
- Read the text below.

Thanks for wanting to add a feature to Open Targets!  You will be responsible for guiding
your feature through completion, and asking the right people for approvals.  

Large features typically go through three stages: [Alpha, Beta, and Stable]
Each stage requires various approvals from various teams (UX, infrastructure, data-pipeline, webapp). Features require several releases
to reach Stable.


** Delete from here to top of input box before creating issue so that issue creation emails will be informative.**

# [ ] Description

**Add description here**
Think of it as the blog post you would write once the feature is released on the Open Targets platform


# Progress Tracker

- [ ] Design & Prototyping
    - [ ] Write a draft of the documentation
      - During development keep a doc up-to-date about the desired experience of the feature and how someone can try the feature in its current state. Think of it as the README of your new feature and a skeleton for the docs to be written before the Open Targets release. -       - [ ] Paste link to Google Doc: **DOC-LINK**
    - [ ] Design Proposal.  
    This goes under [design-proposals](https://github.com/opentargets/features/tree/master/design-proposals).  Doing a proposal as a `.md` file and as a PR allows line-by-line commenting.  
      - [ ] Paste link to design proposal PR here: **PROPOSAL-NUMBER**
    - [ ] Decide which repo(s) this feature's code will be checked into.  **REPO-NAME**
    
    Plan for branch.targetvalidation.org:
    - [ ] Write (code + **tests** + docs). Paste all commit, issues or PR numbers here:  **ALL-PR-NUMBERS**
      - [ ] **Code should have a feature tag to be disabled by default.**   
      - [ ] branch name here: **branch**
      - [ ] Minimal testing
      - [ ] Minimal docs
      - [ ] if on webapp, test a deployment on k8
       
- [ ] Beta
  - [ ] merge code from branch above to master
  - [ ] Testing is sufficient for beta
  - [ ] User docs with tutorials
        - *Updated walkthrough / tutorial* in the docs repo: kubernetes/kubernetes.github.io
        - cc `@kubernetes/docs` on docs PR
        - **cc `@kubernetes/feature-reviewers` on this issue** to get approval before checking this off
  - [ ] Thorough API review
    - **cc `@kubernetes/api`**
- [ ] Stable
  - [ ] docs/proposals/foo.md moved to docs/design/foo.md 
        - **cc `@kubernetes/feature-reviewers` on this issue** to get approval before checking this off
  - [ ] Soak, load testing 			
  - [ ] detailed user docs and examples
    - **cc `@kubernetes/docs`**
    - **cc `@kubernetes/feature-reviewers` on this issue** to get approval before checking this off

*FEATURE_STATUS is used for feature tracking and to be updated by `@kubernetes/feature-reviewers`.*
**FEATURE_STATUS: IN_DEVELOPMENT**

More advice:

Design
   - Once you get LGTM from a *`@kubernetes/feature-reviewers`* member, you can check this checkbox, and the reviewer will apply the "design-complete" label.
 
Coding
  - Use as many PRs as you need.  Write tests in the same or different PRs, as is convenient for you.
  - As each PR is merged, add a comment to this issue referencing the PRs.  Code goes in the http://github.com/kubernetes/kubernetes repository,
        and sometimes http://github.com/kubernetes/contrib, or other repos.
  - When you are done with the code, apply the "code-complete" label.
  - When the feature has user docs, please add a comment mentioning `@kubernetes/feature-reviewers` and they will
        check that the code matches the proposed feature and design, and that everything is done, and that there is adequate
        testing.  They won't do detailed code review: that already happened when your PRs were reviewed.
        When that is done, you can check this box and the reviewer will apply the "code-complete" label.

Docs
  - [ ] Write user docs and get them merged in.
  - User docs go into http://github.com/kubernetes/kubernetes.github.io.
  - When the feature has user docs, please add a comment mentioning `@kubernetes/docs`.
  - When you get LGTM, you can check this checkbox, and the reviewer will apply the "docs-complete" label.

