---
layout: page
title: Original SCOWL and its Artifacts
---

The original SCOWL (SCOWLv1) was a compilation of the information in the
database into a set of simple word lists that can be combined to create
speller dictionaries of various sizes and dialects (American, British (both
-ise and -ize), Canadian and Australian).

SCOWLv2 instead combines all that information into a single text file and
SQLite3 database.

This page contains information on SCOWLv1 and the artifacts from it.

Historic releases are available on SourceForge.net at
https://sourceforge.net/projects/wordlist/files/.

## Original SCOWL

SCOWL (Spell Checker Oriented Word Lists) and Friends is a database of
information on English words useful for creating high-quality word
lists suitable for use in spell checkers of most dialects of English.
The database primary contains information on how common a word is,
differences in spelling between the dialects if English, spelling
variant information, and (basic) part-of-speech and inflection
information.

SCOWL itself is a compilation of the information in the database into
a set of simple word lists that can be combined to create speller
dictionaries of various sizes and dialects (American, British (both
-ise and -ize), Canadian and Australian).

[View readme](/scowl-readme).
Download Version 2020.12.07 as: [tar.gz](http://downloads.sourceforge.net/wordlist/scowl-2020.12.07.tar.gz) (Unix EOL),
[zip](http://downloads.sourceforge.net/wordlist/scowl-2020.12.07.zip) (DOS/Windows EOL).
[Get source](https://github.com/en-wl/wordlist/tree/v1).

## VarCon

VarCon (Variant Conversion Info) is a database to convert between
American, British (both "ise" and "ize" spellings), Canadian and
Australian spellings and vocabulary as well as well as a table listing
the equivalent forms of other variants.

<a href="/varcon-readme">readme</a>,
<a href="http://downloads.sourceforge.net/wordlist/varcon-2020.12.07.tar.gz">tar.gz</a>,
<a href="http://downloads.sourceforge.net/wordlist/varcon-2020.12.07.zip">zip</a>
(2020.12.07)
[source](http://github.com/en-wl/wordlist)

_VarCon is no longer being maintained.  Variant information from VarCon is now
part of SCOWL._

## AGID

AGID is an Automatically Generated Inflection Database from an
insanely large word list. My goal is for the non-questionable entries
to be 100% accurate.

<a href="/agid-readme">readme</a>,
<a href="http://downloads.sourceforge.net/wordlist/agid-2016.01.19.tar.gz">tar.gz</a>, 
<a href="http://downloads.sourceforge.net/wordlist/agid-2016.01.19.zip">zip</a>
(2016.01.19) 
[source](http://github.com/en-wl/wordlist)

_AGID is no longer being mainatined._

## Unofficial Jargon File Word Lists

The Unofficial Jargon File Word Lists is a collection of useful Word Lists created 
from the [Jargon file](http://en.wikipedia.org/wiki/Jargon_File).

<a href="/jargon-wl-readme">readme</a>,
<a href="http://downloads.sourceforge.net/wordlist/jargon-wl-4.2.0-1.tar.gz">tar.gz</a>,
[source](http://github.com/en-wl/wordlist)        

## Part Of Speech Database

The Part Of Speech Database is a combination of "Moby (tm)
Part-of-Speech II" and the WordNet database.

<a href="/pos-readme">readme</a>,
<a href="http://downloads.sourceforge.net/wordlist/pos-1.tar.gz">tar.gz</a>,
<a href="http://downloads.sourceforge.net/wordlist/pos-1.zip">zip</a>,
[source](http://github.com/en-wl/wordlist)

_Please note that this is not a very high quality source.  For common
words the [2of12id.txt](/alt12dicts-infl-readme) file from the
[Alternate 12 Dicts Package](/12dicts) is better._

## Ispell English Word Lists

This package contains the contents of the Ispell (ver 3.1.20) word
list after being expand from there affix compressed form used by
Ispell.

<a href="/ispell-enwl-readme">readme</a>,
<a href="http://downloads.sourceforge.net/wordlist/ispell-enwl-3.1.20.tar.gz">tar.gz</a>,
<a href="http://downloads.sourceforge.net/wordlist/ispell-enwl-3.1.20.zip">zip</a>

_This package is provided for historical purposes.  The Ispell lists
are no longer directly used by SCOWL._

## Other Sources

* [MWords](http://icon.shef.ac.uk/Moby/)
* [UK English Wordlist With Frequency Classification](http://www.bckelk.ukfsn.org/menu.html)
* [ENABLE, YAWL](http://web.archive.org/web/20090122025747/http://personal.riverusers.com/~thegrendel/software.html)
* [UK Advanced Cryptics Dictionary (UKACD)](http://ftp.sunet.se/mirror/archive/ftp.sunet.se/pub/simtelnet/win3/homeent/ukacd17.zip)
* [1990 Census report names file](http://www.census.gov/topics/population/genealogy/data/1990_census/1990_census_namefiles.html)

You can also find the source of these lists in the
[_v1_ branch](https://github.com/en-wl/wordlist/tree/v1/other).
