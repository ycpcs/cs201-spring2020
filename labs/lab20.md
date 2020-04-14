---
layout: default
title: "Lab 20: Recursion"
---

Getting Started
===============

Download [CS201\_Lab20\_Gradle.zip](gradle_src/CS201_Lab20_Gradle.zip) (or [CS201\_Lab20.zip](CS201_Lab20.zip)). Extract the zip file and import it into Cloud9 (or Eclipse **File&rarr;Import...&rarr;Gradle&rarr;Existing Gradle Project**.) You should see a project called **CS201\_Lab20\_Gradle** in the package explorer.

In the terminal window at the bottom of the Cloud9 IDE

    cd ~
    cd environment/CS201_Lab20_Gradle

<!--
Import [CS201\_Lab20.zip](CS201_Lab20.zip) (**File&rarr;Import...&rarr;General&rarr;Existing Projects into Workspace&rarr;Archive File**). You should see a project called **CS201\_Lab20** in the Package Explorer.
-->

Your Task
=========

Implement each static method in the class called **Recursion**. Each method has comments describing what it should do.

When you implement a method, remove the line of code reading

{% highlight java %}
throw new UnsupportedOperationException("Not implemented yet");
{% endhighlight %}

A JUnit test class called **RecursionTest** contains test cases for each method.

You must use recursion in each method. **Do not use a loop in any of the methods.**

As you think about how to implement each method, consider:

-   What is a base case (or base cases) that can be solved without using recursion?
-   How can you find a subproblem which has the same form as the overall problem?
-   How can you extend the solution to the subproblem to solve the overall problem?

Running the Unit Tests
======================

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
Submitting
==========

When you are done, submit the lab to the Marmoset server using either of the methods below.

From Eclipse
------------

If you have the [Simple Marmoset Uploader Plugin](../resources/index.html) installed, select the project (**CS201\_Lab20**) in the package explorer and then press the blue up arrow button in the toolbar. Enter your Marmoset username and password when prompted.

From a web browser
------------------

Save the project (**CS201\_Lab20**) to a zip file by right-clicking it and choosing

> **Export...&rarr;Archive File**

Upload the saved zip file to the Marmoset server as **lab20**. The server URL is

> <https://cs.ycp.edu/marmoset/>
-->