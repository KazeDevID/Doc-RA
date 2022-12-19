
<h1 align="center">Random Anime</h1>

<p align="center"> 

    <img src="https://i.imgur.com/DeP0Nlv.jpeg">

</p>

Get Random Anime based on scrapping from websites.

* [Alphacoders](https://alphacoders.com)

* ~~[Wallpaper Cave](https://wallpapercave.com)~~ *Not working

* [4K Wallpapers](https://free4kwallpapers.com/)

* [Wall Haven](https://wallhaven.cc)

* [Zerochan](https://www.zerochan.net)

# Example Usage

 - Getting Wallpaper from [Alphacoders](https://alphacoders.com) (dynamic) <img align="center" width="15" src="https://cdn.discordapp.com/emojis/735119429016485920.webp?size=128&quality=lossless">

```js

const { RandomAnime } = require("random-anime");

const wall = new RandomAnime();

async function Wallpaper1() {

    const wallpaper = await wall.getAnimeWall1({ search: "to love ru", page: 1 })

    return console.log(wallpaper)

}

Wallpaper1() 

```

- ~~Getting Wallpaper from [Wallpaper Cave](https://wallpapercave.com)~~ <img align="center" width="15" src="https://cdn.discordapp.com/emojis/743459759302377574.webp?size=128&quality=lossless">

```js

async function Wallpaper2() {

    const wallpaper = await wall.getAnimeWall2("keqing")

    return console.log(wallpaper)

}

Wallpaper2()

```

- Getting Random Wallpaper from [4K Wallpapers](https://free4kwallpapers.com/) <img align="center" width="15" src="https://cdn.discordapp.com/emojis/735119429016485920.webp?size=128&quality=lossless">

```js

async function Wallpaper3() {

    const wallpaper = await wall.getAnimeWall3()

    return console.log(wallpaper)

}

Wallpaper3()

```

- Getting Wallpaper from [WallHaven](https://wallhaven.cc) <img align="center" width="15" src="https://cdn.discordapp.com/emojis/735119429016485920.webp?size=128&quality=lossless">

```js

async function Wallpaper4() {

    const wallpaper = await wall.getAnimeWall4({ title: "anime romance", type: "sfw", page: 1 })

    return console.log(wallpaper)

}

Wallpaper4()

```

- Getting Wallpaper from [ZeroChan](https://www.zerochan.net) (dynamic) <img align="center" width="15" src="https://cdn.discordapp.com/emojis/735119429016485920.webp?size=128&quality=lossless">

```js

async function Wallpaper5() {

    const wallpaper = await wall.getAnimeWall5("Makima")

    return console.log(wallpaper)

}

Wallpaper5()

```

<hr>

© [Kaze](https://github.com/KazeDevID)

