# gatherpress-block-playground

This WordPress Playground shows state in the ongoing *block transformation process* of GatherPress. 

Main Issue: [blocks in the big picture](https://github.com/GatherPress/gatherpress/issues/626)

## The Playground loads the following plugins

...which should be merged into GatherPress one by one.


| Purpose | Plugins | related Issues & PRs |
|--------|--------|--------|
| A custom version of `gatherpress`, incl. Export & Import and some additions to make *blocks* work | [export-import--plus-block-cherries.zip](https://github.com/carstingaxion/gatherpress/archive/refs/heads/export-import--plus-block-cherries.zip) | [PR: Export & Import](https://github.com/GatherPress/gatherpress/pull/655)<br/>[ISSUE: General changes to post type registrations and registration of two new invisible patterns](https://github.com/GatherPress/gatherpress/issues/628) |
| Replacement for the *Events List* block | [gatherpress-query-loop.zip](https://github.com/carstingaxion/additional-advanced-query-loops/archive/refs/heads/gatherpress-query-loop.zip) | [ISSUE: Convert Event-List block into query block-variation](https://github.com/GatherPress/gatherpress/issues/599) |
| Replacement for the *Add to Calendar* Block, using the Interactivity API. | [interactive-add-to-calendar.zip](https://github.com/carstingaxion/gatherpress-add-to-calendar/archive/refs/heads/interactivity-api.zip) | [ISSUE: Convert add-to-calendar into interactive button block-variation](https://github.com/GatherPress/gatherpress/issues/606) |
| A *new* Block ... | [gatherpress-venue.zip](https://github.com/carstingaxion/gatherpress-venue/archive/refs/heads/main.zip) | [ISSUE: Add group block-variation to provide context like the existing gatherpress/venue block does](https://github.com/GatherPress/gatherpress/issues/629)<br/>[ISSUE: Convert Address, Phone, Website to not load in a React Component in the Front End](https://github.com/GatherPress/gatherpress/issues/562) |
| An experiment to replace the "website" part of the `gatherpress/venue` block with a block-variation of the `core/paragraph` block. | [gatherpress-venue-website.zip](https://github.com/carstingaxion/gatherpress-venue-website/archive/refs/heads/main.zip) | [ISSUE: NEW Venue Website block](https://github.com/GatherPress/gatherpress/issues/638) | 
| The map block | ... | [ISSUE: NEW Venue Map block](https://github.com/GatherPress/gatherpress/issues/639) |


## In addition some demo content is imported.

- The *(not, yet) default* [GatherPress demo-data](https://github.com/carstingaxion/gatherpress-demo-data)
- [one additional page](/gatherpress.block-demo.xml) "Query Events" with all blocks in use



[<kbd> <br> Edit <code>blueprint.json</code> <br> </kbd>](https://playground.wordpress.net/builder/builder.html?blueprint-url=https://raw.githubusercontent.com/carstingaxion/gatherpress-block-playground/main/blueprint.json)