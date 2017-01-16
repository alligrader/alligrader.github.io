---
title: Roadmap
---

# Roadmap for the Independent Project

- [x] ~~Learn Go (Daniel)~~
- [ ] Virtualize Kubernetes on Vagrant (Robbie)
- [ ] Extract configuration to environment variables (Robbie)
- [ ] Nice to have: switch the default shell to Fish in the Linux box (Robbie)
- [ ] Nice to have: Speed up Vagrant boot and provision time (Robbie)
- [ ] Nice to have: Set up a CI tool (Robbie)

- [ ] Set up an EventWatcher for GitHub events / hooks (Daniel) --> Goes into the autograder
- [ ] Set up tests for the event watcher (Robbie)
- [ ] Document how to use GitHub integrations (Robbie)
- [ ] Write functions to launch Kubernetes pods (Daniel)
- [ ] Find a way to pass data into the pods --> so that you can give it the API key or the repo ref. (Robbie or Daniel)
- [ ] Our Jobs repo needs a main function. This function builds all of the tasks, reads in the right information from the environment, and then executes the Job by walking the tree. It needs to read from the environment a) the repo name b) the access token c) the git ref (Daniel)
- [ ] Tasks: 
    - [ ] Read proper environment variables and inject them into the ctx. (Daniel)
    - [ ] Execute findbugs (Daniel)
    - [ ] Execute checkstyle (Daniel)
    - [ ] fetch the code from github (Daniel)
    - [ ] publish the results to GH (Daniel)
    - [ ] **optional:** change the deployment status (Daniel)
- [ ] Write the Dockerfile and build script (Rake -t version:latest) for the Job: FROM scratch ADD binary (Daniel)

- [ ] Research how to do JWT Authentication with OAuth (Robbie)
- [ ] Build the media types for the user profiles (Robbie)
- [ ] Build the database model for user profiles (Robbie)
- [ ] Build media types for the Findbugs configuration (Connor)
- [ ] Marshall Findbugs configuation into an XML file and store as a Blob in the database (Robbie)
- [ ] Build media types for the Checkstyle configuration (Connor)
- [ ] Marshall Checkstyle configuation into an XML file and store as a Blob in the database (Robbie)

- [ ] Learn React / Redux (Connor)
- [ ] Build sign-in component (Connor)
- [ ] Style index page (Connor)
- [ ] Build home page component (Connor)
- [ ] Create `New bug profile` component (Connor)
- [ ] Create `Edit bug profile` component  (Connor)
- [ ] Write `Delete bug profile` function (Connor)
- [ ] Create `View profile` component (Connor)
- [ ] Create `View all profiles` component (Connor)
- [ ] Create `Settings` component (Connor)
- [ ] Create `add new project` component (Connor)
- [ ] Create `view all projects` component (Connor)
- [ ] Create `view single project` component (Connor)
- [ ] Write `destroy project` function (Connor)
- [ ] Create `edit project` component (Connor)
