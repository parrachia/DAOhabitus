# Git Based Governance

## Proposal: Git Based Governance

Governance is messy, Git is neat. So lets use it for that!

**Why?** See _"Why Git?"_ below. **What?** 2 Git repositories with all validated documentation, blank files for those yet to come + a kanban, somehow. **How?** Honestly I have no clue.

### Governance

> “\[If we consider governance:\] the process by which we attempt to establish \(and maintain/revoke\) the legitimacy of decisions, decision making processes, and related governance norms/expectations,”

We can conceive of many ways to establish the legitimacy of decisions. In some contexts, voting can play a critical role. In others, it’s not needed.[\*](https://www.tonysheng.com/voting-governance)

#### Decisions

> “Ultimately, a company’s value is just the sum of the decisions it makes and executes.”

**Simple decision-making process**

Prioritizes execution over deliberation. Empowering a team to execute comes with the risk of making more mistakes.

* First, we shall stabilish a [**simple decision-making process**](git-based-governance.md). 
* From which we [**engineer the memes**](git-based-governance.md) for a culture where the team does not second guess such decisions. 
* And underlying it all, we nurture a shared sense of [**values**](git-based-governance.md) that guide decisions. 

May this process provide guidance on how avoid unnecessary costs in low-stakes decisions and prioritize execution on all decisions.

**Structured decision-making framework**

Is only needed when there is lack of clarity about a decision that is _higher risk_. Higher risk can mean that the decision has long term implications or that it can be costly to unwind if the wrong decision is made.[\*](git-based-governance.md)

[A framework that offers structure](git-based-governance.md) to the ambiguous and high-risk decisions. Structure removes ambiguity around process and should lead to better decisions with lower overhead. The framework has three stages: **\(1\)** setting the parameters, **\(2\)** deliberation, and **\(3\)** decision.

* **Setting the parameters** is about describing what decision we’re making, who needs to make the decision, who is impacted, and when the decision needs to be made. [Proposal building](git-based-governance.md)
* **Deliberation** is voting on the options. [Loomio](git-based-governance.md)
* **Decision** documents the decision made, the rationale for the decision, and the plan to communicate the decision back to those impacted. _You are here_, this is literaly what this proposal is about.

If the decision is both ambiguous and high-stakes, we use the framework. If the decision is only ambiguous, the decision-maker can collaborate with a few people and make the call. And if the decision is neither ambiguous or high-stakes, the decision-maker should simply move forward. In all cases, communication to the team completes the decision.

**Communication is critical to the process.**

> A decision is not complete until all impacted by that decision are notified. if you'd never abandon a puppy, why abandon decisions outputs? Think about the puppies.

The decision-maker is accountable for determining the best format to deliver this communication. For example, if everybody is highly impacted, an email to all employees may be the best way to communicate the decision. If nobody is directly impacted today, an FYI in a slack channel and a note in a design doc may be sufficient.

#### Decisions outputs

What are they and where do they go after decisions have been made?

Documentation, Logs, notifications to impacted parties. Well, from now on, we should house them here in this neat piece of the cyberspace. A repository that can eas

### Why Git

[https://www.atlassian.com/git/tutorials/why-git](https://www.atlassian.com/git/tutorials/why-git)

Lets design our governance around git main traits:

* Distributed
* Colaboration oriented
* Fast \*\* Rapid prototyping 

#### Intention

## Dillinger

[![N\|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Dillinger is a cloud-enabled, mobile-ready, offline-storage, AngularJS powered HTML5 Markdown editor.

* Type some Markdown on the left
* See HTML in the right
* Magic

## New Features!

* Import a HTML file and watch it magically convert to Markdown
* Drag and drop images \(requires your Dropbox account be linked\)

You can also:

* Import and save files from GitHub, Dropbox, Google Drive and One Drive
* Drag and drop markdown and HTML files into Dillinger
* Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions that people naturally use in email. As [John Gruber](http://daringfireball.net) writes on the [Markdown site](http://daringfireball.net/projects/markdown/)

> The overriding design goal for Markdown's formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions.

This text you see here is _actually_ written in Markdown! To get a feel for Markdown's syntax, type some text into the left window and watch the results in the right.

#### Tech

Dillinger uses a number of open source projects to work properly:

* [AngularJS](http://angularjs.org) - HTML enhanced for web apps!
* [Ace Editor](http://ace.ajax.org) - awesome web-based text editor
* [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser done right. Fast and easy to extend.
* [Twitter Bootstrap](http://twitter.github.com/bootstrap/) - great UI boilerplate for modern web apps
* [node.js](http://nodejs.org) - evented I/O for the backend
* [Express](http://expressjs.com) - fast node.js network app framework [@tjholowaychuk](http://twitter.com/tjholowaychuk)
* [Gulp](http://gulpjs.com) - the streaming build system
* [Breakdance](http://breakdance.io) - HTML to Markdown converter
* [jQuery](http://jquery.com) - duh

And of course Dillinger itself is open source with a [public repository](https://github.com/joemccann/dillinger) on GitHub.

#### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```bash
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```bash
$ npm install --production
$ NODE_ENV=production node app
```

#### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| :--- | :--- |
| Dropbox | [plugins/dropbox/README.md](https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md) |
| Github | [plugins/github/README.md](https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md) |
| Google Drive | [plugins/googledrive/README.md](https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md) |
| OneDrive | [plugins/onedrive/README.md](https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md) |
| Medium | [plugins/medium/README.md](https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md) |
| Google Analytics | [plugins/googleanalytics/README.md](https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md) |

#### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing. Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```bash
$ node app
```

Second Tab:

```bash
$ gulp watch
```

\(optional\) Third:

```bash
$ karma test
```

**Building for source**

For production release:

```bash
$ gulp build --prod
```

Generating pre-built zip archives for distribution:

```bash
$ gulp build dist --prod
```

#### Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the Dockerfile if necessary. When ready, simply use the Dockerfile to build the image.

```bash
cd dillinger
docker build -t joemccann/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies. Be sure to swap out `${package.json.version}` with the actual version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on your host. In this example, we simply map port 8000 of the host to port 8080 of the Docker \(or whatever port was exposed in the Dockerfile\):

```bash
docker run -d -p 8000:8080 --restart="always" <youruser>/dillinger:${package.json.version}
```

Verify the deployment by navigating to your server address in your preferred browser.

```bash
127.0.0.1:8000
```

**Kubernetes + Google Cloud**

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)

#### Todos

* Write MORE Tests
* Add Night Mode

### License

MIT

**Free Software, Hell Yeah!**

