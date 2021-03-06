DecentCMS
=========

DecentCMS aims at being a decent CMS written in Node.
Its design principles are inherited from Drupal and Orchard CMS.

State
-----

The current state of DecentCMS is: naked.

The system can handle very simple sites, in a runtime-only fashion.
There is no dashboard yet.

All code is subject to change and refactoring.

Features
--------

The following features are implemented:

* Module system, with scoped dependency injection and automatic
  detection and loading of services.
* Themes
* Multi-tenancy
* Navigation menus
* Content type system
* Widgets
* Express compatibility
* File-based content store
* Markdown
* Template overloading
* Code-based asynchronous view engine
* Dust-based asynchronous view engine
* Localization base infrastructure
* Tokens
* Logging (using Winston)

Future features include:

* Document database as the content store
* Documentation site
* Localization implementation
* Dashboard
* Authentication
* Installer

Road map
--------

The road map is determined by me, based on what I think are the most
urgent features, on what my customers ask me to build, and on user
and contributor feedback.

Near future milestones are:

* First publicly accessible web site running DecentCMS
* Authentication and basic dashboard infrastructure
* Documentation and community site running DecentCMS

Installation
------------

There is an experimental installation procedure for the moment:

* Install Node.js
* npm install -g grunt-cli
* Clone the repository
* From the root of the clone, npm install
* From the root of the clone, grunt install
* Create a web site or clone an existing one under sites/default
  (for example from [this sample site][decent-consulting-site]).

You can then run the server: node server, and navigate to localhost:1337.

Otherwise, you can manually install by cloning the repository,
adding a sites/default folder (for example from
[this sample site][decent-consulting-site]), and then `npm install`
from the root and from every single module and theme folder.

Does this project take contributions?
-------------------------------------

Yes, please.

  [decent-consulting-site]: https://github.com/DecentCMS/DecentConsulting