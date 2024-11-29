
## Summary (Summarize the bug encountered concisely)

    During new project creation, creation of new blank project is labeled as "Create black project" instead of "Create blank project"

## Steps to reproduce     

   Navigate to https://gitlab.com/projects/new#blank_project
   Notice label "Create black project"

## What is the current bug behavior?

    Label for creating blank project is "Create black project"

## What is the expected correct behavior?

    Label for creating blank project should be "Create blank project"
     
## Relevant logs and/or screenshots

[comment]:![](https://i.imgur.com/GchRTmC.png)

![Image info](../Image/Bug_Project_create_blank.png)
      

## Possible fixes

    Change word 'black' in html element holding label for navigating to new blank project creation to 'blank'


## Whom do you report/ Assign To/ Tags

      /label ~bug ~reproduced ~needs-investigation 
      /cc @project-manager 
      /assign @qa-tester

## Priority

    Trivial.

      
