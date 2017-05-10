# Biased Stop Words

*Bias are bugs*

## About

Stop words are words which are filtered out before processing of natural language data. Often in text analysis there are non-casual correlations, consider the following:

`He is an astronaut, he is on Venus`
`He is an accountant, he is on Earth`
`She is an astronaut, she is on Mars`

Processing these sentences into two topics will result in gendered clustering. If we remove the gendered terms:

`is an astronaut, is on Venus`
`is an accountant, is on Earth`
`is an astronaut, is on Mars`

Processing will result in job clustering. Both clusterings are valid, however if you are interested in employing an astronaut, you don't want male accountants showing up.

## Genres of Bias

 - Gender
 - Names

*More coming, please contribute*

## Implementations

### Python

[biased-stop-words](https://pypi.python.org/pypi/biased-stop-words)
