# Tanime-db
Offline Anime Database, with Synopsis, characters and voice actors. data provided from MAL.
This is the First Version, I'm not sure if this is accurate or not, I just checked a few and I think they look good, in the end my purpose in making this is just for personal use.
if you use this, no credit is required but I appreciate it if you include my name.
Last Update : `15/09/2024`

| File Name | Description |
| ------ | ------ |
| Tanime-database.json | the :sparkles: beautiful :sparkles: version  |
| Tanime-database.min.json | the minified version. :ant: |
`Tanime-database.min.json` data is same as `Tanime-database.json`

## Structure
this preview of json is specially formatted for human eyes :eyes:.
```json
{
  "anime": [
    {
      "mal_id": "52991",
      "Image": "/1015/138006l.jpg",
      "Titles": [
        "Synonyms: Frieren at the Funeral"      ,
        "Japanese: 葬送のフリーレン"                    ,
        "English: Frieren: Beyond Journey's End"
      ],
      "Type": "TV",
      "Episodes": "28",
      "Status": "Finished Airing",
      "Aired": "Sep 29, 2023 to Mar 22, 2024",
      "Premiered": "Fall 2023",
      "Broadcast": "Fridays at 23:00 (JST)",
      "Producers": [
        "Aniplex"                        ,
        "Dentsu"                         ,
        "Shogakukan-Shueisha Productions",
        "Nippon Television Network"      ,
        "TOHO animation"                 ,
        "Shogakukan"
      ],
      "Licensors": ["None found"],
      "Studios": "Madhouse",
      "Source": "Manga",
      "Genres": ["Adventure", "Drama", "Fantasy"],
      "Themes": [],
      "Demographic": ["Shounen"],
      "Duration": "24 min. per ep.",
      "Rating": "PG-13 - Teens 13 or older",
      "Score": "9.37 by 391,580 users",
      "Synopsis": "During their decade-long quest to defeat the Demon King, the members of the hero's party—Himmel himself, the priest Heiter, the dwarf warrior Eisen, and the elven mage Frieren—forge bonds through adventures and battles, creating unforgettable precious memories for most of them.\n\r\nHowever, the time that Frieren spends with her comrades is equivalent to merely a fraction of her life, which has lasted over a thousand years. When the party disbands after their victory, Frieren casually returns to her \"usual\" routine of collecting spells across the continent. Due to her different sense of time, she seemingly holds no strong feelings toward the experiences she went through.\n\r\nAs the years pass, Frieren gradually realizes how her days in the hero's party truly impacted her. Witnessing the deaths of two of her former companions, Frieren begins to regret having taken their presence for granted; she vows to better understand humans and create real personal connections. Although the story of that once memorable journey has long ended, a new tale is about to begin.\n\r\n[Written by MAL Rewrite]",
      "Characters": [
        ["Frieren", "Tanezaki, Atsumi\nJapanese" ],
        ["Fern"   , "Ichinose, Kana\nJapanese"   ],
        ["Stark"  , "Kobayashi, Chiaki\nJapanese"],
        ["Himmel" , "Okamoto, Nobuhiko\nJapanese"],
        ["Methode", "Ueda, Reina\nJapanese"      ],
        ["Übel"   , "Hasegawa, Ikumi\nJapanese"  ],
        ["Flamme" , "Tanaka, Atsuko\nJapanese"   ],
        ["Eisen"  , "Ueda, Youji\nJapanese"      ],
        ["Heiter" , "Touchi, Hiroki\nJapanese"   ],
        ["Sein"   , "Nakamura, Yuuichi\nJapanese"]
      ]
    }
  ],
  "info": {
    "anime_url"    : "https://myanimelist.net/anime/"          ,
    "anime_img_url": "https://cdn.myanimelist.net/images/anime",
    "json_by"      : "Tanuki"
  }
}
```
incase you don't know how to use the `mal_id` and `Image` keys you don't need to worry, i already embedded the base url at `info` field. just combine them. 
example of the full url:
Anime Page : `https://myanimelist.net/anime/52991`
Anime Image : `https://cdn.myanimelist.net/images/anime/1015/138006l.jpg`
also if you need the thumbnail image, just remove the `l` at the image file. example `138006l.jpg` to `138006.jpg`

## License
MIT