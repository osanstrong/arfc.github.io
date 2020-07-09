---
layout: manual
title: Software Templates
subtitle: "A few tools and templates for building a software project"
permalink: /manual/guides/software_templates
---

Software projects are often intensely unique with specifications that far 
exceed the capabilities of a single template. However, there are some cases 
where a template can save a lot of time and overhead. This document will 
hopefully provide ARFC members with the individual tools to mix and match as 
they create software projects.

# Existing Templates
There are a couple open source templates that provide a high quality template 
that can be useful in software development, and if your project falls under the 
range of capabilities they have it can save you a lot of time by using them or 
adapting them to start your project.

## Shablona
[Shablona](https://github.com/uwescience/shablona) is a template repository that 
is designed for scientific python projects. The template comes with everything a 
small-scale project might need, and can be easily adapted for python based 
projects.

To get a sense of whether or not using the Shablona template is appropriate for 
the project, checkout the 
[example](https://github.com/uwescience/shablona/tree/master/examples) provided.

## Cookiecutter
[Cookiecutter](https://github.com/cookiecutter/cookiecutter) is not a template 
repository like Shablona, instead it is a command-line utility that
allows you to build a repository from a "pantry" of templates. This project has 
an extensive 
[Read the Docs](https://cookiecutter.readthedocs.io/en/1.7.2/index.html), and 
it's definitely worth a review before you decide. 

Additional documents that will give you a sense of whether or not to use this 
utility:
1. [Getting to Know Cookiecutter](https://cookiecutter.readthedocs.io/en/1.7.2/tutorial1.html) 
2. [Usage](https://cookiecutter.readthedocs.io/en/1.7.2/usage.html)
3. [Building a Cookiecutter](https://cookiecutter.readthedocs.io/en/1.7.2/first_steps.html)

# Software Project Parts
Even if neither of the above templates fit your requirements, there are still 
some pieces that might benefit your project. JOSS (The Journal of Open Source 
Software) has 
a useful [review checklist](https://joss.readthedocs.io/en/latest/review_checklist.html) 
for software that you should review before beginning your project even though 
this checklist was for reviewers and not creators. 

## Make Files
Makefile is a program building tool that operates with the make utility to compile or re-compile a program or process through a user-defined command in the command-line. They are extremely useful tools that make it a lot easier for contributors or reviewers to compile and run your project.

#### Resources:
- [Introduction](https://www.gnu.org/software/make/manual/html_node/Introduction.html)
- [Writing Makefiles](https://www.gnu.org/software/make/manual/html_node/Makefiles.html#Makefiles)
- [Tutorial](https://makefiletutorial.com/)

## CMake Files
CMake generates makefiles, similar Make or a makefile, except that it is much 
more compatible with C++, and it is designed to integrate across platforms, 
languages, or libraries.

#### Resources:
- [Overview](https://cmake.org/overview/)
- [Step-by-step Tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)
- [Wiki](https://gitlab.kitware.com/cmake/community/-/wikis/Home)

## Docker Files
A Dockerfile is a text file that contains commands that can be used from the 
command line to generate images. 
Like a makefile, docker build can automate a series of command line 
instructions. Several links have been 
provided as informational resources, and there exists a template file. 

Here is a 
[template dockerfile](https://gist.github.com/ju2wheels/3d1a1dfa498977874d03), 
which also has a lot of useful information on what different components do.

#### Resources:
- Information on [Dockerfiles](https://docs.docker.com/engine/reference/builder/)
- A [Quickstart Guide](https://docs.docker.com/get-started/)
- A [Best Practices Guide](https://docs.docker.com/develop/dev-best-practices/)

## Automated Testing
If you think this project may end up requiring multiple people or would benefit 
from a series of tests run on every commit, you might want to check out 
circleci. Circleci allows you to build automatic tests that can run in a couple 
ways, notably before every pull request. This functionality can take some time 
to develop, but if you expect multiple contributors or a lot of pull requests 
you might want to consider implementing tests like this.

#### Resources:
- [Getting Started](https://circleci.com/docs/2.0/hello-world/)
- [Tutorial](https://circleci.com/docs/2.0/tutorials/)
- [Examples](https://circleci.com/docs/2.0/sample-config/)

## Licensing
Every repository that is a part of the ARFC Github Organization should have some 
form of license. Choosing a license can seem like a very daunting task, but for 
many software projects a simple 
[BSD-3 Clause](https://spdx.org/licenses/BSD-3-Clause.html) will cover your whole
project. In the case that your project is more complicated than one license 
(meaning that you are using pieces under a different license), there are 
many ways you can address it. 

One suggestion is that you create separate directories for the code that is 
under the other license. In the separate directory, you can then include the 
license that covers the code in that directory. 

Another suggestion is that you add all the licenses to the docs 
folder and then indicate which files or directories are covered under the 
respective licenses in the README.md files (or in the file itself) in the 
directory covered by it.

There are many other ways to abide by differing licenses, the above are simply 
suggestions about how to go about it and should not be taken as legal advice. 
Ensure that, regardless of the method you use, you are abiding by the 
requirements of any software you are using or adapting.

#### Resources:
- [List of open source licenses](https://opensource.org/licenses/alphabetical)
- [What is copyleft?](https://opensource.org/faq#copyleft)
