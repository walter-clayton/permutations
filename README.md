# permutations


**Take a look ?** [Demo](https://walter-clayton.github.io/permutations/)

## Description

"ODIDULA"

That's a string of letters.

If we were to create an array of all the possible permutations of these letters, sort them

alphabetically and remove repetitions, which index would ADLUDIO be at? :)

Create a single REST JSON endpoint that solves that puzzle

GET /permutation-index/{someStringHere}

The endpoint will respond with a json object with one key:

{

"indexOfGivenPermutation": 34

}

And the value 34 above is an example of the position of the given permutation in a sorted array

of all permutations (when repetitions are omitted)

For example:

Request

GET /permutation-index/LABA

Response

{

"indexOfGivenPermutation": 11

}

## Built with

* HTML5
* Javascript

## Authors

**Walter Clayton** - [GitHub](https://github.com/walter-clayton) [EN]

