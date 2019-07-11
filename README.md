[<img src="https://sourcerer.io/assets/avatar/smarie" width="100" height="100" />](https://sourcerer.io/smarie)

# OVERVIEW
This file is an attempt to give you an overview of what you can find in my github account.

 * [Python](#python)
 * [Rapidminer](#rapidminer)
 * [Java / OSGi](#java--osgi)
 * [Misc](#misc)

In addition, I try to contribute with code or features/issues to great open source projects out there, such as [decorator](https://github.com/smarie/decorator), [scikit-learn](https://github.com/scikit-learn/scikit-learn), [pytest](https://github.com/pytest-dev/pytest), [pytest-profiling](https://github.com/manahl/pytest-plugins), [liblinear](https://github.com/cjlin1/liblinear) and [libsvm](https://github.com/cjlin1/libsvm), [pycharm](https://youtrack.jetbrains.com/issues)...

## Python

### Basics

 * [getversion](https://github.com/smarie/python-getversion/) is a library to get the version of a given package (work in progress)
 * [makefun](https://smarie.github.io/python-makefun) is a library to dynamically generate functions.
 * [decopatch](https://smarie.github.io/python-decopatch) makes it easy to write decorators.
 * [mini-lambda](https://smarie.github.io/python-mini-lambda) is a library to write simple lambda functions without `lambda x:` prefix and with string conversion capability. 
 * [valid8](https://smarie.github.io/python-valid8/) is a validation library with various entrypoints including function and class decorators
 * [autoclass](https://smarie.github.io/python-autoclass/) provides tools to write classes more easily. It is similar to `attrs` or *PEP557 data classes*

### Persistence

 * [yamlable](https://smarie.github.io/python-yamlable/) is a thin wrapper of PyYaml to easily add the yaml capability to your classes
 * [parsyfiles](https://smarie.github.io/python-parsyfiles) is a declarative parsing framework based on PEP484 type hints. One of my first python projects, please be tolerant ;)

### Tests

 * [pytest-steps](https://smarie.github.io/python-pytest-steps) helps you to create step-wise / incremental tests in `pytest`.
 * [pytest-cases](https://smarie.github.io/python-pytest-cases) is a tool to separate test functions from test cases data in `pytest`.
 * [pytest-harvest](https://smarie.github.io/python-pytest-harvest/) helps you collect fixtures and artifacts created during your `pytest` tests execution. Quite handy to create applicative benchmarks.
 * [pytest-patterns](https://smarie.github.io/pytest-patterns/) is not a library, but a repository of examples. In particular you will find here an example concerning how to create data science benchmarks.

### Multiprocessing, Parallel computing & Networking

 * [spawny](https://smarie.github.io/python-spawny) is a utility to launch python code in a separate process, possibly using another python executable/environment.
 * [azml-client](https://smarie.github.io/python-azureml-client) is a client for web services deployed with Microsoft AzureML Studio.

### HMI

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

