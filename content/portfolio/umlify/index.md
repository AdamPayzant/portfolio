---
title: UMLify
description: A silly project to turn C++ header files into compile-able UMLs
date: "2019-05-02T19:47:09+02:00"
jobDate: 2020
work: [C++, UML Class Diagrams]
techs: [C++]
thumbnail: umlify/uml.jpg
projectUrl: https://github.com/AdamPayzant/UML-ifier
---

A fairly silly project inspired by a joke Reddit post where a user made a functional header file formatted as a UML class diagram.

The program will take a collection of C++ header files and turn them all into class diagrams, following standards as close as possible while preserving total compatability.
The project is mostly complete, but can't draw connections between classes as finding valid characters that I like for the lines and arrows is annoying (scouring unicode documentation).