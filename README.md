# Moose wiki  <!-- omit in toc -->

A wiki gathering documentation related to Moose project.
The main Moose source code repository on GitHub is: [https://github.com/moosetechnology]

## Contents  <!-- omit in toc -->

- [Beginners](#Beginners)
- [Users](#Users)
- [Developers](#Developers)
- [Other Documentation](#Other-documentation)

## Beginners

- [Install Moose](Beginners/InstallMoose.md)

## Users

After installing and running Moose, one typically:
1. loads a model of a software system to perform some analyses on it;
1. performs some queries on the model
1. builds some visualization of the model

### Loading a model

A popular meta-model is the Java meta-model:
- [Famix Maker](https://github.com/moosetechnology/Moose-Easy) ![External documentation](https://img.shields.io/badge/-External%20Documentation-blue)
- [Analyse Java Project](https://fuhrmanator.github.io/2019/07/29/AnalyzingJavaWithMoose.html) ![External documentation](https://img.shields.io/badge/-External%20Documentation-blue)

You may also use models for other programming languages (see also the [Parsers](#Parsers) section):
- [Importing and exporting models](Users/ImportingAndExportingModels.md) ![To Review](https://img.shields.io/badge/Progress-ToReview-purple.svg?style=flat)

### Performing queries

- [Moose Query](https://moosequery.ferlicot.fr/) ![External documentation](https://img.shields.io/badge/-External%20Documentation-blue)
- [Tree Query](https://github.com/juliendelplanque/TreeQuery) ![External documentation](https://img.shields.io/badge/-External%20Documentation-blue)

### Visualizing a model

Visualizations are build with the [Roassal tool](https://github.com/ObjectProfile/Roassal3.git)

### More advanced tools

- [Meta Browser](Users/metaBrowser.md) ![To Review](https://img.shields.io/badge/Progress-ToReview-purple.svg?style=flat)


## Developers

A typical development action in Moose is to add a new programming language to the ones already understood.
To be able to take advantage of all the existing tools, this implies writing a parser for the language ([see below](#Parsers)) and [creating a new meta-model](Developers/CreateNewMetamodel.md).
There are also other possible actions.

- [Creating a meta-model](Developers/CreateNewMetamodel.md).
- [Define baseline loading moose](Developers/DefineBaselineLoadingMoose.md) for your own projects

### Parsers

Parsing source code to analyse is an important part of Moose.
There are different (so called) parsers already created at various stages of progress that you can use and/or contribute to.

Note: they do more than parsing since they also resolve names in the parsed code and this is not a small task.

- [Petit Parser](https://github.com/moosetechnology/PetitParser) - Write easily a Parser with Moose ![External documentation](https://img.shields.io/badge/-External%20Documentation-blue)
- [VerveineJ](Developers/Parsers/VerveineJ.md) - Generate an mse from a Java project ![To Review](https://img.shields.io/badge/Progress-ToReview-purple.svg?style=flat)
- [PowerBuilderParser](Developers/Parsers/PowerBuilderParser.md) - Generate an mse from a Powerbuilder project ![Unfinished](https://img.shields.io/badge/Progress-Unfinished-yellow.svg?style=flat)
- [FAST](Developers/Parsers/FAST.md) - Represent the AST in Famix ![Unfinished](https://img.shields.io/badge/Progress-Unfinished-yellow.svg?style=flat)


## Other Documentation

Moose is an extensive platform for software and data analysis.
It offers multiple services ranging from importing and parsing data, to modeling, to measuring, querying, mining, and to building interactive and visual analysis tools. 

The following resources are also useful to understand Moose:

- [Moose Technology](http://moosetechnology.org/) - the main web site for Moose.
- [The Moose Book](http://themoosebook.org/) - a tutorial for using Moose to analyze Java source code (Moose 6).
