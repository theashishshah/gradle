# Starter pipeline
# Start with a minimal pipeline that you can customize to build and deploy your code.
# Add steps that build, run tests, deploy, and more:
# https://aka.ms/yaml

trigger:
- master

pool:
  name: Default

steps:
- script: echo My Gradle Application
  displayName: 'Run a one-line script'
- script: gradle build
  displayName: 'Building the gradle application'
- script: gradle run
  displayName: 'Running gradle application'
