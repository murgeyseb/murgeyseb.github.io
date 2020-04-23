---
layout: post
title:  "Project Ramuh - Prologue"
date:   2020-04-23 05:00:59 +0200
categories: project ramuh
---

Hi everyone!

Time has come to write down a description of "Project Ramuh", the first of my personal projects.

This one will be closely related to my current activities as an active member of [FARAO][farao-website] and [PowSyBl][powsybl-website] projects.

# Showcasing FARAO

I had many opportunities to present the PowSyBl framework, and the features added to it by the FARAO project. But until now, I was often blocked by one important "detail". Neither FARAO toolbox nor PowSyBl framework have dedicated application that allows to showcase  their features. These projects provides high added value features through a set of libraries, that must be integrated in a platform.

PowSyBl project team, well aware that something was falling through the net, started recently to create a [demo application][powsybl-demo].

My project is to create a demo application to showcase the main feature of FARAO project, remedial actions optimisation.

This application will be centered on one critical component, which is often seen as a WOW factor during demos: a graphical representation of the grid (on a geographical map or not, depending on the availability of geographical data in the source file).

The main challenges are to make the grid representation visually appealing even when no geographical data is provided, and to summarize the results of an entire grid security analysis in one simple graphical representation.

# Training full-stack skills

My day-to-day work is mainly focused on business logic and backend development. This project will give me the opportunity to extpand my knowledge and skills in other parts of the stack:
- UI/UX design, using React
- Cloud deployment using Kubernetes

Moreover, I think it will also be a good training on designing an application using micro-services architecture.

This project is kind of a big one to start with. That is the reason why I will do it step by step, by chapters. The available chapters will are listed below.

Next article will be focused on the walking skeleton of "Project Ramuh".

But that’s another story…

See you soon
Sébastien

[powsybl-website]: https://www.powsybl.org/
[farao-website]:   https://farao-community.github.io/
[powsybl-demo]: https://demo.powsybl.org/
