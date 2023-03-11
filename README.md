# __MKVToolNix-in-Google-Colab__
Install latest __MKVToolNix__ into the Google Colab runtime. Use __mkvmerge, mkvextract, mkvpropedit__

<a href="https://colab.research.google.com/github/dropcreations/MKVToolNix-in-Google-Colab/blob/main/MKVToolNix-in-Google-Colab.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a>
<br>
- Click on the ***"Open in Colab"*** button to open this notebook in google colab
<br>

<p align="center">
    <img alt="MKVToolNix-Logo" src=https://raw.githubusercontent.com/dropcreations/MKVToolNix-in-Google-Colab/main/MKVToolNix-Logo.png></img>
</p>

## __mkvmerge__

* You can __add__ tracks while running the cell.
* Don't use `#` and `"` in `mkvTitle`.
* Add XML file path for `globalTags`, `segmentInfo`.
* Choose a `splitMode` and add `splitArgument` __according__ to the `splitMode`.
* Chapters are accpeted __both__ `XML` and `OGM_txt` files.
* When adding a language use __laguage codes__.
* If you don't want to fill a field, leave it blank.
* If you don't know what is the relevant `mime-type`, also leave it blank in `mimeType`.
* When adding track `default`, `forced` flags, If you leave it blank, it's value will be __"No"__.
* For all `[y/n]` inputs __"y"__ for __"yes"__ and __"n"__ for __"no"__.
* `webmCompliantFile`: Create a WebM compliant file instead of mkv file output.
* While adding tracks if you have done adding, leave `inputFile` as blank to continue.
* When saving options are asked, enter folder path that you want to save your output file in `Enter folder path: ` and enter a file name to add to your output file in `Enter a name to save: `.
* If you leave both `Enter folder path: ` and `Enter a name to save: `, output folder will be `/content/` and your file will be renamed as the string that you gave in `mkvTitle`. If you haven't added `mkvTitle`, then your file will be renamed as same as the first inputed file's name. If a file exsists with the name generated for file, this will add `_new` to the end.

## __mkvextract__

* You can extract __all tracks, attachments, chapters, tags, cues, cue sheet, timecodes__.
* Also you can extract a __single track__ by selecting `extractMode: Single Track` option.
* While extracting chapters, enter `chapters extract type?` as `xml` or `ogm` when asked for extract in that format

## __mkvpropedit__

* You can edit __segment info, track info, chapters, attachments, tags__ in a mkv file.
* If you want to __delete statistic tags__ from tracks select `deleteTrackStatisticsTags`

## __Matroska/WebM Tags__

* Enter __mkv or webm file's path__ in `mkvFile`.
* If you want to delete `Title`, leave it as blank.
* You can add __tags__ using a __text document__, but the text document's content must be as formatted as below.
```
Tag name: Tag value
Tag name: Tag value, Tag value
```
* This doesn't add tags as __multiple tags__, adds all values as a single tag.
* Use __official tag names__ to add __matroska official tags__. see [here](https://www.matroska.org/technical/tagging.html)
