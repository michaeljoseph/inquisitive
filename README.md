# inquisitive

[![Build Status](https://secure.travis-ci.org/michaeljoseph/inquisitive.png)](http://travis-ci.org/michaeljoseph/inquisitive)
[![Stories in Ready](https://badge.waffle.io/michaeljoseph/inquisitive.png?label=ready)](https://waffle.io/michaeljoseph/inquisitive) [![pypi version](https://badge.fury.io/py/inquisitive.png)](http://badge.fury.io/py/inquisitive)
[![# of downloads](https://pypip.in/d/inquisitive/badge.png)](https://crate.io/packages/inquisitive?version=latest)
[![code coverage](https://coveralls.io/repos/michaeljoseph/inquisitive/badge.png?branch=master)](https://coveralls.io/r/michaeljoseph/inquisitive?branch=master)

## Overview

Inquisitive

* features
* and stuff 

## Usage

Install `inquisitive`:

    pip install inquisitive

Then execute the sample cli:

   inquisitive

## Documentation

[API Documentation](http://inquisitive.rtfd.org)

## Testing

Install development requirements:

    pip install -r requirements.txt

Tests can then be run with:

    nosetests

Lint the project with:

    flake8 inquisitive tests

## API documentation

Generate the documentation with:

    cd docs && PYTHONPATH=.. make singlehtml

To monitor changes to Python files and execute flake8 and nosetests
automatically, execute the following from the root project directory:

    tdaemon -t py
