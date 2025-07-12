[![Deploy static content to Pages](https://github.com/LakshmiSathvika21/static-portfolio-webpage/actions/workflows/static.yml/badge.svg)](https://github.com/LakshmiSathvika21/static-portfolio-webpage/actions/workflows/static.yml)
Domain 1: Author and maintain workflows (40%)

Section-1 : Work with events that trigger workflows

**Configure workflows to run for one or more events**

1. on: push
2. specify branches
   on: 
    push:
     branches:
       - main

**Configure workflows to run for scheduled events**

1.on: 
  schedule:
    - cron: '*/5 * * * *'  #Runs every 5 minutes.

**Configure workflows to run for manual events**

1. on:
     workflow_dispatch:

2. Inputs

3. on: 
  workflow_dispatch:
    inputs: 
      ENV:
        description: ENV NAME
        default: hi

**Configure workflows to run for webhook events**


