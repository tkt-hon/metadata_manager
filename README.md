# Metadata Manager

This utility fetches botmetadata-files and creates interface to fetch information from them.

## Installing

Clone this repository under Hon/game/bots/lib with name ```metadata_manager```.

To use metadata manager, make your object (hero, team, etc) run file ```bots/lib/metadata_manager/init.lua```, which initializes metadata manager.

    runfile 'bots/lib/metadata_manager/init.lua'

## How to use

To use metadata manager following functions:

    dataObject object.metadata.manager.GetMapData(sFile)

    tNodes dataObject.GetNodes()
    tNodes dataObject.QueryNodes(funcMatcher)
    node dataObject.QueryNode(funcMatcher)
    node dataObject.FindByName(sName)
    node dataObject.FindAllByProperty(sProperty, value)
