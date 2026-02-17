---
layout: page
---

SCOWLv2 (temporary name, see
[#465](https://github.com/en-wl/wordlist/discussions/465)) is a SQLite
database and human-readable text file of basic information on English words.
The text file can be converted to and from the SQLite database via the
libscowl Python module.  The database contains information on how common a
word is, differences in spelling between the different dialects of English,
variant information, and (basic) part-of-speech and inflection information.

The primary purpose of the database is to allow the creation of high-quality
spellchecker dictionaries for most dialects of English.  The dictionary
creation can be customized to suit your specific needs.

[Premade dictionaries](dicts) are available for Hunspell, Aspell, and
as plain wordlists.  If none of those dictionaries are suitable for
your needs a simple web app is available to 
[create a customized wordlist](https://app.aspell.net/create).

The database also contains fairly comprehensive information on the spelling
differences between the various dialects of English (current American,
British, British (OED), Canadian, and Australian).  This includes marking of
variant spellings within a dialect.

SCOWLv2 is still a work in progress.  Official speller dictionaries
generated from SCOWL will be released periodically.  However, an official
release of SCOWL itself will not be created until things stabilize.  If you
wish to use SCOWL directly, it is best you check out the source from Git at
https://github.com/en-wl/wordlist.
