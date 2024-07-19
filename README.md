# GatherPress `block` Playground

[This WordPress Playground](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/carstingaxion/gatherpress-block-playground/main/blueprint.json) shows state in the ongoing *block transformation process* of GatherPress. 

- [blocks in the big picture](https://github.com/GatherPress/gatherpress/issues/626) is the main issue
- [![BLOCKS](https://img.shields.io/badge/blocks-%23135545)](https://github.com/GatherPress/gatherpress/issues?q=is%3Aissue+is%3Aopen+label%3Ablocks) is the corresponding Label

## ... loads the following plugins

...which should be merged into GatherPress one by one.


| Purpose | Plugins | related Issues & PRs |
|--------|--------|--------|
| A custom version of `gatherpress`, incl. Export & Import and some additions to make *blocks* work | [export-import--plus-block-cherries.zip](https://github.com/carstingaxion/gatherpress/archive/refs/heads/export-import--plus-block-cherries.zip) | - [PR: Export & Import](https://github.com/GatherPress/gatherpress/pull/655)<br/>- [PR: *block cherries only*](https://github.com/carstingaxion/gatherpress/pull/25)<br/>- [ISSUE: General changes to post type registrations and registration of two new invisible patterns](https://github.com/GatherPress/gatherpress/issues/628) |
| Replacement for the *Events List* block | [gatherpress-query-loop.zip](https://github.com/carstingaxion/additional-advanced-query-loops/archive/refs/heads/gatherpress-query-loop.zip) |- [ISSUE: Convert Event-List block into query block-variation](https://github.com/GatherPress/gatherpress/issues/599) |
| Replacement for the *Add to Calendar* Block, using the Interactivity API. | [interactive-add-to-calendar.zip](https://github.com/carstingaxion/gatherpress-add-to-calendar/archive/refs/heads/interactivity-api.zip) |- [ISSUE: Convert add-to-calendar into interactive button block-variation](https://github.com/GatherPress/gatherpress/issues/606) |
| Alternative replacement for the *Add to Calendar* Block, using the Block-Bindings API. | [block-bindings-add-to-calendar.zip](https://github.com/carstingaxion/gatherpress-add-to-calendar/archive/refs/heads/block-bindings.zip) |- [COMMENT on ISSUE: Convert add-to-calendar into interactive button block-variation](https://github.com/GatherPress/gatherpress/issues/606#issuecomment-2185484883) |
| Replacement for the *Online Event* block | [gatherpress-onlineevent.zip](https://github.com/carstingaxion/gatherpress-onlineevent-or-venue-block/archive/refs/heads/main.zip) |- [ISSUE: NEW gatherpress/online-event block](https://github.com/GatherPress/gatherpress/issues/690) |
| A *new* Venue Block | [gatherpress-venue.zip](https://github.com/carstingaxion/gatherpress-venue/archive/refs/heads/main.zip) |- [ISSUE: Add group block-variation to provide context like the existing gatherpress/venue block does](https://github.com/GatherPress/gatherpress/issues/629)<br/>- [ISSUE: Convert Address, Phone, Website to not load in a React Component in the Front End](https://github.com/GatherPress/gatherpress/issues/562) |
| An experiment to replace the "website" part of the `gatherpress/venue` block with a block-variation of the `core/paragraph` block. | [gatherpress-venue-website.zip](https://github.com/carstingaxion/gatherpress-venue-website/archive/refs/heads/main.zip) |- [ISSUE: NEW Venue Website block](https://github.com/GatherPress/gatherpress/issues/638) | 
| The map block | ... |- [ISSUE: NEW Venue Map block](https://github.com/GatherPress/gatherpress/issues/639) |
| The Event date block | ... |- [ISSUE: NEW Event Date block](https://github.com/GatherPress/gatherpress/issues/684) |
| The RSVP block | ... | |
| The RSVP response block | ... |- [ISSUE: NEW interactive RSVP block](https://github.com/GatherPress/gatherpress/issues/691) |
| New commands for the palette | ... |- [ISSUE: NEW Commands for Palette (API)](https://github.com/GatherPress/gatherpress/issues/735) |


## ... imports some demo content

- The *(not, yet) default* [GatherPress demo-data](https://github.com/carstingaxion/gatherpress-demo-data)
- [one additional page](/gatherpress.block-demo.xml) "Query Events" with all blocks in use

## ... and sets some options

- Enable user registration, via `users_can_register`
- Enable pretty permalinks


[<kbd> <br>Test it using <code>WordPress' playground</code> <br> </kbd>](https://playground.wordpress.net/?mode=seamless&blueprint-url=https://raw.githubusercontent.com/carstingaxion/gatherpress-block-playground/main/blueprint.json)

[<kbd> <br> Edit <code>blueprint.json</code> <br> </kbd>](https://playground.wordpress.net/builder/builder.html?blueprint-url=https://raw.githubusercontent.com/carstingaxion/gatherpress-block-playground/main/blueprint.json)