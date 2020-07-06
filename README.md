# Extending Elixir

This document is an experiment in response to a [thread][1] on [Elixir Forum][2]
about Elixir Language Design, extensibility and innovation.

In a [Smart Logic Podcast][3] at 54:30, Dave Thomas talks about his desire for
a native pipeline operator.  At 40:30 he talks about his desire for an elixir
component model described in his [2018 Empex Keynote][4].

The core Elixir language is 'done' ([watch][5] at 54:00) by virtue of the fact
that Elixir was designed to be an extensible language.

Given that we have an extensible language, how can we as a community do a
better job of encouraging experimentation?  What is the most effective way to
guide developers towards high value problems?  How can we give efficient
feedback to Elixir core for language tweaks that enable breakthru innovation?  

[1]: tbd
[2]: tbd
[3]: tbd
[4]: tbd
[5]: tbd

To get started, we have this document with a catalog of resources for Extending
Elixir:

1. [Problems](#Problems) - to describe language problems that we see in the
community

2. [Experiments](#Experiments) - to list Elixir experiments and language
prototypes done by developers

3. [Comparables](#Comparables) - sometimes we look to other languages or
frameworks for inspiration

4. [History](#History) - often it's useful to understand the thinking of people
who came before us

5. [Vision](#Vision) - sometimes people envision alternative computing models
that could inspire new ideas

Pull-requests welcome!

Possibly this material could be complemented with a Slack room or a forum
channel or a conference session.  Let's see if there is interest.

## Problems

| Problem              | Problem Impact             |
|----------------------|----------------------------|
| Boilerplate          | Productivity               |
| Composable_Pipelines | Composability, Maintenance |
| TBD                  | BigData                    |

### Boilerplate

Description:

GenServers require too much boilerplate.  

Impact:

References:

### Composable_Pipelines

TBD

### Independant_Components

TBD

## Experiments

| Repo                  | Summary              | Problems Addressed |
|-----------------------|----------------------|--------------------|
| [pragdave/jeeves][e1] |                      |                    |
| Witchcraft            | Composable Pipelines |                    |
| Jeeves                | TBD                  |                    |

## Comparables

| Language | Feature | Problems Addressed |
|----------|---------|--------------------|
| Haskell  | Monads  | TBD                |

## History

| Robert Virding |
| Joe Armstrong  |
| Carl Hewett    |

## Vision

| Carl Hewett | A global infrastrure |
