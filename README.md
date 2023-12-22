# Corpus Analysis with spaCy

Taylor Swift’s 50 Best Songs, Ranked

If you would like more information, please refer to [here](https://variety.com/lists/best-taylor-swift-songs-ranked/tim-mcgraw/)

## 1.The corpus itself

```This corpus comes from a ranked list done by Chris Willman, which focuses on ranking, parsing and reviewing several of Taylor swift's albums.```

“I’m doing good, I’m on some new shit,” Taylor Swift softly declared at the outset of “Folklore,” and truer sentiments are never constantly spoken than in the case of the woman who somehow manages to the best and most prolific songwriter in pop. Consider that, just since the last time she went on tour, Swift has released six albums, four of which were all-new, two of which dug into her vaults and proved she’s even more of a constant song fount than we knew. New shit is her brand — maybe her compulsion, too — and definitely our pleasure.

So sometimes it takes a special occasion to tear yourself away from the chronic relistenability of a “Midnights” to ask yourself: What do “Speak Now,” “1989,” “Reputation,” et al. have to say to me today?

If your favorite Swift song is missing from this highly subjective, critical 50-best list, rest assured that it’s probably in our unspoken 51st or 52nd slot. And know that on any given day, the winds might have blown differently and we might even have put “Shake It Off” or “Love Story” on the list. For now, there were just too many brilliant deep cuts to consider to let all the bigger hits hog the top ranks of the canon. And having just named “Midnights” the album of the year, I didn’t think it was too soon to push some cuts from that record onto this “Eras”-spanning list. Are you ready for it? (Boom, boom, boom.)

## 2.Target audience and the intended use of the corpus

### Target Audience:

Music Enthusiasts: People who enjoy exploring and discussing music, particularly Taylor Swift's songs and albums.

Taylor Swift Fans: Individuals who are devoted fans of Taylor Swift and are interested in exploring rankings or critical assessments of her songs.

Music Critics/Analysts: Those interested in analyzing and discussing the artistic merit, themes, and impact of Taylor Swift's music.

### Intended Use:
Song Analysis and Ranking: The corpus seems aimed at providing a critical assessment and ranking of Taylor Swift's songs across various albums.

Entertainment and Discussion: It's likely intended to spark discussions and debates among fans about the rankings and choices made by the author.

Insight into Taylor Swift's Work: It offers insights into Swift's evolution as a songwriter, her creative output, and the themes explored in her music.

```This corpus might serve as a resource for fans and analysts to engage in discussions, debates, and deeper analysis regarding Taylor Swift's music. It provides a curated list of songs and an overview of the author's subjective evaluations and rankings, likely inviting readers to explore and interpret Taylor Swift's music in various ways.```

## 3.Text selection criteria

### Ranking and Critical Assessment:

Song Quality: Selection based on the perceived quality, impact, and artistic merit of Taylor Swift's songs.

Album Representation: Inclusion of songs from various albums to cover a broad spectrum of Swift's work.

Subjective Evaluation: The author's personal preferences and critical evaluation likely influenced the inclusion of certain songs.

### Diversity and Representation:

Spanning Eras: Songs chosen from different eras of Taylor Swift's career to represent her growth and evolution as an artist.

Balance between Hits and Deep Cuts: Including both popular hits and lesser-known "deep cuts" to offer a diverse representation of her music.

### Exclusion Criteria:

Subjective Exclusion: Certain songs might have been omitted due to personal biases or the author's specific criteria for what defines a "top" song.

Space Limitations: Given the finite space of a "top 50" list, limitations in the number of songs chosen might result in exclusions.

### Author's Perspective:
Author's Preferences: The selection might reflect the author's preferences, tastes, or critical viewpoints on Taylor Swift's music.

## 4.The data collection process

### Source Identification:

Identifying the Source: The corpus is  originate from a ranked list created by Chris Willman, published in a music-related website.

### Manual Extraction and Annotation:

Manual Selection of Texts: The text excerpts about Taylor Swift were manually selected from the list written by Chris Willman.

### Text Extraction:

Extraction of Relevant Texts: Specific sections or paragraphs from the original article that focused on Swift's song analysis.

## 5.Cleaning and/or preprocessing steps 

### Text Cleaning:

Lowercasing: Converting the text to lowercase to ensure uniformity in text analysis.

Tokenization: Breaking the text into individual tokens (words or phrases) for further analysis.

### Preprocessing:

Lemmatization or Stemming: Converting words to their base or root form to reduce inflectional forms and improve analysis accuracy.

Sentence Segmentation: Splitting the text into individual sentences for granular analysis or processing.

### Feature Extraction:

Named Entity Recognition (NER): Identification and tagging of named entities (e.g., "Taylor Swift," "Folklore") for entity-based analysis.

Part-of-Speech (POS) Tagging: Assigning POS tags (verbs, nouns, adjectives) to words for syntactic analysis.

## 6.Annotations and tools

### Annotations:

NE_Words:
[decade, Swift, second, all 21st century]
[All Too Well, Taylor’s Version, linear, 10-minute, Swifties, another 10 minutes, All Too Well, All Too Well, 20-Minute Version]
[Max Martin, Shellback, Jack Antonoff, Getaway Car”, Bonnie, Clyde, first, Ridin] ...

POS:
[('PRON', 'PRP'), ('VERB', 'VBP'), ('ADP', 'IN'), ('PRON', 'PRP'), ('PRON', 'PRP'), ('VERB', 'VBZ'), ('ADV', 'RB'), ('ADV', 'RB'), ('VERB', 'VBN'), ('ADP', 'IN'), ('PRON', 'NN'), ('PROPN', 'NNP'), ('ADV', 'RB'), ('VERB', 'VBD'), ('PUNCT', ','), ('CCONJ', 'CC'), ('PRON', 'DT'), ('VERB', 'VBZ'), ('DET', 'DT'), ('NOUN', 'NN'), ('PART', 'TO'), ('VERB', 'VB'), ('PART', 'TO'), ('VERB', 'VB')]....

Lemmas:
['you', 'belong', 'with', 'I', 'it', '’', 'as', 'eternally', 'teenage', 'as', 'anything', 'Swift', 'ever', 'write', ',', 'but', 'that', '’', 'no', 'reason', 'to', 'have', 'to', 'grow', 'out', 'of', 'it', '.', 'adult', 'life', 'be', 'full', 'of', 'nothing', 'if', 'not', 'many', 'equivalent', 'to', 'high', '-', 'school', 'friend', '-', 'zoning', '.', 'who', 'among', 'we', 'eer', 'stop', 'wish', 'we', '’d', 'be', 'see', 'for', 'our', 'true', 'self', 'by', 'the', 'guy', 'who', 'can', 'not', 'take', 'his', 'eye', 'off', 'the', 'cheer', 'captain', ',', 'whether', 'for']......

Tokens
['You', 'Belong', 'With', 'Me', 'It', '’s', 'as', 'eternally', 'teenaged', 'as', 'anything', 'Swift', 'ever', 'wrote', ',', 'but', 'that', '’s', 'no', 'reason', 'to', 'have', 'to', 'grow', 'out', 'of', 'it', '.', 'Adult', 'life', 'is', 'full', 'of', 'nothing', 'if', 'not']...

Proper_Nouns
['Swift', 'eer', 'Swift']
['Taylor', 'Version', 'Groundhog', 'Day', 'Swift', 'Swifties', 'All', 'Version']...

Named_Entities
['DATE', 'PERSON', 'ORDINAL', 'DATE']
['WORK_OF_ART', 'WORK_OF_ART', 'ORG', 'TIME', 'NORP', 'TIME', 'WORK_OF_ART', 'WORK_OF_ART', 'TIME']
['PERSON', 'ORG', 'PERSON', 'PRODUCT', 'PERSON', 'GPE', 'ORDINAL', 'PERSON']...

### Tools:

SpaCy

## 7.Format of the files in the corpus

### txt and csv

```Description of the columns in the CSV file```

Filename :the name of the original text file in the data folder.

Document :the original text exactly as it appears in the text file.

Text :preprocessed text of this document.

Tokens :tokenized text of this document.

Lemmas :lemmatized text of this document.

Parts-of-speech : parts of speech of all the tokens in this document.

Proper_Nouns :specific names of people, places, organizations, or things that are capitalized in the text.)

Named_Entities :specific words or phrases in text that represent real-world entities such as persons, organizations, locations, dates, or numerical expressions.)

NE_Words : the words or tokens within a text that have been recognized or identified as named entities through a specific NLP process or system.)


## 8.Format of the files in the corpus

Data Integrity Checks

Text Specific Quality Checks

Named Entity Recognition (NER) Quality Check


