# Now *that's* what I call *Awesome Python Packages*

![project-status](https://img.shields.io/badge/Status-%20Under%20Construction-yellow.svg)

> *Yes*! This is not a dream!
> You have stumbled upon yet *another* "awesome" list of python packages!

<h2> Contents </h2>

- [🤩 Status: *awesome*](#-status-awesome)
  - [Development](#development)
    - [Static Analysis](#static-analysis)
    - [Refactoring](#refactoring)
- [👀 Status: *lookin' awesome*](#-status-lookin-awesome)
  - [Development](#development-1)
  - [Static Analysis/Testing/etc](#static-analysistestingetc)
- [❓ Status: *unknown*](#-status-unknown)
- [🫡 Status: *was awesome*](#-status-was-awesome)

## 🤩 Status: *awesome*
>
> I *know* that these are awesome, because I use(d) them myself!

### Development

#### Static Analysis

- [`ruff`](https://github.com/astral-sh/ruff) - make code look good and fix those dumb mistakes past-me made (and future-me will make - these dudes are terrible!).
  - can be used as a pre-commit hook
  <!-- - ![essential](https://img.shields.io/badge/-Essential-black.svg) -->
- [`mypy`](https://github.com/python/mypy) - to make sure those type annotations are not just evil tricks to fool maintainers.
  - can be used as a pre-commit hook
  <!-- - ![essential](https://img.shields.io/badge/-Essential-black.svg) -->

#### Refactoring

- [`flynt`](https://github.com/ikamensh/flynt) - convert ugly old *%-format* strings as well as those `.format(...)` strings into beautiful `f-strings` 😮‍💨
  - can be used as a pre-commit hook

## 👀 Status: *lookin' awesome*
>
> These all definitely *look* awesome - but looks can be deceiving! Future me must be so excited to try all of them and find out the truth! (I have been waiting for him to do so for a while now, though...)
>
#### Development

- [`hatch`](https://hatch.pypa.io/latest/) - extensible project manager; yay! another thingsy-ma-bobs that requires me to throw a bunch of stuff that cost me blood, sweat, tears, and sleepless nights *out the window* so that I can see if it actually does anything significantly better. And I will probably have learn a bunch of stuff too to get it to work. *Yay!*
  - [`hatch-fancy-pypi-readme`](https://github.com/hynek/hatch-fancy-pypi-readme)

#### Static Analysis/Testing/etc

- [`pytest-watch`](https://github.com/joeyespo/pytest-watch) - a zero-config CLI tool that runs pytest, and re-runs it when a file in your project changes. It beeps on failures and can run arbitrary commands on each passing and failing test run.
- [`beartype`](https://github.com/beartype/beartype) - you are confident with your type annotations? Well, I guess nothing speaks against bringing those type-checks into production! 👍
  - [`pytest-beartype`](https://github.com/beartype/pytest-beartype) - propably a great starting point to see if `beartype` is for you (or your codebase)
- [`plum`](https://github.com/beartype/plum) - *"an implementation of multiple dispatch that is Pythonic, yet close to how Julia does it."* This really looks like a good way to tidy up codebases that were initially written in times where type annotations were not a thing yet. And where a parameter must allow for multiple types for whatever reason and you want to avoid a bunch of `if`-statements (which you always do).

## ❓ Status: *unknown*
>
> I don't even know if these *look* awesome, they could be malware for all I know! (But they probably aren't. Probably.)
>

- [`boltons`](https://github.com/mahmoud/boltons) - looks like a random assortment of miscellaneous stuff, various what-nots, and other such bizness
- [`typer`](https://github.com/tiangolo/typer) - a library for building CLI applications based on Python type hints... I think? seems like it could be one of those things that is *from the author, for the author*, i.e. built around a *very* specific way of thinking about/doing stuff. Or maybe it's teh goat. I dunno. Future me will have to try it out sometime.

## 🫡 Status: *was awesome*
>
> *Oh Oh!* 🚨 Personal Opinion Alert! 🚨 These packages were awesome (and probably still are), but either I have found something that I like better, or they were abandoned/are kaput/took an arrow to the knee/suffered some other unfortunate fate.

- [`flake8`](https://github.com/pycqa/flake8) - I think my grandpa is still using it, but I have moved on to `ruff`. Nothing about it is *bad* or *wrong*, but I just prefer things that are, well, *better* 😈.
  - can be used as a pre-commit hook
