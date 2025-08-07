# DevOps-Course

Welcome everyone, welcome to DevOps Course. This repository contains informations, labs, homeworks, projects and lessons specific to your course.

## Schedule
| - | Days | Time | 
| --- | ------------- | ------------- | 
| Class | Sun - Thurs  | 4PM - 8pm  | 


## Unit 01 \(Git & GitHub \)

| Topics |
| :--- |
| <ul> <li>Git Basics</li> <br> <li>Git Branches</li> <br> <li>Git Merge and Rebase</li> <br> <li>Git Remotes</li> </ul> |



## Unit 02 \(Docker & Docker Compose \)

| Topics |
| :--- |
| <ul> <li>Docker Images</li> <br> <li>Docker Containers</li> <br> <li>Docker Volumes</li> <br> <li>Docker Networking</li> <br> <li>Building Images with Docker</li> <br> <li>Docker Compose</li></ul> |

## Unit 03 \(CI/CD using GitHub Actions \)

| Topics |
| :--- |
| <ul> <li>CI/CD Concept</li> <br> <li>CI/CD Tools Exploring</li> <br> <li>Bash Scripting</li>  <br> <li>GitHub Actions</li> </ul> |


## What We Expect From You
### Graduation Requirements
* Complete and submit all labs.
* Maintain consistent attendance.

### Additional Expectations
* Be present.
* Contribute constructively.
* Work hard.
* Ask questions.
* Be supportive.
* Talk to us.


| Section | Lessons | Labs | Homeworks & Additional Resources |
|:-|:--------|:------|:-----|
| 1.1  |  <ol><li> [Introduction](https://docs.google.com/presentation/d/19GdFplivDOu9-S8jYZV8pLZ5xoSAxD3vW9KsHhWCCFY/edit?usp=sharing) </li> <li> Git Overview </li> <li> [Version Control Systems](https://www.atlassian.com/git/tutorials/what-is-version-control) </li> <li> [Install Git](https://www.atlassian.com/git/tutorials/install-git) </li> </ol>|  |<ol><li> [Intro to Git Course](https://satr.codes/course/nindivqslr/view) </li>|
| 1.2  |  <ol><li> [Basic commands:](https://www.atlassian.com/git/tutorials/setting-up-a-repository) init, add, commit, log, status, diff, stash, .gitignore, tag, config </li> <li> [Git Branches](https://www.atlassian.com/git/tutorials/using-branches): git branch, checkout </li> <li>[Git Merge](https://www.atlassian.com/git/tutorials/using-branches/git-merge): git merge, fast forward, three way merge, conflicts</li>  <li> [Git Merge and Rebase:](https://www.atlassian.com/git/tutorials/merging-vs-rebasing) rebase vs. merge </li></ol>  | <ol><li> [Git Merge Lab](https://satr.codes/course/UFsXqimdgm/session/c0ff923b-d304-4189-acee-af36ca3261ec/view) </li> <li> [Git Rebase Lab](https://satr.codes/course/vZnxaKXPzw/session/26c3eec4-0bb9-4a16-a90a-4c9bd47ad348/view) </li>  <li> [Git Rebase Lab 2](https://satr.codes/course/vZnxaKXPzw/session/2c08d677-c4e6-4d35-b1e4-3841bf773ee0/view) </li></ol> | <ol><li> [Git Branches and Merge Course](https://satr.codes/course/UFsXqimdgm/view) </li> <li> [Git Rebase Course](https://satr.codes/course/vZnxaKXPzw/view) </li></ol>|
| 1.3  |  <ol> <li> [Deep Dive:](https://www.atlassian.com/git/tutorials/resetting-checking-out-and-reverting) reset, revert and checkout </li> <li> [Git Remote:](https://www.atlassian.com/git/tutorials/syncing) clone, pull, push, fork, pull request </li> <li>[Git Project](https://drive.google.com/file/d/1ZOAgFFYAXe0Uek7KQGHVGWncetJxnOyZ/view?usp=sharing)</li></ol>| <ol> <li> [Git Remote Lab](https://satr.codes/course/QpuMhOuMhW/session/ce9acb7a-e4f6-4a80-857d-b6c7de898d94/view)</li> | <ol><li> [Git Remote Course](https://satr.codes/course/QpuMhOuMhW/view) </li>  <li> [Review Git Course](https://satr.codes/course/ZlKLfufzmW/view) <li></li> [Git Cheat Sheet](https://drive.google.com/file/d/1TqoOIS9zFlT_HuwZeWESXiiEh1NQ3THi/view?usp=sharing)|
| 2.1  | <ol><li> Virtualization vs. Containerization </li><li> [Docker and Docker Components Overview](https://docs.docker.com/get-started/docker-overview/) </li> <li> [Docker Images Overview](https://docs.docker.com/get-started/docker-concepts/the-basics/what-is-an-image/) </li><li> [Docker Containers Overview](https://docs.docker.com/get-started/docker-concepts/the-basics/what-is-a-container/) </li><li> [Docker Volumes Overview](https://docs.docker.com/engine/storage/volumes/) </li><li> [Docker Networking Overview](https://docs.docker.com/engine/network/) </li><li> [Docker Setup](https://www.docker.com/get-started/) </li><li> Docker Images and Containers in action: <br> Docker Basic commands -> pull, run, ls, exec, exit, attach, kill, rm </ol>| <ol><li> [Lab](https://satr.codes/course/RWuHfOReeA/session/2d5a80d1-59f0-432d-80f2-9c0adda84066/view)</li></ol> | <ol><li> [Play with Docker Environment](https://labs.play-with-docker.com/?_gl=1*mj4rto*_gcl_au*MTAzMjk1MDg0My4xNzIzNjIyNzEw*_ga*NjAyODM3NjcwLjE2OTgwNDUyNjI.*_ga_XJWPQMJYHQ*MTcyNjQ3OTg5Mi4zOC4wLjE3MjY0Nzk4OTIuNjAuMC4w) </li><li> [Intro to Docker Course](https://satr.codes/course/RWuHfOReeA/view) </li><li> [Docker Cheat Sheet](https://drive.google.com/file/d/1AWkYysalX4G8hedj6pzW0IP26NOAk9Qb/view?usp=sharing) </li></ol>|
| 2.2  |  <ol><li> [Dockerfile](https://docs.docker.com/build/concepts/dockerfile/) </li><li> Core Concepts:  build, tags, size</li> <li>[Multi-stage build](https://github.com/vercel/next.js/blob/canary/examples/with-docker/Dockerfile)</li> </ol> | <ol> <li>[Practice COPY instruction](https://dockerlabs.collabnix.com//beginners/dockerfile/lab4_dockerfile_copy.html)</li> <li>[Practice ENTRYPOINT instruction](https://dockerlabs.collabnix.com/beginners/dockerfile/Dockerfile-ENTRYPOINT.html)</li> <li>[Practice WORKDIR instruction](https://dockerlabs.collabnix.com/beginners/dockerfile/WORKDIR_instruction.html)</li> <li>[Practice RUN instruction](https://dockerlabs.collabnix.com/beginners/dockerfile/Lab%237_RUN_instruction.html)</li> <li>[Practice ARG instruction](https://dockerlabs.collabnix.com//beginners/dockerfile/arg.html)</li> <li>[Lab: Dockerfile with Python Script](https://dockerlabs.collabnix.com/beginners/dockerfile/lab_dockerfile_python.html)</li></ol> | <ol><li> [YAML Course](https://satr.codes/course/dhyKzxwfvT/view) </li><li> [Build and Share Docker Images Course](https://satr.codes/course/sZvvvDJlNy/view) </li></ol> |
| 2.3  |  <ol> <li> Docker Deep Dive:  [OS Arch](https://docs.docker.com/build/building/multi-platform/), [caching](https://docs.docker.com/build/cache/), [inspect](https://docs.docker.com/reference/cli/docker/inspect/), [login](https://docs.docker.com/reference/cli/docker/login/), [push](https://docs.docker.com/reference/cli/docker/image/push/) </li> </ol> | <ol><li>[Containerize Flask App](https://github.com/faialotaibi/flask-app)</li><li>[Containerize Laravel App](https://github.com/faialotaibi/laravel-app)</li></ol>|  |
| 2.4  |  <ol> <li> [Docker Volumes in action](https://docs.docker.com/engine/storage/volumes/) </li><li> [Docker Networking in action](https://docs.docker.com/engine/network/) </li> </ol> | <ol><li> [Volumes Lab](https://dockerlabs.collabnix.com/beginners/volume/managing-volumes-via-docker-cli.html) </li><li> [Volumes Lab](https://dockerlabs.collabnix.com/beginners/volume/creating-volume-mount-from-dockercli.html) </li><li>[Networks Lab](https://dockerlabs.collabnix.com/beginners/using-docker-network.html)</li></ol>  |  |
| 2.5  | <ol><li> [Multi Container Application with Docker Example](https://github.com/faialotaibi/multi-container-app) </li><li> [Multi Container Application with Docker Compose](https://docs.docker.com/compose/intro/features-uses/) </li><li> [Docker and Docker Compose Project](https://drive.google.com/file/d/1ZkR4HC3XU-x2G1pGcKlZiYLud5kO90OS/view?usp=sharing) </li></ol> |  <ol><li> [Lab](https://dockerlabs.collabnix.com/intermediate/workshop/DockerCompose/Create_first_docker-compose_file_with_ngnix_and_mysql.html) </li></ol> | <ol><li> [Docker Compose Installation](https://dockerlabs.collabnix.com/intermediate/workshop/DockerCompose/How_to_Install_Docker_Compose.html) </li></ol>|
| 3.1  |  <ol><li>[Introduction to CI/CD](https://circleci.com/ci-cd/)</li><li>Overview of CI/CD Tools <ol><li>[Jenkins](https://www.jenkins.io/)</li> <li>[CircleCI](https://circleci.com/)</li>  <li>[GitLab CI/CD](https://docs.gitlab.com/ee/ci/)</li> <li>[GitHub Actions](https://github.com/features/actions)</li></ol> <li>[Pipeline Designing Techniques](https://www.browserstack.com/guide/building-ci-cd-pipeline)</li> <li>[Overview of GitHub Actions](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)  <ol><li>Core components of GitHub Actions (Workflows, Jobs, Steps, Actions)</li></ol></li>  <li>[Creating and Setting Up Your First Workflow](https://docs.github.com/en/actions/writing-workflows/quickstart)</li>  <li>[GitHub Marketplace](https://github.com/marketplace?type=)</li></ol> </ol> | <ol><li> [Research Task](https://satr.codes/course/DDIqRSoiua/session/b491c393-e6bc-49c1-895d-40db6ada4905/view)</li>  <li>[Pipeline Design Lab](https://satr.codes/course/qTpabYcFrh/session/82c16616-63bb-44c3-aaaf-13f9b3ba8f99/view)</li> </ol> | <ol><li>[CI/CD Course 1](https://satr.codes/course/DDIqRSoiua/view)</li><li>[CI/CD Course 2](https://satr.codes/course/qTpabYcFrh/view)</li> <li>[GitHub Actions Course 1](https://satr.codes/course/CTOIXnlPmi/view)</li> <li>[GitHub Actions Course 2](https://satr.codes/course/OdSRnxBBSf/view)</li></ol> |
| 4.1  |  <ol><li>[GitHub workflow syntax](https://docs.github.com/en/actions/writing-workflows/workflow-syntax-for-github-actions)</li><li>[Basics of Bash Scripting](https://github.com/faialotaibi/DevOps-Bootacmp/blob/main/week03/bash-scripting.md)</li> <li>[Flask App (with Test Job)](https://github.com/faialotaibi/flask-github-actions)</li> <li>[C App (with Build Job)](https://github.com/faialotaibi/github-actions-c)</li>  </ol> | <ol><li>[GO App (with Build Job)](https://github.com/faialotaibi/github-actions-go)</li> <li>[Typescript App (with Build and Test)](https://github.com/Alja7dali/bun-dockerized)</li></ol> | <ol> <li>[Bash Course 1](https://satr.codes/course/SeKcdRBnEj/view)</li> <li>[Bash Course 2](https://satr.codes/course/rwzGgfjiUQ/view)</li> <li>[Bash Course 3](https://satr.codes/course/PjZicrpjiz/view)</li> <li>[Bash Course 4](https://satr.codes/course/PFzwaZCOTV/view)</li> <li>[Bash Course 5](https://satr.codes/course/xKFakzkzVs/view)</li> <li>[Bash Course 6](https://satr.codes/course/UqoNYCliHF/view)</li> <li>[Bash Practice 1](https://satr.codes/course/PjZicrpjiz/session/dd5477e1-6739-4d1d-9637-c818d5184be1/view)</li><li>[Bash Practice 2](https://satr.codes/course/PFzwaZCOTV/session/c022dee4-8b0c-4761-8e75-a2fcb825a274/view)</li> </ol>|
| 5  | <ol><li>[Final Project](https://github.com/faialotaibi/devops-course-final-project)</li></ol> |  |  |
