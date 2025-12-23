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

Initially, the *Clap* project merged the `ArgumentParser` and `OptionParser` command-line argument parsers in a single module that uses `ArgumentParser` as default and `OptionParser` as fallback.

Meanwhile, the support for `OptionParser` has been removed, due to the fact, that *Clap* requires at least *Python* 3.6, which comes with the `ArgumentParser` module by default. So, what remains is a simple wrapper for `ArgumentParser`.

The current version of *Clap* provides a parser object which can parse arguments...

*   that expect a single user-defined value (such as a number, string or path).
*   that expect a certain value (from a predefined list of options).
*   that do not expect anything, but return a Boolean value (e. g. to set a variable to `True` when given).

[Top](#clap)

## Requirements

In order to use the module, *Python* 3.6 or higher must be installed.

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
*   The module for *Python* 3 was initially created by converting the *Python* 2 module using the *2to3* tool. However, both files were identical except for the shebang.

[Top](#clap)
