[![travis status](https://travis-ci.org/wighawag/gc.svg)](https://travis-ci.org/wighawag/gc)

gc code utils

Currently allow to gather gc usage in code
See Tests/src/TestAll.hx for code examples

The Tests also serve as a live documentation on how Haxe and hxcpp deal with various type regarding gc usage.

The most notable is how adding a first element to an array or map create allocation on top of the one required for creating the array/map in the first place. 

