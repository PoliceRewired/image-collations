# image-collations

Images collected by the image collator.

See also: [policerewired/knife-image-collator](https://github.com/PoliceRewired/knife-image-collator)

## Directory structure

The root directory contains:

* This README
* Keywords files
* `group name/` - a collation group
    * `collated-media.csv` - a CSV summarising 
    * `yyyy-MM/` - folder containing images collated from that month

## Groups

Each group represents the collation of a subset of media retrieved from a number of accounts over a given period.

| group                     | contains |
|---------------------------|----------|
| `test-group-mps-taskforce`| Test data. [@mettaskforce](https://twitter.com/mpstaskforce) tweets matching keywords found in the knife keywords list. |

## Keyword lists

Some collations will be filtered by keyword to help reduce the.

| keyword list                     | contains |
|----------------------------------|----------|
| `keywords-list-knife-tweets.txt` | Keywords thought to be used for tweets featuring photos of knives. |
