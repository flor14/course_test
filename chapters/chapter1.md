---
title: 'Chapter 1: Getting started'
description:
  'This chapter will teach you about many cool things and introduce you to the
  most important concepts of the course.'
prev: null
next: /chapter2
type: chapter
id: 1
---

<exercise id="1" title="Introduction" type="slides">

<slides source="chapter1_01_introduction">
</slides>

</exercise>

<exercise id="2" title="Getting Started">

Let's ask some questions about the slides. Whats the correct answer?

Multiple Choice: Which smooth term in this model is _significant_ and _linear_?
<choice>
  
<opt text="weight">

`s(weight)` has `edf` over five, indicating it is nonlinear."

</opt>

<opt text="length">

`s(length)` has a `p-value` over 0.05 and no stars, indicating it is not significant.

</opt>

<opt text="price" correct="true">

Correct! `price` is significant (p <0.05) and linear (`edf` near 1).

</opt>

<opt text="rpm">

`s(rpm)` has `edf` over five, indicating it is nonlinear.

</opt>

<opt text="width">

`s(width)` has a `p-value` over 0.05 and no stars, indicating it is not significant.

</opt>
</choice>

Multiple Choice: In the same model (`mod_city4`), which smooth term is _non-significant_ and _non-linear_?


</exercise>

<exercise id="3" title="First steps">

&lambda; This is a code exercise. The content can be formatted in simple Markdown – so
you can have **bold text**, `code` or [links](https://spacy.io) or lists, like
the one for the instructions below.

- These are instructions and they can have bullet points.
- The code block below will look for the files `exc_01_03`, `solution_01_03` and
  `test_01_03` in `/exercises`.

<codeblock id="01_03">

This is a hint.

</codeblock>

</exercise>
