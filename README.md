# GitLab Runner

This docker image is based on [sameersbn/gitlab-ci-runner](https://github.com/sameersbn/docker-gitlab-ci-runner).

It contains additionnal tools to support building your projects with various technologies:

  - NodeJS (nvm)
  - Ruby (rbenv)
  - Python (pyenv)
  - Java (jenv)
  - C/C++ (build-essential)

# Supported environments

## NodeJS

NodeJS support is provided through [nvm](https://github.com/creationix/nvm).

## Ruby

Ruby support is provided through [rbenv](https://github.com/sstephenson/rbenv).

## Python

Python support is provided through [pyenv](https://github.com/yyuu/pyenv).

## Java

Java support is provided through [jenv](http://www.jenv.be/);

## C/C++

C/C++ support is provided natively with [build-essentials](http://packages.ubuntu.com/fr/trusty/build-essential) from ubuntu:14.04