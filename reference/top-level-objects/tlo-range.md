# TLO:Range

## Description

Test if _n_ is inside a range of 2 numbers or between 2 numbers

## Forms

* [_range_](../data-types/datatype-range.md) **Range**

## Access to Types

* [_range_](../data-types/datatype-range.md) **Between**
* [_range_](../data-types/datatype-range.md) **Inside**

## Changes.txt

Note: this is the info from the changes.txt this is not how it functions in current mq2.

`24 Apr 2017 by htw`  
`- Added a new TLO ${Range} which returns a pRangeType`  
`pRangeType has 2 members:`  
`Between which returns TRUE or FALSE`  
`and`  
`Inside which also returns TRUE or FALSE`  
`Usage Example:`  
`/echo ${Range.Inside[10,5:9]}`  
`which will return TRUE since 5 and 9 are both within the 10 range.`  
`/echo ${Range.Between[85,95:100]}`  
`which will return FALSE since 85 is not a number between 95 and 100`

