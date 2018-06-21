# Gerrit release tools

This repository contains tools to support Gerrit release management. The
tools can be used standalone, independent of the gerrit branch checked out.

## Prerequisites

It is assumed that [pip](https://pypi.org/project/pip/) and
[pipenv](https://docs.pipenv.org/) are installed.

## Installation

Installation is as simple as cloning the repository:

```
  git clone https://gerrit.googlesource.com/gerrit-release-tools
```

and then installing the dependencies with `pipenv`:

```
  cd gerrit-release-tools
  pipenv install
```

## Usage

To use the tools the environment must be activated:

```
  pipenv shell
```

Refer to the individual tools' help for further details.
