---
layout: page
title: English Spell Checker Dictionaries
---

SCOWL is the basis for the official English dictionary in Aspell and
the en_US, en_CA and en_AU dictionaries in Hunspell.  Dictionaries for
British English are also available for Hunspell.

## Hunspell Dictionaries

The latest release is: 2026.02.25 ([readme](/hunspell-readme))

  * American:
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_US-2026.02.25.zip">en_US</a>,
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_US-large-2026.02.25.zip">en_US-large</a>
  * Canadian:
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_CA-2026.02.25.zip">en_CA</a>,
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_CA-large-2026.02.25.zip">en_CA-large</a>
  * Australian:
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_AU-2026.02.25.zip">en_AU</a>,
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_AU-large-2026.02.25.zip">en_AU-large</a>

The default dictionaries correspond to SCOWL size 60 and, to encourage
consistent spelling, generally only include one spelling variant for a word.
The large dictionaries correspond to SCOWL size 70 and include common
spelling variants.  The larger dictionaries, however, (1) have not been as
carefully checked for errors as the normal dictionaries and thus may contain
misspelled or invalid words; and (2) contain uncommon, yet valid, words that
might cause problems as they are likely to be misspellings of more common
words (for example, "ort" and "calender").

British English dictionaries are also available, however they are not
considered the official dictionaries for Hunspell.  The official ones are
maintained by Marco A.G.Pinto at <a
href="https://proofingtoolgui.org/">proofingtoolgui.org</a>.  Marco's
dictionaries are based on David Bartlett's now abandoned version.  They likely
have better coverage of British words and fewer Americanisms.  Marco's
dictionaries are also considerably larger than the ones based on SCOWL, and
include variant spellings.

  * British, _-ise_ (alternative version, traditional spelling):
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_GB-ise-2026.02.25.zip">en_GB-ise</a>
  * British, _-ize_ (alternative version, Oxford spelling):
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_GB-ize-2026.02.25.zip">en_GB-ize</a>
  * British large (alternative version, both spellings):
    <a href="https://github.com/en-wl/wordlist/releases/download/rel-2026.02.25/hunspell-en_GB-large-2026.02.25.zip">en_GB-large</a>

Older release of Hunspell Dictionaries are available on SourceForge at
<https://sourceforge.net/projects/wordlist/files/speller/>.

From 2026 onwards Hunspell Dictionaries are also available on GitHub at
<https://github.com/en-wl/wordlist/releases>.

## Plain Wordlists

Plain wordlist versions for the latest release are available on SourceForge in
the same directory as the latest release:
<https://sourceforge.net/projects/wordlist/files/speller/2026.02.25>

On GitHub they are available in the
[wordlist-diff](https://github.com/en-wl/wordlist-diff/tree/rel-2026.02.25) repo.

## Aspell Dictionaries

The official English speller dictionary for Aspell includes all dialects and
is available on the GNU FTP server:
[ftp.gnu.org/gnu/aspell/dict/en/](https://ftp.gnu.org/gnu/aspell/dict/en/).

## Custom Dictionaries

If none of these dictionaries are suitable to your needs you can
create your own from the information in SCOWL using this [simple
tool](https://app.aspell.net/create).

## Contributing

Suggestions for new words are always welcome.  I now use ChatGPT (and other
LLMs) to help screen words (see
[#429](https://github.com/en-wl/wordlist/discussions/429)).  To get an idea if
a word will be accepted you can use the [SCOWL Word Evaluation
GPT](https://chatgpt.com/g/g-6972895467f88191b57a7d071a15b5bf-scowl-word-evaluation).
LLMs' analysis is a significant data point, but only one of many factors
considered when adding words.

To suggest new words simply create an issue at
<https://github.com/en-wl/wordlist/issues>.  If you have multiple related words
to suggest please include them in a single issue as it is less work for me to
evaluate batches of words than one word at a time.

The old app that checked if a word is in SCOWL is retired.  If you want to
check if a word is in the latest version use the
[wordlist-diff](https://github.com/en-wl/wordlist-diff) repo.  This repo
contains generated wordlists and the combined <tt>scowl.txt</tt> file
for each commit to the main repo.

SCOWL is in no way perfect, if you find words that don't belong or other
inconsistencies please feel free to report them as an issue.

General feedback is also welcome, you can either email me directly at
<kevina@gnu.org>, or preferably start a public discussion at
<https://github.com/en-wl/wordlist/discussions>.
