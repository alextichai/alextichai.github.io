---
title: Software
layout: "page"
icon: fa-book
order: 3
---

I am personally involved in the development and maintenance of various pieces of scientific software that are particularly dedicated to the automation of the scientific development process.


AMC - Angular-momentum coupling
==============================


The **AMC** tool automates the time-consuming and error-prone derivation of angular-momentum coupling in many-body theory.
Many codes implement rotationally invariant versions of the many-body formalisms, thus, requiring a lengthy formal derivation using SU(2) algebra to simplify Clebsch-Gordan expressions. This has now been automated using graph-theory-based tools (so-called Yucys graphs) to provide the correct working equations in a matter of seconds that otherwise takes months of manual work.

We are still actively working on extending the current state to more general many-body formalism, e.g., quasi-particle theories to account for nuclear superfluidity.

The **AMC** code can be easily fetched from the python package index ('pip3 install amc')

ADG - Automated diagram generator
==============================

The **ADG** code suite provides a systematic tool to derive the working equations for a large variety of many-body frameworks with particular emphasis on symmetry-broken (Bogoliubov-based) approaches.
The use of graph-theory tools enables systematic treatment of many-body Feynman diagrams and a fast evaluation of their algebraic expression. In the past this has been elementary in deriving and validating perturbative expressions at higher orders.
Quite recently this has been extended for the first time to the non-perturbative in-medium similarity renormalization group (IMSRG).

The **ADG** code can be easily fetched from the python package index ('pip3 install adg')
