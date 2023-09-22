---
layout: page
title: About
---

<p class="message"> 
	Tailoringexpert is a multi tenant plattform to create easily, fast and reproduceable requirement documentation based on a 
	general requirement catalog on a limited set of parameters, which characterize the specific project.
</p>

## Introduction
The created project requirements are called tailoring. 
A tailoring is initially created by evaluating a provided screeningsheet.
The screeningsheet is a document containing all parameters needed for selecting requirements to be applicable for a project.
Because parameters related to tenant needs tailoring creation is based on screeningsheet instead of a graphical frontend.

After initial tailoring of a project, the requirements to be appicable can either be changed using the web frontend or via 
an Excel import interface. 

The documents to be created are also tentent dependend. As a miniumum plattform provided documents for the project requirement catalog 
and also a comparison document. All plattform documents are PDF files. Templates for generating the output documents are based on HTML.

It is also possible to attach files to a template. As an example you can think of an requirement input Excel that was used for tailoring.
All files are stored in a database.

## Technical implementation

Tailoringexpert cosists of two modules:

1. Java backend plattform, realized using Spring Boot
2. Single page web frontend, realized Vue using Vuetify


Tailoringexpert is developed on and hosted with GitHub. 
Head to the [plattform repository](https://github.com/tailoringexpert/plattform) for downloads, bug reports, and features requests.
Go to [frontend](https://github.com/tailoringexpert/plattform)