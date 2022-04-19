![Logo Unused Node Cleaner](https://user-images.githubusercontent.com/521864/161403833-2de0e36b-2acb-48f4-b7d0-7ce002cd6cce.gif)

# Unused Node Cleaner
"Unused Node Cleaner" allows you to clean your blueprints from unused nodes that someone left somewhere and are still there to just distract you.

**WARNING:** While the "Hide Unused" toggle is on, the plugin will disable the "Hide Unrelated" feature as te plugin uses the same engine functions to make the nodes fade out.

## How to use

**Unused Node Cleaner** can be bought from the [Unreal Engine marketplace](https://www.unrealengine.com/marketplace/en-US/slug/unused-node-cleaner).

The plugin only adds two buttons to the Blueprint editor, but you can find more information and see it in action on the wiki [Getting started](https://github.com/Urkaz/UnusedNodeCleaner/wiki/Getting-started).

You can find answers for some frequently questions on the wiki: [FAQ](https://github.com/Urkaz/UnusedNodeCleaner/wiki/FAQ).

And if you have some problem using the plugin or want to give some feedback, please create a new [Issue](https://github.com/Urkaz/UnusedNodeCleaner/issues/new/choose).

## Compatible Engine Version

Engine Version | Plugin Version | Support
-------------- | -------------- | ----
UE 4.27 | v1.1 | ✅
UE 5.0 | v1.1 | ✅

## Changelog

**Version 1.2 (under review)**
- Bug Fixes:
   - Some "pure" macro nodes were treated as unused.
- Performance:
   - Optimize Composite Nodes handling.
   - Optimize node type filtering to avoid.
- New:
   - Animation Blueprint Event Graph support. (AnimGraph will be supported in a future update).

**Version 1.1**
- Bug Fixes:
   - Button visibility on Breakpoint.
   - Node appearance when using Ctrl+Z to undo operations.
   - Composite Node handling.
   - Incorrect focused graph when viewing sub graphs.

**Version 1.0**
- Features:
   - "Clean Graph" button to remove unused nodes.
   - "Hide Unused" toggle to fade out the unused nodes.
