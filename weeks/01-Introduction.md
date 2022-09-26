---
layout: week
title: Week 01
permalink: /weeks/01-Introduction/
doodle: /doodle.png
---

# Introduction to Code-Understanding and Malware

## Topics

This week's assignments will guide you through the following topics:
* 
* How machine learning can identify malware via graphs.

## Reading

Please read the following:
* [Introduction to Malware](https://www.greycampus.com/blog/information-security/introduction-to-malware-definition-attacks-types-and-analysis)
* Wired's article [Android's Malware Problem](https://www.wired.com/story/android-malware-app-defense-alliance/)
* [Hindroid](https://www.cse.ust.hk/~yqsong/papers/2017-KDD-HINDROID.pdf)
  (Read the Introduction)

## Tasks

Find your favorite python file and sketch out how you would train an
n-gram model on it (or actually try it!). Things you should consider
are:
* how would you tokenize it? (what do you consider a word?)
* what would you consider a sentence or paragraph?
* What *syntactic* structure would you likely pick up and what would
  it miss? (What would co-occur with a function definition, for
  example?).
  
If you actually tried this, train it on python projects from github
repositories. Use your language model to generate code and see how it
fails to run!

**Note:** Recently, the success of *transformers* in language modeling
has been capable of understanding computer code surprisingly well, by
essentially throwing massive amounts of computation power at the
problem.

## Weekly Questions

Answer the following questions on Canvas:

* How is learning computer code different than typical approachs to
  NLP (e.g. n-gram models)? What would an NLP model fail to learn?
  Give an example.
* What are the different ways Malware might attack a mobile device
  through an application?
* What are the primary ways of analyzing source code for evidence of Malware?

