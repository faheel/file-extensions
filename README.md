# File extensions

JSON collection of scraped file extensions, along with their description and type, from [FileInfo.com][fileinfo].

The scraped data is available as JSON in two formats:

1. ### [Extensions by type](extensions_by_type.json)

   This JSON dictionary has **file types** as keys that map to an **array of extentsions** which are of that type.

   ```json
   {
       "3D image": [
           ".OBJ",
           ".3DS",
           ".3DM",
           ".MAX",
           ...
       ],
       "Audio": [
           ".AIF",
           ".M4A",
           ".MID",
           ".MP3",
           ...
       ],
       ...
   }
   ```

2. ### [Extensions with details](extensions.json)

   This JSON dictionary has **file extensions** as keys that map to a dictionary containing the **description** of that extension and its **type**.

   ```json
   {
       ".!BT": {
           "description": "BitTorrent Incomplete Download File",
           "type": "Misc"
       },
       ".!QB": {
           "description": "qBittorrent Partial Download File",
           "type": "Misc"
       },
       ".!SYNC": {
           "description": "BitTorrent Partially Synced File",
           "type": "Misc"
       },
       ...
   }
   ```

## License

This project is licensed under the terms of the [MIT license](LICENSE).


[fileinfo]: https://fileinfo.com
