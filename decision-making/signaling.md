# Signaling

### Environments

or smaller companies \(it's not clear how big yours is\), three environments \(dev, stage, production\) are common. Larger companies will often have a QA environment between dev and stage.

These normally break down as follows:

dev: Working code copy. Changes made by developers are deployed here so integration and features can be tested. This environment is rapidly updated and contains the most recent version of the application.

qa: \(Not all companies will have this\). Environment for quality assurance; this provides a less frequently changed version of the application which testers can perform checks against. This allows reporting on a common revision so developers know whether particular issues found by testers has already been corrected in the development code.

staging: This is the release candidate, and this environment is normally a mirror of the production environment. The staging area contains the "next" version of the application and is used for final stress testing and client/manager approvals before going live.

production: This is the currently released version of the application, accessible to the client/end users. This version preferably does not change except for during scheduled releases. 

### Signaling and screening games

![](../.gitbook/assets/image.png)

