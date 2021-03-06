### v0.4.5
* Fix export of relics without flavor text (#3)
* Export custom keywords added with modId

### v0.4.4
* Export watcher relics

### v0.4.3
* Added more information to creature export (type, HP)
* Exporting of images can now be turned off in the mod config.
* Better bounding boxes for creature export

### v0.4.2
* Added Json export
* Added export of keywords
* Sort cards and other items in the per mod export
* Add color markup support for relic descriptions and flavor text
* Correctly use UTF8 encoding for input and output files
* Fix export of replay the spire creatures

### v0.4.1
* Fix file extension of creature images (#2)
* Avoid redundant mod ids in filenames

### v0.4.0
* No longer automatically exports on startup (can be configured).
* Exporting items from the base game can be disabled.
* Exporter now works correctly when the game is scaled down.
* Exported items are grouped per mod

### v0.3.2
* Fix for week 45 release
* Add markdown export

### v0.3.1
* Fix mod pages on case sensitive file systems
* Fix invalid characters in filenames (issue #1)

### v0.3.0
* Use BaseMod.customMonsters to also export custom monsters
* Export relics
* Export potions
* Make a per mod page of items from that mod
* Include low resolution card images, to save bandwidth on large card pages.

### v0.2.2
* Use BaseMod.encounterList to also export monsters from custom encounters.

### v0.2.1
* Compatibility with ModTheSpire and BaseMod v3.0.0
