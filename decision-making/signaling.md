# Signaling

### Environments

**Production**: The environment configured to host the final release version of a product targeting end users. It is optimized for security and performance. It is hosted on a live server. It requires alerted and urgent support. It is data-critical. Therefore, its data is backed up regularly. It also involves risk management and disaster recovery. The production environment is configured to show friendly errors to end users.

**Staging**: The environment configured to host the release candidate of the application after declaring a code freeze. It targets project manager/owner alongside the development team to agree upon the scope of the release candidate. It involves quality assurance and also the development team to do the final fixes and final furnishing before releasing to production. The best practice is to mimic the production environment by using the latest data available from a live DB copied from the production environment. Normally, the staging environment is only accessible by the internal team and stakeholders, therefore, it is either secured on a public server or published on an intranet environment if all stakeholders can access a local network. The staging environment is configured to show medium or full technical errors.

**Development**: The private environment configured by a single developer on his machine to check his/her own work during a development cycle, normally, called a sprint in a scrum environment. The development environment is configured to show full technical errors.

or smaller companies \(it's not clear how big yours is\), three environments \(dev, stage, production\) are common. Larger companies will often have a QA environment between dev and stage.

These normally break down as follows:

dev: Working code copy. Changes made by developers are deployed here so integration and features can be tested. This environment is rapidly updated and contains the most recent version of the application.

qa: \(Not all companies will have this\). Environment for quality assurance; this provides a less frequently changed version of the application which testers can perform checks against. This allows reporting on a common revision so developers know whether particular issues found by testers has already been corrected in the development code.

staging: This is the release candidate, and this environment is normally a mirror of the production environment. The staging area contains the "next" version of the application and is used for final stress testing and client/manager approvals before going live.

production: This is the currently released version of the application, accessible to the client/end users. This version preferably does not change except for during scheduled releases. 

### Signaling and screening games

![](../.gitbook/assets/image.png)

