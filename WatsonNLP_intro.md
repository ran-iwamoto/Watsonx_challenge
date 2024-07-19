# Watson Natural Language Processing library

The Watson Natural Language Processing library provides natural language processing functions for syntax analysis and pre-trained models for a wide variety of text processing tasks, such as sentiment analysis, keyword extraction, and classification. The Watson Natural Language Processing library is available for Python only.

## Supported languages

The Language Detection block is able to detect the following 31 languages:

af, ar, bs, ca, cs, da, de, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, nl, nn, pl, pt, ro, ru, sk, sr, sv, tr, zh_cn, zh_tw

## Hierarchical text categorization

The Watson Natural Language Processing Categories block assigns individual nodes within a hierarchical taxonomy to an input document. For example, in the text IBM announces new advances in quantum computing, examples of extracted categories are technology and computing/hardware/computer and technology and computing/operating systems. These categories represent level 3 and level 2 nodes in a hierarchical taxonomy.

This block differs from the Classification block in that training starts from a set of seed phrases associated with each node in the taxonomy, and does not require labeled documents.


### Block name

categories_esa_en_stock

### Supported languages

The Categories block is available for the following languages. For a list of the language codes and the corresponding language, see Language codes.

de,en

### Capabilities

Use this block to determine the topics of documents on the web by categorizing web pages into a taxonomy of general domain topics, for ad placement and content recommendation. The model was tested on data from news reports and general web pages.

For a list of the categories that can be returned, see Category types.

### Dependencies on other blocks

The following block must run before you can run the hierarchical categorization block:

    syntax_izumo_<language>_stock


### Category types

The categories that are returned by the the Watson Natural Language Processing Categories block are based on the IAB Tech Lab Content Taxonomy, which provides common language categories that can be used when describing content.

## Syntax analysis
### Supported Languages

The Syntax analysis block is available for the following languages. For a list of the language codes and the corresponding language, see Language codes.

Language codes to use for model syntax_izumo_<language>_stock: af, ar, bs, ca, cs, da, de, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, nl, nn, pl, pt, ro, ru, sk, sr, sv, tr, zh_cn, zh_tw

Language codes to use for model syntax_izumo_<language>_stock-dp: af, ar, bs, ca, cs, da, de, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, nl, nn, pl, pt, ro, ru, sk, sr, sv, tr, zh

List of the supported languages for each syntax taskTask

## Supported language codes

- Tokenization: af, ar, bs, ca, cs, da, de, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, nl, nn, pl, pt, ro, ru, sk, sr, sv, tr, zh_cn, zh_tw, zh

- Part-of-speech tagging: af, ar, bs, ca, cs, da, de, nl, nn, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, pl, pt, ro, ru, sk, sr, sv, tr, zh_cn, zh_tw, zh

- Lemmatization: af, ar, bs, ca, cs, da, de, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, nl, nn, pl, pt, ro, ru, sk, sr, sv, tr, zh_cn, zh_tw, zh

- Sentence detection: af, ar, bs, ca, cs, da, de, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, nl, nn, pl, pt, ro, ru, sk, sr, sv, tr, zh_cn, zh_tw, zh

- Paragraph detection: af, ar, bs, ca, cs, da, de, el, en, es, fi, fr, he, hi, hr, it, ja, ko, nb, nl, nn, pl, pt, ro, ru, sk, sr, sv, tr, zh_cn, zh_tw, zh

- Dependency parsing: af, ar, bs, cs, da, de, en, es, fi, fr, hi, hr, it, ja, nb, nl, nn, pt, ro, ru, sk, sr, sv

