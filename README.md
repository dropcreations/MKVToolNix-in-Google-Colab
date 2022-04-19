# **MKVToolNix-in-Google-Colab**
Install latest **MKVToolNix** into the Google Colab runtime. Use **mkvmerge, mkvextract, mkvpropedit**

<a href="https://colab.research.google.com/github/dropcreations/MKVToolNix-in-Google-Colab/blob/main/MKVToolNix-in-Google-Colab.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a>
<br>
- Click on the ***"Open in Colab"*** button to open this notebook in google colab
<br>

<p align="center">
    <img alt="MKVToolNix-Logo" src=https://raw.githubusercontent.com/dropcreations/MKVToolNix-in-Google-Colab/main/MKVToolNix-Logo.png></img>
</p>

## <u>**mkvmerge**</u>

* You can **input tracks** while running the cell.
* Don't use `#` and `"` in `file_title`.
* Add XML file path for `global_tags`, `segment_info`.
* Choose a **split mode** and add split argument **according** to the split mode.
* Chapters are accpeted **both** `XML` and `OGM_txt` files.
* When adding a language use **laguage codes**.
* If you don't want to fill a field, leave it blank.
* If you don't know what is the relevant `mime-type`, also leave it blank in **attachments section**.
* When adding track `default`, `forced` flags type '**Yes**' or '**No**', If you leave it blank, It's value will be '**No**'.

## <u>**mkvextract**</u>

* You can extract **all tracks, attachments, chapters, tags, cues, cue sheet, timecodes**.
* Also you can extract a **single track** by selecting `extract_mode: single track` option.
* `chapters_mode` is for `extract_mode: chapters`

## <u>**mkvpropedit**</u>

* You can edit **segment info, track info, chapters, attachments, tags** in a mkv file.
* If you want to **delete statistic tags** from tracks select `delete_track_statistics_tags`

## <u>**Matroska/WebM Tags**</u>

* If you want to delete `Title` type as **"delete"** in `Title` when it asked.
* If you want to add **multiple values**, separate tags by a **comma** and a **space**.
> __Eg: Artist: Artist1, Artist2, Artist3__
* You can add **tags** using a **text file**. Text file's content must be as formatted as below.
> __Tag name 1: Tag value 1, Tag value 2, Tag value 3__<br>
> __Tag name 2: Tag value 1, Tag value 2, Tag value 3__<br>
* Explainations are available while running the cell.
