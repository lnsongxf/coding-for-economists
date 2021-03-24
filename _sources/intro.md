# Introduction

```{warning}
This book is under construction.
```

Welcome to **coding for economists**, a guide for economists on what programming is, why it's useful, and how to do it.

The book aims to give you the skills you need to code for economics, while also giving you bits and pieces of information about programming more generally that might be useful to you. It's suitable for complete beginners who have never written any code before. Some of the later chapters are suitable for people who have coded before too.

Naturally, at times, I have made choices regarding what to include, what to omit, and what to recommend. I have given recommendations based on what will serve you best in the long-run. Very occasionally, like the Karate Kid painting Mr Miyagi's fence, you will wonder why such and such a thing is useful for coding in an economics context. But, also like the Karate Kid, you will find that you weren't *just* learning to paint a fence, you were becoming a karate (coding) master.

## What is coding?

Computer programming, or coding, is the process of issuing a series of commands that a computer can understand and execute in order to perform a task. Today, almost all research with some quantitative aspect involves coding.

Imagine a computer as being like a particularly mischievous genie; if your instructions aren't completely unambiguous, the computer won't do what you asked for. So we write out our code, our list of instructions for the computer, very explicitly to make sure *we* can check we wrote what we meant, and that the computer will do it in the way we anticipate. Like a genie though, if you can get the instructions just so, you can create magical things.

## Why should economists learn to code?

Given so much of economics is quantitative, coding is an essential skill for many economists. Many of the tools and packages that have been developed will help you to do better work more productively. It's Pareto improving.

As a skill, programming is enormously valuable *beyond economics* too because it's used across a wide range of domains (this is especially true for general purpose programming languages). Code is widely used across industry, academia, and the public sector in everything from computer games to websites, data science to software applications. And learning basic programming concepts in any language is useful for almost any other programming language. So learning to code is good for your human capital.

Coding is like a superpower; it's both fun and powerful! Head to the first section to get started.

## How to use this book

As well as reading the book, you can also run the code examples for yourself (this is a great way to learn). There are a couple of ways to run code from the book:

1. All pages that have code on can be downloaded to your desktop and run as *Jupyter Notebooks*. Click the download symbol in the top right hand corner of the page and select '.ipynb', which stands for 'ipython notebook'. To use downloaded notebooks, you'll need a minimum of an installation of Python and the Jupyter (or Jupyter Lab) library (`pip install jupyterlab`). To run a downloaded notebook you can either open it directly in Visual Studio Code (see the instructions in the Preliminaries chapter for more on installing Visual Studio Code) or you can run `jupyter-lab` on the command line (you can find out more about what a 'command line' is in the book!) and then open the notebook file.

2. Most pages that have code on can be run as a *Google Colab* notebook with a single click on `Colab`, found under the rocket launch button at the top of the page. If you need to install any extra packages in a Google Colab session, the syntax is `!pip install packagename` to install a library called 'packagename'.

For a small number of the examples using data, you may need to download the relevant files from this book's github [repository](https://github.com/aeturrell/coding-for-economists/tree/main/data), but this will always be explained in the relevant subsections.

```{admonition} Tip
:class: tip
Every page with code can be downloaded and run as a Jupyter notebook--just click <i class="fas fa-download"></i> at the top of the page and select '.ipynb'.

Most pages with code can be run in Google Colab --just click <i class="fas fa-rocket"></i> at the top of the page and select 'Colab'.

```

## Reading guide

You can read this book in any order depending on your experience. Check the section headings and numbered chapter headings to find out what would be most valuable for you.

## Contributing

Contributions are welcome! You can make suggestions, requests, and point out bugs or mistakes by [raising an issue](https://github.com/aeturrell/coding-for-economists/issues) on the github repository for the book. You can also make [pull requests]() with fixes, edits, or new content.

## Citing Coding for Economists

To cite this book, please use:

```
@book{Turrell2021,
title     = "Coding for Economists",
author    = "Turrell, Arthur",
year      = 2021,
publisher = "Online",
url       = "https://aeturrell.github.io/coding-for-economists"
}
```

Please note that this book does not represent the views of any employer of its author(s).