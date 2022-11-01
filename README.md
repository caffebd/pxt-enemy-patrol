 


> Open this page at [https://caffebd.github.io/pxt-enemy-patrol/](https://caffebd.github.io/pxt-enemy-patrol/)

## Usage

This extensions adds blocks in sprites to quickly implement an enemy patrol route. Give your enemy sprite an x or y velocity and then use the enemy patrol blocks to set a maximum distance to move before reversing direction.

Useful for platform games or RPG games where you don't simply want the enemy to bounce on the edge of the screen or off a wall.

The blocks are added to the bottom of the **sprites** toolbox.

* Setting Distance for X Axis

```blocks
let mySprite = sprites.create(sprites.castle.heroWalkFront1, SpriteKind.Player)
mySprite.vx = 20
sprites.setPatrolPathX(mySprite, 50)
```

* Setting Distance for Y Axis

```blocks
let mySprite = sprites.create(sprites.builtin.forestBat0, SpriteKind.Player)
mySprite.vy = 20
sprites.setPatrolPathY(mySprite, 50)
```

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/caffebd/pxt-enemy-patrol** and import

## Edit this project ![Build status badge](https://github.com/caffebd/pxt-enemy-patrol/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/caffebd/pxt-enemy-patrol** and click import

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
