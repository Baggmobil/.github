# Welcome Baggmobilers

We are at an exciting juncture with a lot of unknowns in the horizon which can be both intriguing and overwhelming at the same time. This document hopes to be your guiding light in this quest towards success and should contain a brief overview of all our internal processes and other helpful resources.

> As we get into our rythm and streamline our work, feel free to add any information you may find useful for beginners here.

## Overview

- Each repository will represent an independent module
- All repositories will follow a similar template and contain the following:
  - A readme file that describes processes and workflows specific to that repo
  - A changelog file based on [Keepachangelog](https://keepachangelog.com/en/1.0.0/)
  - A documentation folder that contains all module specific details
  - A folder containing deployment information (eg. helm charts, kube manifests, ansible files etc.)
  - A folder with source files
  - A folder with test files (unit tests, integration tests)
- Project management will be done through org level projects in GitHub for now

### Active Projects

Due to limitations in GitHub projects, we will have one week sprints instead of the regular two that we have grown accustomed to. Sprints are referred to as _iterations_ in the following projects.

Feel free to take ownership of your individual modules/codebases and add tickets for upcoming work along with expected effort and start/end dates. This will help everyone get a quick glance of our current status through the _roadmap view_ in these projects and be aligned with their dependencies.

| Project | Description |
| --- | --- |
| [Sandstone](https://github.com/orgs/Baggmobil/projects/1) | Tracks the development status of our core product which includes the client facing mobile application and its backend |

### Active Repositories

| Repository | Description |
| --- | --- |
| [Org Profile](https://github.com/Baggmobil/.github) | Contains documentation shown in our GitHub org profile |
| [Sandstone](https://github.com/Baggmobil/sandstone) | Contains the codebase for our client-facing cross-platform mobile app |