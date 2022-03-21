---
layout: default
title: Getting started
parent: Git
grand_parent: Clever Code
nav_order: 
has_children: false
---
# Getting started with Git

1. Download and install Git:
    - Windows: https://git-scm.com/download/win
    - Linux: https://git-scm.com/download/linux
2. Make life easier for yourself and install a GUI 
    - Could be Github Desktop: https://desktop.github.com/ 
    - Alternatives: https://git-scm.com/downloads/guis
3. Github user (if you do not already have one)
    - Two options:
        - Make a new user/use existing personal user with personal email, add `@NILT.com` mail to it
        - Make a new userwith `@NILT.com` mail.
4. Create a new repository (repo) and play around.
    - Go to github, create repository (Can also be done from the desktop, with e.g. Github Desktop)
    - `clone` the repo to your computer using github desktop
    - Create some files, `commit` changes along the way
        - A commit is a check point, you will always be able to go pack to here
    - Done making changes? `Push` your changes
    - Collaborating with others? Do forget to `fetch` and `pull` new changes first.
        - There might be `merge conflicts`!
            - Happens when two people have edited the same thing between "checking in" i.e. commiting, pushing and pulling
        - Solve the merge conflict, by deciding what should happen in the places both people have edited.
        - After solving, commit the changes!
5. When you feel ready, try to:
    - Make a new `branch`
        - This is a copy of the project at the moment.
        - Changes can be made here in parallel with the original branch or other branches (the *master* or *main* branch)
          without affecting each other
    - Done making changes on you branch? Make a `pull request` (PR)
        - This will merge changes back into the main branch
            - If there are merge conflicts, wait with the pull request, 
              and pull from main into your branch first ("update from main" on Github desktop),
              solve the conflicts, and then make the pull request.
        - Other people can review you pull request, before it is merged.