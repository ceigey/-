# Hanashinarai
話し習い - Hanashinarai - Λαλ(ι)ομάθησις

Table of Contents
=================
* [Introduction](#introduction)
  * [Objective](#objective)
  * [Background](#background)
  * [Alternatives](#alternatives)
* [Architecture](#architecture)
* [Technologies](#technologies)
  * [Overview](#overview)
  * [UI](#ui)
  * [Pseudowiki](#pseudowiki)
  * [Interactive Lesson Definitions](#interactive-lesson-definitions)
  * [Misc](#misc)
* [License](#license)

## Introduction
### Objective
To create a decent, lightweight and relatively exentsible Language Learning Web App. In addition, to practice reactive web app design.

Lessons can have a written explanatory component and sets of interactive activities. The activities should cover a broad range of things, such as the typical variations on flashcards we often see in language learning apps, to conjugation and grammar challenges.

### Background
There have been many learning apps and programs available to people seeking to learn a language. Many have fallen by the wayside, such as Byki and Livemocha. At the moment, Duolingo is something of a de facto market leader, but Duolingo does not have an accessible backend, with the only way for new courses to be built via the incubator process. This has its own advantages.

However, for supporters of minority languages and conlangers, there is demand for something people can hack around with and deploy quite liberally. This hopefully can lead to something like that.

### Alternatives
*There are alternatives out there, I'm just not sure how many and how far ahead they are*...

## Architecture
Intended to be a front-end heavy app.

Client-side JavaScript manipulates DOM and generates pages on the fly. Lessons are loaded as JSON or other documents and used to generate an interactive lesson activity.

Lesson activity definitions (*apart from having a consistent name*) should come complete with all the information needed - e.g. points (*user-wide-xp? lesson-progression-points?*) the activity is worth, words shown to the learner, tips or at least pointers to tips, right and wrong answers, etc.

The language should possess something of a "dumb" dictionary for a given language, containing alternative forms and conjugations of a given word, etc. These should be user (teacher) definable and assumed to be structureless by nature from the programming side of things. For this reason, JSON would be quite helpful.

## Technologies
### Overview
### UI
* JavaScript -> Elm for reactive functional UI?
### Pseudowiki
* Maybe some sort of Markdown system for writing detailed lessons
### Interactive Lesson Definitions
* Possibly JSON?
### Misc
* JQuery is always helpful.
* Maybe Pug for HTML Templating because it's **[````Æ S Þ Ē T Y K````]**. But there should still be a clear separation of logic and templating, cf. [this link](http://www.workingsoftware.com.au/page/Your_templating_engine_sucks_and_everything_you_have_ever_written_is_spaghetti_code_yes_you).

## License
*To be updated*
