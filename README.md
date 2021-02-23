
<!-- README.md is generated from README.Rmd. Please edit that file -->

A series of meetups about data pipelines with the package
“[targets](https://docs.ropensci.org/targets/)”.

## Syllabus

### Motivation

[Meet Will
Landau](https://github.com/2DegreesInvesting/ds-incubator/issues/70).

### Walkthrough

Setup a minimal targets project from scratch.

Objectives:

-   Setup a file “\_targets.R” and explore its
    [structure](https://books.ropensci.org/targets/walkthrough.html#file-structure).

-   Try common functions:

    -   `tar_script()`.
    -   `tar_edit()`.
    -   `tar_glimpse()`.
    -   `tar_make()`.
    -   `tar_visnetwork()`.
    -   `tar_objects()`.
    -   `tar_read()`.

-   Create a report using targets.

-   Understand the benefit.

### Functions

This meetup adapts the examples shown in the “Functions” chapter of
targets [manual](https://books.ropensci.org/targets/). It covers how to
refactor a data science project, moving from a workflow based on a
sequence of scripts to a workflow based on a pipeline of functions.

Objectives:

-   Explore an analysis structured as a sequence of scripts.
-   Make and use our own targets.
-   Report multiple analyses with the same superset of targets.
-   Transform code chunks into functions.
-   Report the analysis as using targets.
-   Make and use targets from the package targets.

### Target cues

This meetup covers the rules that mark a target as outdated. It explores
the helpfile of
[`tar_cue()`](https://docs.ropensci.org/targets/reference/tar_cue.html).
After this session you will be more able to predict when `tar_make()`
will either skip or run a target, and to set the options that trigger
the behavior you want.

Objective:

-   Understand the
    [details](https://docs.ropensci.org/targets/reference/tar_cue.html#details)
    of
    [`tar_cue()`](https://docs.ropensci.org/targets/reference/tar_cue.html).

### Best practices

This meetup covers selected topics from the chapter [Best
Practices](https://books.ropensci.org/targets/practices) of target’s
manual.

Objectives:

-   Understand how to define good targets.
-   Understand how to ignore or depend on changes in R packages.

### Next

The rest of the series will likely cover these topics:

-   [Target
    factories](https://wlandau.github.io/targetopia/contributing.html#target-factories).
-   Debugging.

We’ll follow [targets’ manual](https://books.ropensci.org/targets/) but
loosely.
