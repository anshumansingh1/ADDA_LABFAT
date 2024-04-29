# ADDA_LABFAT

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [QUESTION](#question)
  - [Scenario:](#scenario)
  - [Task:](#task)
- [STEPS](#steps)
  - [1) Create a repository (preferably public)](#1-create-a-repository-preferably-public)
  - [2) Add the TOC Generator action from marketplace. Steps are as follows:](#2-add-the-toc-generator-action-from-marketplace-steps-are-as-follows)
  - [3) For the external action to do modifications to our readme file we will need to provide it access to our repo by providing a ADDA_ACCESS_TOKEN. Which can be done as follows:](#3-for-the-external-action-to-do-modifications-to-our-readme-file-we-will-need-to-provide-it-access-to-our-repo-by-providing-a-adda_access_token-which-can-be-done-as-follows)
  - [4) Add the ADDA_ACCESS_TOKEN to the repo's Secrets](#4-add-the-adda_access_token-to-the-repos-secrets)
  - [5) Now we are good to go. The TOCs must be getting generated upon PUSH](#5-now-we-are-good-to-go-the-tocs-must-be-getting-generated-upon-push)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# QUESTION

Implement a CI/CD pipeline with the following real-world scenario:

## Scenario 20MIC0026: 

You're writing documentation using Markdown files.

## Task: 

Create a workflow that runs on push to any branch and uses an action like actions/markdown-toc to automatically generate a table of contents for your documentation.

# STEPS

## 1) Create a repository (preferably public)
## 2) Add the [TOC Generator](https://github.com/marketplace/actions/toc-generator) action from marketplace. Steps are as follows:
## 3) For the external action to do modifications to our readme file we will need to provide it access to our repo by providing a ADDA_ACCESS_TOKEN. Which can be done as follows:
## 4) Add the ADDA_ACCESS_TOKEN to the repo's Secrets
## 5) Now we are good to go. The TOCs must be getting generated upon PUSH
