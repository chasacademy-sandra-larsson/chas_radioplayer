# Sveriges Radio Player :radio:

I denna övning ska du använda Sveriges Radio API för att fetcha information om radiokanaler samt kunna streama ljudet från respektive kanal!

## Hur du gör denna övning

Till att börja med, tiita på API-svaret från Sveriges Radio. Här hittar du en lista av alla 55 stationer och en url till varje radiostations live-stream: http://api.sr.se/api/v2/channels?format=json&size=100

Din uppgift är att använda `fetch()` för att får svaret i JSON-format och sedan rendera listan av alla radiostationer på din sifda. Den information som du ska ta hem är radiostationens namn, bild, färgkod till en layout som ser ut som denna:

![Wireframe](https://github.com/davidshore/chas_radioplayer/blob/main/wireframe.png?raw=true)

#### API Key

Sveriges Radio:S API behöver ingen authentisering, så det behöver du inte bry dig om! :-)

#### Audio

Kolla dokumentation [documentation](https://www.w3schools.com/tags/tag_audio.asp) for the `<audio>` tag. Formatet som streamas är mp3, så du behöver använda `<source>` med "type" "audio/mpeg".
