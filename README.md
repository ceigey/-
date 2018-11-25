# Lalein
From Greek λαλεῖν, the infinitive of "to talk, chat".
A language learning and practice app system.

## Table of Contents
* [Introduction](#introduction)
  * [Background](#background)
  * [Objective](#objective)
  * [Alternatives](#alternatives)
* [Architecture](#architecture)
* [Technologies](#technologies)
* [License](#license)

## Introduction
### Background
There have been many language learning websites, programs and apps, some of which enjoy widespread popularity today, others of which have fallen by the wayside. Often, these have locked-down backends, mostly for quality control reasons.

However, for supporters of minority languages and conlangers, there is demand for something people can hack around with and deploy quite liberally. This hopefully can lead to something like that.

### Objective
To create a decent, lightweight and relatively exentsible Language Learning Web App. In addition, to web app design.

Lessons can have a written explanatory component and sets of interactive activities. The activities should cover a broad range of things, such as the typical variations on flashcards we often see in language learning apps, to conjugation and grammar challenges.

### Alternatives
*There are alternatives out there, I'm just not sure how many and how far ahead they are...*

## Architecture
Intended to be an SPA.

Lesson activity definitions (*apart from having a consistent name*) should come complete with all the information needed - e.g. points (*user-wide-xp? lesson-progression-points?*) the activity is worth, words shown to the learner, tips or at least pointers to tips, right and wrong answers, etc.

The language should possess something of a "dumb" dictionary for a given language, containing alternative forms and conjugations of a given word, etc. These should be user (teacher) definable and assumed to be structureless by nature from the programming side of things. For this reason, JSON would be quite helpful.

## Technologies
* PureScript
* Maybe some sort of Markdown system for writing detailed lessons
* JSON, YAML, TOML for lesson definitions

## License
*To be updated*
