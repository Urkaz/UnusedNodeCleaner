![Logo Unused Node Cleaner](https://user-images.githubusercontent.com/521864/161403833-2de0e36b-2acb-48f4-b7d0-7ce002cd6cce.gif)

# Unused Node Cleaner
"Unused Node Cleaner" allows you to clean your blueprints from unused nodes that someone left somewhere and are still there to distract you.

**WARNING:** While the "Hide Unused" toggle is on, the plugin will disable the "Hide Unrelated" feature as the plugin uses the same engine functions to make the nodes fade out.

## How to use

**Unused Node Cleaner** can be purchased on [fab.com](https://www.fab.com/listings/e3d7a5b3-4696-4056-84d7-8d9c63954748).

The plugin adds two buttons to different blueprint/graph editors that allow cleaning them. Find more information and see it in action on the [Getting Started](https://github.com/Urkaz/UnusedNodeCleaner/wiki/Getting-started) wiki page.

You can find answers to some frequent questions on the [FAQ](https://github.com/Urkaz/UnusedNodeCleaner/wiki/FAQ).

And if you have some problems using the plugin or want to give some feedback, please create a new [Issue](https://github.com/Urkaz/UnusedNodeCleaner/issues/new/choose).

## Compatible Engine Version

Check the [Version compatibility](https://github.com/Urkaz/UnusedNodeCleaner/wiki/Version-compatibility) wiki page.

## Changelog

**Version 2.4**
- Bug Fixes:
   - Project-wide cleaning crashes related to "Conduit" and "Transition" graphs from State Machine graphs.
   - State Machine "State Alias" nodes are handled correctly now.
   - Fixed a build warning related to the "EnvironmentQueryEditor" plugin.

**Version 2.3**
- New:
   - Project-wide cleaning: A new option is available in the Right-click menu from the Content Browser to clean the graphs of multiple assets at once.
      - Right-click a folder in the Content Browser to clean the graphs of that folder.
      - Right-click anywhere in the Content Browser without selecting anything to run the cleaner in the current folder.

**Version 2.2**
- New:
   - Added a keyboard shortcut to execute the "Clean Nodes" action: **Ctrl+Shift+C** (can be changed in the engine settings).
   - Added a keyboard shortcut to toggle the "Hide Unused" button: **Ctrl+Shift+H** (can be changed in the engine settings).

**Version 2.1**
- Bug Fixes:
   - Fixed a crash when adding a Button event from the UMG editor.

**Version 2.0**
- New:
   - Animation Blueprint AnimGraph support.
   - Animation State Machine support.
   - Behavior Tree editor support (Only available on UE5.3).
   - EQS editor support (Not available in UE5.3 due to an engine bug).

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
- New:
   - "Clean Graph" button to remove unused nodes.
   - "Hide Unused" toggle to fade out the unused nodes.
