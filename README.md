![Logo Unused Node Cleaner](https://user-images.githubusercontent.com/521864/161403833-2de0e36b-2acb-48f4-b7d0-7ce002cd6cce.gif)

# Unused Node Cleaner
"Unused Node Cleaner" allows you to clean your blueprints from unused nodes that someone left somewhere and are still there to just distract you.

**WARNING:** While the "Hide Unused" toggle is on, the plugin will disable the "Hide Unrelated" feature as the plugin uses the same engine functions to make the nodes fade out.

## How to use

**Unused Node Cleaner** can be purchased on the [Unreal Engine marketplace](https://www.unrealengine.com/marketplace/en-US/slug/unused-node-cleaner).

The plugin only adds two buttons to the Blueprint editor, but you can find more information and see it in action on the wiki [Getting started](https://github.com/Urkaz/UnusedNodeCleaner/wiki/Getting-started).

You can find answers to some frequent questions on the wiki: [FAQ](https://github.com/Urkaz/UnusedNodeCleaner/wiki/FAQ).

And if you have some problems using the plugin or want to give some feedback, please create a new [Issue](https://github.com/Urkaz/UnusedNodeCleaner/issues/new/choose).

## Compatible Engine Version

Check the [Version compatibility](https://github.com/Urkaz/UnusedNodeCleaner/wiki/Version-compatibility) wiki page

## Changelog

**Version 2.0 (For UE 5.3)**
- New:
   - Behavior Tree editor support.
   - EQS editor support (Probably not available in UE 5.3 due to an engine bug).
   - Animation Blueprint AnimGraph support.
   - Animation State Machine support.

**Version 1.5**
- Bug Fixes:
   - Fix Timeline component nodes being deleted if not connected to anything.
   - Fix build error on Debug configuration.

**Version 1.4**
- Bug Fixes:
   - Fix Comment nodes being deleted.

**Version 1.3**
- Bug Fixes:
   - Fix Composite Node Event detection.

**Version 1.2**
- Bug Fixes:
   - Some "pure" macro nodes were treated as unused.
- Performance:
   - Optimize Composite Node handling.
   - Optimize node type filtering to avoid.
- New:
   - Animation Blueprint Event Graph support.

**Version 1.1**
- Bug Fixes:
   - Button visibility on Breakpoint.
   - Node appearance when using Ctrl+Z to undo operations.
   - Composite Node handling.

**Version 1.0**
- Features:
   - "Clean Graph" button to remove unused nodes.
   - "Hide Unused" toggle to fade out the unused nodes.
