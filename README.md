# java-library-template

[![Java CI](https://github.com/thriving-dev/java-library-template/actions/workflows/1.pipeline.yml/badge.svg)](https://github.com/thriving-dev/java-library-template/actions/workflows/1.pipeline.yml)
[![Maven Central](https://img.shields.io/maven-central/v/dev.thriving.oss/java-library-template.svg)](https://central.sonatype.com/artifact/dev.thriving.oss/java-library-template)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
[![Javadoc](https://img.shields.io/badge/JavaDoc-Online-green)](https://thriving-dev.github.io/java-library-template/javadoc/current)


### Considered
- https://github.com/ncipollo/release-action 
- 

### Tasks
- [ ] gh actions
  - [x] env vars required
  - [x] build + test
  - [x] intTest step
  - [x] release
  - [x] publish to maven central
  - [x] javadoc -> gh pages
    - [x] generate root folder index.html listing subfolders (tags + current) ??
  - [x] renovate
  - [x] codeql > trivy
  - [x] migration action
  - [ ] ? protect 'release' via environment > approvers? https://youtu.be/w_37LDOy4sI?t=230
- [x] script to rename group, lib, package name
  - [x] java packages
  - [x] gradle group 
  - [x] gradle lib name
  - [x] maven central link + badge
- [x] add badges
- [ ] docs
  - [ ] features
  - [ ] todos after create from template
    - [ ] required PAC -> `CI_GITHUB_TOKEN`
    - [ ] secrets for GPG sign + publish to Maven Central
    - [ ] migration
    - [ ] enable gp pages deploy
    - [ ] license
    - [ ] branch protection
    - [ ] artifact maven publish details (license, developers)
    - [ ] enable + configure renovate app
  - [ ] pipeline
  - [ ] add renovate
  - [ ] release process
  - [ ] register sona / maven central
  - [ ] codeql & security
  - [ ] recommended branch protection rules
    - [ ] main branch
    - [ ] PRs
    - [ ] ? protect 'release' via environment > approvers? https://youtu.be/w_37LDOy4sI?t=230
- [ ] blog
  - [ ] introduce, usage example + demo
  - [ ] gradle project, plugins, multi-project
  - [ ] gh actions, workflows
  - [ ] publish to maven central
  - [ ] javadoc
  - [ ] renovate (> vs. depandabot?)
  - [ ] trivy vulnerability scan ('codeql')
  - [ ] Issue & PR Templates


