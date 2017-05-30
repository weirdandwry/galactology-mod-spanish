*** Example translation mod for Spanish ***

The manifest.lua must contain a language_code key to declare this as a translation mod. Please use ISO 639-1 codes.

Since this mod is handled as pure data no code will be run. Your files must be located and formatted in a specific way.

Translation files must always be located inside the mod in the path language/xx, where xx is the ISO 639-1 code of the languague your are providing and must match the manifest.lua code. Unless you have very good reasons I recommend to keep the two file names as-is (dict1.tsv and dict2.tsv).

Translation files are always TSV UTF-8 files. Google Spreadsheets is known to both import and create optimally formatted files as required by this game with "File -> Download as -> Tab-separated values".

The first column of the TSV file is the string key and must be kept as-is.

The second coiumn is the translated string. Write your translation in this column.

The third colum is the internal date of when this string was added to the game. The sorting order of the file does not matter so you can sort by this column to quickly see any new strings.

The fourth column is the original english text.

Any code-like sequences like ~A, %s, \n, @ui_icon_15px_arrow.png, represent text insertion points of various kinds. Their order and number must be kept identical, but you can control where to put them inside your string.

You can test your mod before uploading to Steam by copying it inside the mods folder in the game install folder. Restart the game to see any changes.

(NOTE: if you are a Spanish speaker and believe you can improve this example translation, feel free to fork it and do your own!)
