# MyBit-Npm.template
📑 A template for MyBit repositories that build pull requests with CircleCI, deploy w/Travis and push to NPM + Github


# Introduction

The idea is to use this repository whenever you want to create a ES6 ready npm package that is automatically built
and deployed by CircleCI and Travis. We use two CI systems to allow CircleCI build public forks, and Travis to only
build local ones.

# Setup

- Download this repository, and push it to your local setup
- Change the `package.json` to fit your project name and build procedures
- Go to https://circleci.com and setup your project to be build by CircleCI
