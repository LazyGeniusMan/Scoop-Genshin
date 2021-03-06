---
name: "Bug Report"
about: "I am facing some problems."
title: ""
labels: "bug"
---

<!--
  By opening this issue you confirm that you have searched for similar issues/PRs here already.
  Failing to do so will most likely result in closing of this issue without any explanation.
  Incomplete form details below might also result in closing of the issue.
-->

<!--
  If your app data is lost after update, likely it's because folder that contain user data in the app directory isn't set as persist folder in the app manifest.
  If this happen, please tell me what's the folder path that contain those user data when you create a new issue. It will help me a lot to fix it.
  As a temporary solution, you can go to `%userprofile%\scoop\apps\<app-name>\` and go to older version folder to recover your data and paste it in the new version folder.
-->

## Bug Report

**Package Name:** [name of package which has bug(s)]

### Current Behaviour

<!-- A clear and concise description of the behaviour. -->

### Expected Behaviour

<!-- A clear and concise description of what you expected to happen. -->

### Additional context/output

<!-- Add any other context about the problem here. If applicable, paste terminal output here to help explain. -->

### Possible Solution

<!--- Only if you have suggestions on a fix for the bug -->

### System details

**Windows version:** [e.g. 7, 8, 10]

**OS architecture:** [e.g. 32bit, 64bit]

**PowerShell version:** [output of `"$($PSVersionTable.PSVersion)"`]

**Additional software:** [(optional) e.g. ConEmu, Git]

#### Scoop Configuration
<!-- Can be found in  ~/.config/scoop/config.json -->

```json
//# Your configuration here
```
