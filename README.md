ivantage-sublime-snippets
=========================

A collection of iVantage-styled snippets for use with Sublime Text 2

## Installation

**Package Control**

The easiest way to install is via the *Package Control* plugin. Use `Ctrl + Shift + P` to bring up the command pallete and
choose `Package Control: Add Repository`. Paste the URL for this repository (https://github.com/esheffield-ivantage/ivantage-sublime-snippets) into the box.
This will add it to the list of packages available under package control. Run the command `Package Control: Install Package` and search
for `ivantage-sublime-snippets`. Choose the package to install it. Future updates to this repository should be installed automatically
when Sublime Text starts up.

## Snippet Triggers

You can use the following tab triggers to use the snippets.

#### DocBlocks

- *dbpackage*,  File header
- *dbheader*,   Function/Method header
- *dbparam*,    `@param` line for function header
- *dbproperty*, Property/attribute descriptor

#### General

- *vardump*,	Output a PHP `var_dump()` with `<pre>` and `exit()` formatting
- *dashline*,	Generic "dashed-line" comment
- *consoledir*,	Outputs a `Console::dir()` statement

#### Active4D

Fills in the gaps in the official Active4D SublimeText package. Note that this
package has not yet been release for SublimeText 3.

#### PHP

- *gs*,	Create PHP getters and setters
- *ddump*, Outputs a Doctrine debug statement
