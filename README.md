# OVERVIEW
This file is an attempt to give you an overview of what you can find in my github account.

 * [Python](#python)
 * [Rapidminer](#rapidminer)
 * [Java / OSGi](#java--osgi)
 * [Misc](#misc)

## Python

### Basics

 * [mini-lambda](https://smarie.github.io/python-mini-lambda) is a library to write simple lambda functions without `lambda x:` prefix and with string conversion capability. 
 * [valid8](https://smarie.github.io/python-valid8/) is a validation library with various entrypoints including function and class decorators
 * [autoclass](https://smarie.github.io/python-autoclass/) provides tools to write classes more easily. It is similar to `attrs` or *PEP557 data classes*

### Persistence

 * [yamlable](https://smarie.github.io/python-yamlable/) is a thin wrapper of PyYaml to easily add the yaml capability to your classes

### Tests

 * [pytest-steps](https://smarie.github.io/python-pytest-steps) helps you to create step-wise / incremental tests in `pytest`.
 * [pytest-cases](https://smarie.github.io/python-pytest-cases) is a tool to separate test functions from test cases data in `pytest`.
 * [pytest-harvest](https://github.com/smarie/python-pytest-harvest) helps you collect fixtures and artifacts created during your `pytest` tests execution. Quite handy to create applicative benchmarks.

### Misc / exotic

 * [parsyfiles](https://smarie.github.io/python-parsyfiles) is a declarative parsing framework based on PEP484 type hints. One of my first python projects, please be tolerant ;)
 * [pyoad](https://smarie.github.io/python-object-as-daemon) is a tiny utility to launch a python object in a separate process, possibly using another python executable/environment.
 * [azml-client](https://github.com/smarie/python-azureml-client) is a client for web services deployed with Microsoft AzureML Studio.
 * [PyQt5-minimal](https://github.com/smarie/PyQt5-minimal) is a minimal version of the PyQt5 GPL package, so that you do not end up with a 80Mo-large distribution when freezing your application with cx_Freeze, py2exe or others. 

## Rapidminer

 * [octminer](https://github.com/smarie/java-octminer) is an extension for Rapidminer 5 to call octave scripts in a process
 * [matlab-miner]() is an extension for Rapidminer 5 to call matlab scripts in a process (available on demand)
 * RIP many other (10+) unpublished extensions for rapidminer 5: enrico, meteociel, unit tests, proxy tools, devtools, svn...

## Java / OSGi

This is **very old** stuff...

 * [soa4d-java-osgi-commons](https://github.com/smarie/java-soa4d-java-osgi-commons) common building blocks for java and OSGi projects, such as execution environments, adaptation of jsr support for embedded targets, etc. XML-related blocks sits in a separate project called "xml-java-osgi", below.
 * [xml-osgi](https://github.com/smarie/java-xml-osgi) a stack of packaged xml bundles for embedded OSGi 
 * [dpws4j](https://github.com/smarie/java-dpws4j) is a devices profiles for web services (now web services for devices) implementation in java
 * [osgi-dpwsdriver](https://github.com/smarie/java-osgi-dpwsdriver) is a wrapper of *dpws4j* for OSGi, mapping devices to proxy OSGi services.
 * [ws-management4j](https://github.com/smarie/java-ws-management4j)
 * [wsman-osgi](https://github.com/smarie/java-wsman-osgi)

## Misc

 * [Blync4CI](https://github.com/smarie/blync4CI) is an http daemon with a little REST interface to use blync lights for CI engines through an OpenWRT router
 * [develop-behind-proxy](https://github.com/smarie/develop-behind-proxy) is a tutorial to help you configure your development environment if you are located behind a network proxy
 * [envswitch](https://github.com/smarie/env-switcher-gui) is a tool to quickly change environment variables, able to save and restore profiles. It can be used for example to switch the environment variables for the network proxy (`http_proxy`, etc.), as explained in the develop-behind-proxy tutorial.

