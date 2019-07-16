# Folder-based Authorization for Jenkins

[![Build Status](https://ci.jenkins.io/job/Plugins/job/folder-auth-plugin/job/master/badge/icon)](https://ci.jenkins.io/job/Plugins/job/folder-auth-plugin/job/master/)
[![Gitter](https://badges.gitter.im/jenkinsci/role-strategy-plugin.svg)](https://gitter.im/jenkinsci/role-strategy-plugin?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

This plugin adds an authorization strategy for Jenkins that works on Cloudbees' Folder plugin.
Permissions given to a user for a folder are inherited by all its children.

You can chat with us, share your feedback and ask questions on our [Gitter chat](https://gitter.im/jenkinsci/role-strategy-plugin).
We share the channel with the [Role Strategy Plugin](https://github.com/jenkinsci/role-strategy-plugin)
because this plugin also follows a similar, though simplified, 'role-based' model and was created to 
avoid the performance penalty of using regular expressions.