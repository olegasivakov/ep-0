# ep-0

Indexes of 'cache' arrays of txpool may be less than 0, or higher then array length.
Edited functions are: ```Forward()```, ```LastElement()```.

See ```// EP-0``` lines in the sourcecode.

Edited on ethnode release is Mawinor (v1.12.2) (https://github.com/ethereum/go-ethereum/releases/tag/v1.12.2) commit bed8460.

Copy file ```./txpool/legacypool/list.go``` to ethnode sourcecode.
