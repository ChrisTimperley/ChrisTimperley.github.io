---
layout: page
title: Software
permalink: /software/
---

### (Selected) Open Source Projects

* [**BugZoo**](https://github.com/squaresLab/BugZoo)<br/>
  A decentralised platform, built on top of [Docker](https://docker.com),
  for studying and sharing historical software bugs.
  It can be used for research on program testing, analysis and repair on existing bug datasets.
  It provides a [command-line interface](https://squareslab.github.io/BugZoo/cli.html),
  a [RESTlike API](https://github.com/squaresLab/BugZoo/blob/master/api-specification.yml),
  and [Python](https://squareslab.github.io/BugZoo/api.html) bindings.
  BugZoo currently supports a number of datasets, including
  ManyBugs and IntroClass,
  GenProg TSE 2012's dataset, and [ROBUST](https://github.com/robust-rosin/robust).
  Check out the docs to [add support for BugZoo to your bug dataset!](https://squareslab.github.io/BugZoo/contributing/bugs.html)
* [**Darjeeling**](https://github.com/squaresLab/Darjeeling)<br/>
  Darjeeling is a language-agnostic search-based program repair tool.
  Unlike other repair tools, such as GenProg, SPR, and Nopol,
  Darjeeling delegates the responsibility of generating patches,
  obtaining coverage, analyzing code, and executing tests to other services.
  Once those auxillary concerns are removed, what is left is a lightweight
  framework for composing and executing repair algorithms: Darjeeling.
* [**roswire**](https://github.com/ChrisTimperley/roswire)<br/>
  A Python library for static and dynamic analysis of Robot Operating System
  (ROS) applications.
  Given a Docker image containing a ROS application, roswire
  automatically discovering its types, packages, messages, service,
  actions, etc., and provides an interface for dynamically generating
  and interacting with instances of that application in the form of
  Docker containers (e.g., service calls, bag recording, topic publishing and
  subscribing, catkin builds, etc.).
* [**Wallace.jl.**](http://github.com/ChrisTimperley/Wallace)<br/>
  A high-performance dynamic framework for evolutionary computation, written in [Julia](http://julialang.org/). Achieves the performance of C++/Java tools, such as ECJ and Evolving Objects, whilst maintaining the simplicity and
  ease-of-use of dynamic-language-based tools, such as DEAP.
* [**Push.jl.**](http://github.com/ChrisTimperley/Push.jl)<br/>
  A Julia implementation of the [Push](http://faculty.hampshire.edu/lspector/push.html) programming language for (auto-constructive) evolutionary computation. Integrates with Wallace to perform high-performance PushGP in Julia.
* [**RubyREVAC.**](http://github.com/ChrisTimperley/RubyREVAC)<br/>
  A simple, but effective implementation of [Eiben and Nannen's REVAC (Relevance Estimation and Value Calibration)]() method for efficiently tuning meta-heuristic parameters, written in Ruby.


### (Selected) Closed Source Projects

* **Voyager (July 2011 - July 2013)**.<br/>
  A flexible cloud-based tool for performing financial analysis and anomaly detection, built using a variety of languages and tools,
  including Ruby, Rails, AngularJS, Python, EC2, MongoDB and Redis.
* **The Guild of Dark Knights**.<br/>
  An online massively multiplayer online role-playing game, set in Medieval
  Britain (and later in Late Medieval Europe and Near-Asia), where players assumed the role of a penniless
  bandit, and had to plunder, steal and battle their way to the rank of king.
  Hand-written in PHP, MySQL, HTML, Javascript and CSS, when I was 14 years old.
  At its peak, the game had over 50,000 registered users.
