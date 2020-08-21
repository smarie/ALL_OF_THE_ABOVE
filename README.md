[<img src="https://sourcerer.io/assets/avatar/smarie" width="100" height="100" />](https://sourcerer.io/smarie)

# OVERVIEW
This file is an attempt to give you an overview of what you can find in my github account.

 * [Python](#python)
 * [Rapidminer](#rapidminer)
 * [Java / OSGi](#java--osgi)
 * [Misc](#misc)

In addition, I try to contribute with code or features/issues to great open source projects out there, such as [nox](https://github.com/theacodes/nox), [decorator](https://github.com/smarie/decorator), [scikit-learn](https://github.com/scikit-learn/scikit-learn), [pytest](https://github.com/pytest-dev/pytest), [pytest-xdist](https://github.com/pytest-dev/pytest-xdist), [pytest-profiling](https://github.com/manahl/pytest-plugins), [attrs](https://github.com/python-attrs/attrs/), [requests-oauthlib](https://github.com/requests/requests-oauthlib), [enforce](https://github.com/RussBaz/enforce), [typing-inspect](https://github.com/ilevkivskyi/typing_inspect), [stdlib-list](https://github.com/jackmaney/python-stdlib-list), [funcsigs](https://github.com/testing-cabal/funcsigs), [liblinear](https://github.com/cjlin1/liblinear) and [libsvm](https://github.com/cjlin1/libsvm), [pycharm](https://youtrack.jetbrains.com/issues)...

## Python

### Developer's Basics

 * [getversion](https://smarie.github.io/python-getversion/) is a library to get the version of any python package or module, reliably.
 * [makefun](https://smarie.github.io/python-makefun) is a library to dynamically generate functions.
 * [decopatch](https://smarie.github.io/python-decopatch) makes it easy to write decorators.

### Object-Oriented

 * [pyfields](https://smarie.github.io/python-pyfields/) helps you define fields in python classes, easily.
 * [mixture](https://smarie.github.io/python-mixture) provides a few interesting mixins for you to reuse (work in progress)
 * [autoclass](https://smarie.github.io/python-autoclass/) provides tools to write classes more easily. It is similar to `attrs` or *PEP557 data classes*

### Application tools

 * [mini-lambda](https://smarie.github.io/python-mini-lambda) is a library to write simple lambda functions without `lambda x:` prefix and with string conversion capability. 
 * [valid8](https://smarie.github.io/python-valid8/) is a validation library with various entrypoints including function and class decorators
 * [vtypes](https://smarie.github.io/python-vtypes/) allows you to create "validating types" able to validate both type and value with `isinstance`, in a simple and composable way.
 * [kopylog](https://smarie.github.io/python-kopylog/) (work in progress)
 
### Persistence

 * [jsoners]() (work in progress)
 * [yamlable](https://smarie.github.io/python-yamlable/) is a thin wrapper of PyYaml to easily add the yaml capability to your classes
 * [parsyfiles](https://smarie.github.io/python-parsyfiles) is a declarative parsing framework based on PEP484 type hints. One of my first python projects, please be tolerant ;)

### Build tools

 * [fprules](https://smarie.github.io/python-fprules) helps you create `make`-like file pattern rules easily, to be used for example in build tools such as `doit`.

### Tests

 * [pytest-pilot](https://smarie.github.io/python-pytest-pilot) Slice in your pytest test base thanks to powerful markers
 * [pytest-cases](https://smarie.github.io/python-pytest-cases) is a tool to separate test functions from test cases data in `pytest`.
 * [pytest-steps](https://smarie.github.io/python-pytest-steps) helps you to create step-wise / incremental tests in `pytest`.
 * [pytest-harvest](https://smarie.github.io/python-pytest-harvest/) helps you collect fixtures and artifacts created during your `pytest` tests execution. Quite handy to create applicative benchmarks.
 * [pytest-patterns](https://smarie.github.io/pytest-patterns/) is not a library, but a repository of examples. In particular you will find here an example concerning how to create data science benchmarks.

### Multiprocessing, Parallel computing & Networking

 * [spawny](https://smarie.github.io/python-spawny) is a utility to launch python code in a separate process, possibly using another python executable/environment.
 * [azml-client](https://smarie.github.io/python-azureml-client) is a client for web services deployed with Microsoft AzureML Studio.
 * [odsclient](https://smarie.github.io/python-odsclient/) is a client for OpenDataSoft API.

### HMI

 * [PyQt5-minimal](https://github.com/smarie/PyQt5-minimal) is a minimal version of the PyQt5 GPL package, so that you do not end up with a 80Mo-large distribution when freezing your application with cx_Freeze, py2exe or others. 

## Misc

 * [Blync4CI](https://github.com/smarie/blync4CI) is an http daemon with a little REST interface to use blync lights for CI engines through an OpenWRT router
 * [develop-behind-proxy](https://github.com/smarie/develop-behind-proxy) is a tutorial to help you configure your development environment if you are located behind a network proxy
 * [envswitch](https://github.com/smarie/env-switcher-gui) is a python GUI tool to quickly change environment variables, able to save and restore profiles. It can be used for example to switch the environment variables for the network proxy (`http_proxy`, etc.), as explained in the develop-behind-proxy tutorial.

## Rapidminer

This is **very old** stuff...

 * [octminer](https://github.com/smarie/java-octminer) is an extension for Rapidminer 5 to call octave scripts in a process. Downloaded 10k times from Rapidminer marketplace.
 * [matlab-miner]() is an extension for Rapidminer 5 to call matlab scripts in a process (available on demand)
 * RIP many other (10+) unpublished extensions for rapidminer 5: enrico, meteociel, unit tests, java scripting, proxy tools, devtools, svn...

## Java / OSGi

This is **very old** stuff, hosted at [SOA4D](https://forge.soa4d.org/) but listed here for reference.

 * [soa4d-java-osgi-commons](https://github.com/smarie/java-soa4d-java-osgi-commons) common building blocks for java and OSGi projects, such as execution environments, adaptation of jsr support for embedded targets, etc. XML-related blocks sits in a separate project called "xml-java-osgi", below.
 * [xml-osgi](https://github.com/smarie/java-xml-osgi) a stack of packaged xml bundles for embedded OSGi 
 * [dpws4j](https://github.com/smarie/java-dpws4j) is a devices profiles for web services (now web services for devices OASIS WS-DD) implementation in java
 * [osgi-dpwsdriver](https://github.com/smarie/java-osgi-dpwsdriver) is a wrapper of *dpws4j* for OSGi, mapping devices to proxy OSGi services.
 * [ws-management4j](https://github.com/smarie/java-ws-management4j)
 * [wsman-osgi](https://github.com/smarie/java-wsman-osgi)
