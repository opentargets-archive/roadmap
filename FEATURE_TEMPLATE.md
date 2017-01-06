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

# Description

**Add description here**


# Progress Tracker

- [ ] Alpha
    - [ ] Write and maintain draft quality doc
      - [ ] During development keep a doc up-to-date about the desired experience of the feature and how someone can try the feature in its current state. Think of it as the README of your new feature and a skeleton for the docs to be written before the Open Targets release. Paste link to Google Doc: **DOC-LINK**
    - [ ] Design Approval
      - [ ] Design Proposal.  This goes under [design-proposals](https://github.com/kubernetes/community/tree/master/contributors/design-proposals).  Doing a proposal as a PR allows line-by-line commenting from community, and creates the basis for later design documentation.  Paste link to merged design proposal here: **PROPOSAL-NUMBER**
      - [ ] Decide which repo this feature's code will be checked into. Not everything needs to land in the core kubernetes repo. **REPO-NAME**
      - [ ] Initial API review (if API).  Maybe same PR as design doc. **PR-NUMBER**
        -  Any code that changes an API (`/pkg/apis/...`)
        -  **cc `@kubernetes/api`**
      - [ ] Identify shepherd (your SIG lead and/or kubernetes-pm@googlegroups.com will be able to help you). **My Shepherd is:** _replace.me@replaceme.com_ (and/or GH Handle)
        -  A shepherd is an individual who will help acquaint you with the process of getting your feature into the repo, identify reviewers and provide feedback on the feature. They are _not_ (necessarily) the code reviewer of the feature, or tech lead for the area.
        -  The shepherd is _not_ responsible for showing up to Kubernetes-PM meetings and/or communicating if the feature is on-track to make the release goals. That is still your responsibility.
      - [ ] Identify secondary/backup contact point. **My Secondary Contact Point is:** _replace.me@replaceme.com_ (and/or GH Handle)
    - [ ] Write (code + tests + docs) then get them merged.  **ALL-PR-NUMBERS**
      - [ ] **Code needs to be disabled by default.**   Verified by code OWNERS
      - [ ] Minimal testing
      - [ ] Minimal docs
        - cc `@kubernetes/docs` on docs PR
        - **cc `@kubernetes/feature-reviewers` on this issue** to get approval before checking this off
        - New apis: *Glossary Section Item* in the docs repo: kubernetes/kubernetes.github.io
      - [ ] Update release notes
- [ ] Beta
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

