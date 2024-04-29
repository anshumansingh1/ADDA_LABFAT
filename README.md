# ADDA_LABFAT

# ANSHUMAN SINGH
# 20MIC0026
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
    - [a) Goto your account Settings > Developer Settings > Personal access tokens > Tokens (classic)](#a-goto-your-account-settings--developer-settings--personal-access-tokens--tokens-classic)
    - [b) Create a ACCESS_TOKEN giving PUSH access](#b-create-a-access_token-giving-push-access)
    - [c) Copy the secret key, we will need it later](#c-copy-the-secret-key-we-will-need-it-later)
  - [4) Add the ADDA_ACCESS_TOKEN to the repo's Secrets](#4-add-the-adda_access_token-to-the-repos-secrets)
    - [a) Goto repo's Setings > Security > Secrets and variables > Actions > New repository secret](#a-goto-repos-setings--security--secrets-and-variables--actions--new-repository-secret)
    - [b) Add the new repo secret with name ADDA_ACCESS_TOKEN](#b-add-the-new-repo-secret-with-name-adda_access_token)
  - [5) Now we are good to go. The TOCs must be getting generated upon PUSH](#5-now-we-are-good-to-go-the-tocs-must-be-getting-generated-upon-push)

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
### a) Goto your account Settings > Developer Settings > Personal access tokens > Tokens (classic)
### b) Create a ACCESS_TOKEN giving PUSH access
### c) Copy the secret key, we will need it later
## 4) Add the ADDA_ACCESS_TOKEN to the repo's Secrets
### a) Goto repo's Setings > Security > Secrets and variables > Actions > New repository secret
### b) Add the new repo secret with name ADDA_ACCESS_TOKEN
## 5) Now we are good to go. The TOCs must be getting generated upon PUSH
