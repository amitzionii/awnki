## Awnki - a type-in-the-answer CLI Anki written in AWK

### Usage
![](https://raw.githubusercontent.com/amitzionii/awnki/main/img/awnki_usage.gif)

### Deck File Format
The format of new deck files are as follows:

```
TERM 1 | DEFINITION 1
TERM 2 | DEFINITION 2
TERM 3 | DEFINITION 3
```

after first review the order of the cards might change and 3 more fields are added 
Then the format would be:

```
NEXT_REVIEW_TIMESTAMP 1 | CONSECUTIVE_SUCCESSES 1 | EASINESS_FACTOR 1 | TERM 1 | DEFINITION 1
NEXT_REVIEW_TIMESTAMP 2 | CONSECUTIVE_SUCCESSES 2 | EASINESS_FACTOR 2 | TERM 2 | DEFINITION 2
NEXT_REVIEW_TIMESTAMP 3 | CONSECUTIVE_SUCCESSES 3 | EASINESS_FACTOR 3 | TERM 3 | DEFINITION 3

```

adding new cards to an already played deck is easy. 
In a new line just add the card term and definition.
It might look something like this:

```
NEXT_REVIEW_TIMESTAMP 1 | CONSECUTIVE_SUCCESSES 1 | EASINESS_FACTOR 1 | TERM 1 | DEFINITION 1
NEXT_REVIEW_TIMESTAMP 2 | CONSECUTIVE_SUCCESSES 2 | EASINESS_FACTOR 2 | TERM 2 | DEFINITION 2
NEXT_REVIEW_TIMESTAMP 3 | CONSECUTIVE_SUCCESSES 3 | EASINESS_FACTOR 3 | TERM 3 | DEFINITION 3
TERM 4 | DEFINITION 4
TERM 5 | DEFINITION 5

```
