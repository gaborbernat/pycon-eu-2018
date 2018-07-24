# Details
Bernat Gabor works at Bloomberg LP as a software engineer and will be giving a talk about trying to standardize testing tools in Python.

In this talk, Bernat will introduce tox, an open source tool with the bold vision of standardizing testing. From a CIs point of view, testing contains much more than just unit and/or integration tests; other things like code style checks, packaging, testing under various versions of Python, and checking that documentation still generates, are just as important. Things quickly start to spiral out of control once you add into the mix that there are many tools and ways to accomplish each of these tasks. In this talk, we will learn how tox tries to abstract away all this complexity, how to easily run CI tests on your local machine, and how one can use this tool inside your CI frameworks to ensure high quality and easily maintainable packages.