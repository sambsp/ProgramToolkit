# ProgramToolkit
Toolkit for programming

## C#

### ini

#### ini-parser
##### https://github.com/rickyah/ini-parser

A .NET, Mono and Unity3d compatible(*) library for reading/writing INI data from IO streams, file streams, and strings written in C#.

Also implements merging operations, both for complete ini files, sections, or even just a subset of the keys contained by the files.

(*) This library is 100% .NET code and does not have any dependencies on Windows API calls in order to be portable.

Note: read, cannot iterate

#### ini
##### https://github.com/Enichan/Ini

ni file reader and writer for C# written in pure .NET in a single source file.

Supports bools (case insensitive true/false), integers, doubles, and strings. Strings can have whitespace preserved or not, and can have exterior quotes or not. Defaults to case insensitive string comparisons for keys (section names and variable names), but this can be changed by changing the StringComparer field, or by changing IniFile.DefaultStringComparer for all future instances.

Comments are ignored and not saved. Inline comments at the end of values are not supported. Anything before the first section is also ignored.

Empty sections are not saved unless SaveEmptySections is set to true. Whitespace surrounding section names is removed on save and load. It is not removed while working with an IniFile instance, because this could create undesirable behavior.

Attempting to retrieve missing sections or values through indexing will not throw exceptions.

Note: read, write, iterate




