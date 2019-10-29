# TDT4250 project

## Project task alternatives


1. Find a public or easily available data source with some volume of data and interesting level of complexity. Model the data using Ecore and implement an transformation facility so you can import, view and process the data using EMF. Then create a viewer and editor for the data using (preferably) Sirius or EMF Forms, that can be installed into Eclipse.

2. ***Find a kind of artifact, e.g. file format, preferably text-based, that is used within software development. Create an alternative textual syntax that is easier to use (read and write) and implement an Xtext-based editor for it, and an M2M or M2T transformation to the existing format.***

3. Like 1, but implement a web service for serving the data (as Ecore instances data), instead of a viewer and editor. The web service should run on top of OSGi and provide facilities for removing and adding data sets and should support updating the data model and supported data sources without restarting.

## Task specification

This project will mostly cover the same course topics as task alternative 2.
It will atempt to use antlr, xtext, acceleo and java to create a [DSL](https://en.wikipedia.org/wiki/Domain-specific_language) for converting programming languages to kernel languages for the appropriate programming paradigm. 

- The programming language and kernel language will be defined with antlr grammar files.
- The translation from programming language to kernel language will be defined as a DSL.
- The DSL will be defined using Xtext.
- The parser for the antlr generated tokenstream will be implemented with acceleo based on the Ecore model given with the DSL.

## Motivation

The reason for doing this is mainly to learn more in-depth use of xtext and antlr. It will help me understand DSL's better and use of acceleo as a template framework and OCL.

Although the the limited time on this project will not allow for a complete solution. If the project is taken further it could help with simplifying programming languages for applications that parses languages to extract information related to paradigmes.