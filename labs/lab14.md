---
layout: default
title: "Lab 14: Iterators, Interleaving"
---

Getting started
===============

Download [CS201\_Lab14\_Gradle.zip](gradle_src/CS201_Lab14_Gradle.zip) (or [CS201\_Lab14.zip](CS201_Lab14.zip). Extract the zip file and import it into Cloud9 (or Eclipse (**File&rarr;Import...&rarr;Gradle&rarr;Existing Gradle Project**.) You should see a project called **CS201\_Lab14\_Gradle** in the package explorer.

In the terminal window at the bottom of the Cloud9 IDE

    cd ~
    cd environment/CS201\_Lab14\_Gradle

Your Task
=========

Your task is to implement two generic methods in the **Algorithm** class: **interleave** and **mergeSortedLists**. Each method takes references to two collections as parameters.

-   The **interleave** method takes two collections, uses iterators to traverse their elements, and returns a list in which the elements in the original collections are "interleaved". For example, if the collections are lists containing **(A, B, C)** and **(D, E, F)** respectively, the result will be a list containing **(A, D, B, E, C, F)**.
-   The **mergeSortedLists** method takes two sorted lists and returns a single list containing all of the elements in the two original lists, in sorted order. For example, if the original lists are **(1, 4, 5)** and **(2, 3, 6)** then the result list would be **(1, 2, 3, 4, 5, 6)**.

Each method is accompanied by a detailed documentation comment describing how the method should work, and providing hints.

The **AlgorithmTest** JUnit test class has unit tests for each method. Take a look at the tests if you are not sure about how the method is intended to work.

Running Test Cases
==================

From the terminal window at the bottom of the Cloud9 IDE, 

    gradle build

Submitting
==========

When you are done, submit the lab to the Marmoset server using

    make submit
    
If you receive a permission denied error, type

    chmod 755 submitToMarmoset.pl
    make submit
    
<!--
From Eclipse
------------

If you have the [Simple Marmoset Uploader Plugin](../resources/index.html) installed, select the project (**CS201\_Lab14**) in the package explorer and then press the blue up arrow button in the toolbar. Enter your Marmoset username and password when prompted.

From a web browser
------------------

Save the project (**CS201\_Lab14**) to a zip file by right-clicking it and choosing

> **Export...&rarr;Archive File**

Upload the saved zip file to the Marmoset server as **lab14**. The server URL is

> <https://cs.ycp.edu/marmoset/>
-->