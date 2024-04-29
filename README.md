# ADDA_LABFAT

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [QUESTION](#question)
  - [Scenario: You're writing documentation using Markdown files.](#scenario-youre-writing-documentation-using-markdown-files)
  - [Task: Create a workflow that runs on push to any branch and uses an action like actions/markdown-toc to automatically generate a table of contents for your documentation.](#task-create-a-workflow-that-runs-on-push-to-any-branch-and-uses-an-action-like-actionsmarkdown-toc-to-automatically-generate-a-table-of-contents-for-your-documentation)
- [STEPS](#steps)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# QUESTION

Implement a CI/CD pipeline with the following real-world scenario:

## Scenario: 

You're writing documentation using Markdown files.

## Task: 

Create a workflow that runs on push to any branch and uses an action like actions/markdown-toc to automatically generate a table of contents for your documentation.

# STEPS

## 1) Create a repository (preferably public)
## 2) Add the [TOC Generator](https://github.com/marketplace/actions/toc-generator) action from marketplace. Steps are as follows:
## 3) For the external action to do modifications to our readme file we will need to provide it access to our repo by providing a ADDA_ACCESS_TOKEN. Which can be done as follows:
## 4) Add the ADDA_ACCESS_TOKEN to the repo's Secrets
## 5) Now we are good to go. The TOCs must be getting generated upon PUSH
