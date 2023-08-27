# EP-0

## Overview
Indexes of 'cache' arrays of txpool may be less than 0, or higher then array length.
Edited functions are: ```Forward()```, ```LastElement()```.

## Notes
> [!IMPORTANT]
> Copy file ```./txpool/legacypool/list.go``` to ethnode sourcecode and build ```geth``` as usual.

> [!NOTE]
> See ```// EP-0``` lines in the sourcecode.

> [!NOTE]
> Based on ethnode release Mawinor (v1.12.2) (https://github.com/ethereum/go-ethereum/releases/tag/v1.12.2) commit bed8460.
