# English-Greek Dictionary

A Vocabulary of the Attic Language by S. C. WOODHOUSE, M.A.

This is being processed as part of the [Greek Learner Texts Project](https://greek-learner-texts.org/).

## Source

* `orig-data/woodhouse.csv` from <https://github.com/dcthree/woodhouse> (for which see provenance)

## Data Produced So Far

* `data/woodhouse.txt` programmatically processed version of csv with vowel length handled via Unicode rather than colour and other colours converted to more semantic tags. Minor (automated) corrections along the way but still lots to do

Example of current format being worked on:

```
---
Abash
{b}v. trans.{/b}
{i}Make ashamed{/i}: {corpus}P.{/corpus} and {corpus}V.{/corpus} αἰδῶ πᾰρέχειν ({grm}dat.{/grm}).
{i}Be abashed{/i}: {corpus}P.{/corpus} and {corpus}V.{/corpus} αἰσχύνεσθαι, ἐπαισχύνεσθαι. See {i}ashamed.{/i}
---
Abashed
{b}adj.{/b}
{corpus}V.{/corpus} κᾰτηφής.
```

## Possible Next Steps

* breakdown structure within each entry better
* generate index of Greek words
* extract simple mapping of words without extra context
* correct errors of inconsistent markup or punctuation
* subset based on English learner word lists

## License

The underlying text is in the public domain but data being generated is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
