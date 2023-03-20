---
title: Sample Presentation
---

class: center, middle

# Sample Presentation

How this example course setup works...

---

# Agenda

1. [Overview](#overview)
1. [Markdown](#markdown)
1. [Remark.js](#remark.js)
1. [GitHub](#github)
1. [GitHub Pages](#github-pages)
1. [GitHub Classroom](#github-classroom)
1. [Conclusions](#conclusions)

---

name: overview

# Overview

--

## Concept

This presentation includes notes on how this example course website, including these slides, was created.

--

- The contents are entirely written in [Markdown](#markdown) and stored on [GitHub](#github).

--

- The contents of this presentation are stored in the file named `slides`/`sample-presentation.md`.

--

- In fact, any Markdown file placed within the `slides` directory will automatically be converted into a presentation.

--

- Markdown documents placed outside of the `slides` directory will be displayed as regular web pages, e.g. the example [course schedule](../../) and [syllabus](../../syllabus/).

---

name: markdown

# Markdown

--

## Concept

Markdown is a simple text-based markup language that anyone can master.

- **widely-used** for writing documentation
- supported by a wide variety of software tools
- **easy** to learn
- easy to read
- easy to write
- easy to copy from one document to another _without formatting issues_
- non-proprietary (i.e., not owned by a single company)

Learn more [at wikipedia](https://en.wikipedia.org/wiki/Markdown) or try a tutorial [here](https://www.markdowntutorial.com/).

---

template: markdown

## Example

For example, the content of the previous slide was originally written like this:

```markdown
# Markdown

## Concept

Markdown is a simple text-based markup language that anyone can master.

- **widely-used** for writing documentation
- supported by a wide variety of software tools
- **easy** to learn
- easy to read
- easy to write
- easy to copy from one document to another _without formatting issues_
- non-proprietary (i.e., not owned by a single company)

Learn more [at wikipedia](https://en.wikipedia.org/wiki/Markdown) or try a tutorial [here](https://www.markdowntutorial.com/).
```

---

template: markdown

## Advantages

One of the advantages of writing using Markdown is that you can _use any text editor or word processor_.

--

- easy to copy and paste from one document to another wth no loss of formatting... it's all just plain text

--

- no lock-in to a specific product like Google Docs or Microsoft Word, although these too can be used to write Markdown if you must.

--

- _spend your time creating good content_, not on formatting.

---

name: remarkjs

# Remark.js

--

## Concept

[Remark.js](https://remarkjs.com) is a program that converts Markdown into a presentation that can be viewed in any web browser.

--

- It is what is used to generate this presentation.

--

- Write your a document in Markdown, put it in the `slides` directory, and the rest is automatic.

--

- You really don't even need to know that Remark.js exists in order to use it.

---

name: github

# GitHub

--

## Concept

At its core, [GitHub](https://github.com), is a file sharing service owned by Microsoft, primarily used by software developers.

--

- share and collaborete on files with others

--

- track changes to files

--

- and more...

---

template: github

## Example

All the files used to create this example course website are stored on GitHub [here](https://github.com/bloombar/example-course-materials) in a project "_repository_".

- Click the `Fork` button on that page to get your own copy of this repository!

  ![Fork button](../assets/sample-presentation/fork-button.png)

---

name: github-pages

# GitHub Pages

--

## Concept

GitHub includes a featured called **Pages** that allows you to automatically publish a website based on the files in your repository.

- This feature can be turned on for any repository in its `Settings` page.

  ![Settings page](../assets/sample-presentation/github-pages-setup.png)

---

template: github-pages

## Published site

Once enabled, the site will be published and republished automatically every time you change the Markdown.

- The link to the published site will appear on the page within a minute or two.

  ![Published site](../assets/sample-presentation/github-pages-link.png)

---

name: github-classroom

# GitHub Classroom

--

## Concept

GitHub also includes a feature called **[Classroom](https://classroom.github.com)** for educators to create and share assignments with students.

--

- Assignments can be generated from any GitHub repository. The instructor can include any starter files, instructions (written in Markdown), etc, in their original copy of the repository.

--

- When students "_accept_" the assignment, they are given their own copy of the repository.

--

- GitHub Classroom allows the instructor to easily see an archive and log of all the changes each student has made to the files in their repository.

---

template: github-classroom

## Example

Tnis repository itself is set up as an assignment using GitHub Classroom.

- Accept this assignment by clicking [this link](https://classroom.github.com/a/3PHuVk8D)!

- Feel free to turn on [GitHub Pages](#github-pages) on your copy and modify the files any way you wish.

- See your changes published live within a minute or two.

---

name: conclusions

# Conclusions

--

## Extensibility

This type of course materials setup is just the beginning.

- There are many additional tools and features that can be integrated into the setup outlined in this presentation.

- For example, [GitHub Actions](https://github.com/marketplace?type=actions) can be used to automatically run any program when a student changes their repository files, such as auto-grading it or logging their changes into a spreadsheet.

---

template: conclusions

## Thank you

Bye!
