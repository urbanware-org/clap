# *Clap*

## Definition

The *Clap* module is an easy-to-use command-line argument parser for *Python* projects.

## Details

Current versions of *Python* provide the `ArgumentParser` module to parse command-line arguments. However, older versions (such as *Python* 2.6 and below) only contain the deprecated `OptionParser` module.

The *Clap* project merges both parsers in a single module with less configuration effort, using `ArgumentParser` as default and `OptionParser` as fallback.

The current version of *Clap* provides a parser object which can parse arguments...

 * that expect a single user-defined value (such as a number, string or path).
 * that expect a certain value (from a predefined list of options).
 * that do not expect anything, but return a Boolean value (e. g. to set a variable to `True` when given).

## Useless facts

 * The project name is an abbreviation for ***C****ommand* ***L****ine* ***A****grument* ***P****arser*.
 * The first version uploaded on *GitHub* was *Clap* 1.1.8 built on January 15th, 2015.
 * The module for *Python* 3 was created by converting the *Python* 2 module using the *2to3* tool. However, both files are identical except for the shebang.

