# *Clap*

**Table of contents**
*   [Definition](#definition)
*   [Details](#details)
*   [Requirements](#requirements)
*   [Documentation](#documentation)
*   [Contact](#contact)
*   [Useless facts](#useless-facts)

----

## Definition

The *Clap* module is an easy-to-use command-line argument parser for *Python* projects.

[Top](#clap)

## Details

Current versions of *Python* provide the `ArgumentParser` module to parse command-line arguments. However, older versions (such as *Python* 2.6 and below) only contain the deprecated `OptionParser` module.

The *Clap* project merges both parsers in a single module with less configuration effort, using `ArgumentParser` as default and `OptionParser` as fallback.

The current version of *Clap* provides a parser object which can parse arguments...

*   that expect a single user-defined value (such as a number, string or path).
*   that expect a certain value (from a predefined list of options).
*   that do not expect anything, but return a Boolean value (e. g. to set a variable to `True` when given).

[Top](#clap)

## Requirements

In order to run the latest version of *Clap*, the *Python* 3.x framework (version 3.2 or higher is recommended) must be installed on the system.

Version 1.1.11 is the last official release that also runs on the *Python* 2.x framework.

If you need a later version for the *Python* 2.x framework for whatever reason, you can try refactoring the syntax from *Python* 3.x to version 2.x using the *[3to2](https://pypi.python.org/pypi/3to2)* tool.

However, there is no guarantee that this works properly or at all.

[Top](#clap)

## Documentation

For fundamental documentation as well as some usage examples you may have a look at the `usage.txt` file.

[Top](#clap)

## Contact

Any suggestions, questions, bugs to report or feedback to give?

You can contact me by sending an email to [dev@urbanware.org](mailto:dev@urbanware.org) or by opening a *GitHub* issue (which I would prefer if you have a *GitHub* account).

[Top](#clap)

## Useless facts

*   The project name is an abbreviation for ***C****ommand* ***L****ine* ***A****grument* ***P****arser*.
*   The first version uploaded on *GitHub* was *Clap* 1.1.8 built on January 15<sup>th</sup>, 2015.
*   The module for *Python* 3 was initially created by converting the *Python* 2 module using the *2to3* tool. However, both files are identical except for the shebang.

[Top](#clap)
