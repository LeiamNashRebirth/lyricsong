<p align="center">
  
<img src="https://i.imgur.com/6J2amlX.jpg" alt="LeiamNashProject">
  LyricSong <br> a free and unlimited request lyrics scraper for musixmatch and azlyrics </p>

  <br> <br> features:<br>• no need apikey<br>• fast and easy to use<br>• supports multiple request<br>• have a bigger database<br>• almost all songs have an lyrics data

  <br> <br>

installation
```js
npm i lyricsong
```

<br>
  
calling a variable
```js
const lyrics = require("lyricsong");
```

<br>

how to use?
```js
lyrics.get("MUSIC TITLE");
```

<br>

example:
```js
const music = await lyrics.get("say you wont let go");

console.log(music);

```
take note please read
<br>

• the output, or result, of your lyrics is written on actual lyrics. i don't code some of the object results for lyrics so that you can easily get the song lyrics
<br><br>

function for await
```js
async function song () {
  const music = await lyrics.get("say you wont let go");
console.log(music);
}
song();
```

<br>
<p align="center">
LyricSong is a package scrape for musixmatch and azlyrics this program uses cheerio to have and easy and readable output
  </p>


<br> • [LeiamNash](https://www.facebook.com/LeiamNashRebrth)
