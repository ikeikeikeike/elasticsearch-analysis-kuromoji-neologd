Elasticsearch Analysis Kuromoji Neologd
=======================

## Overview

Elasticsearch Analysis Neologd Plugin provides Tokenizer/CharFilter/TokenFilter for Kuromoji with Neologd.

## Version

| Version   | elasticsearch |
|:---------:|:-------------:|
| master    | 1.4.X         |
| 1.4.0     | 1.4.4         |

### Issues/Questions

Please file an [issue](https://github.com/codelibs/elasticsearch-analysis-kuromoji-neologd/issues "issue").
(Japanese forum is [here](https://github.com/codelibs/codelibs-ja-forum "here").)

## Installation

    $ $ES_HOME/bin/plugin --install org.codelibs/elasticsearch-analysis-kuromoji-neologd/1.4.0

## References

### Analyzer, Tokenizer, TokenFilter, CharFilter

The plugin includes these analyzer and tokenizer, tokenfilter.

| name                    | type        |
|-------------------------|-------------|
| kuromoji\_neologd\_iteration\_mark | charfilter  |
| kuromoji\_neologd                | analyzer    |
| kuromoji\_neologd\_tokenizer      | tokenizer   |
| kuromoji\_neologd\_baseform       | tokenfilter |
| kuromoji\_neologd\_part\_of\_speech | tokenfilter |
| kuromoji\_neologd\_readingform    | tokenfilter |
| kuromoji\_neologd\_stemmer        | tokenfilter |

### Usage

See [Elasticsearch Kuromoji](https://github.com/elastic/elasticsearch-analysis-kuromoji "elasticsearch-analysis-kuromoji").

### What is NEologd

See [mecab-ipadic-NEologd](https://github.com/neologd/mecab-ipadic-neologd "mecab-ipadic-NEologd").

