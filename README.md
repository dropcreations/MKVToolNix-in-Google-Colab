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
* Don't use `#` and `"` in `mkvTitle`.
* Add XML file path for `globalTags`, `segmentInfo`.
* Choose a `splitMode` and add `splitArgument` **according** to the `splitMode`.
* Chapter are accpeted **both** `XML` and `OGM_txt` files.
* When adding a language use **laguage codes**.
* If you don't want to fill a field, leave it blank.
* If you don't know what is the relevant `mime-type`, also leave it blank in `attachmentmimeType`.
* When adding track `default`, `forced` flags, If you leave it blank, it's value will be '**No**'.
* For all inputs **'y'** for **'yes'** and **'n'** for **'no'**. 
* `webmCompliantFile`: Create a WebM compliant file instead of mkv.
* Add tracks while running the cell and after adding all tracks you want, type **'done'** in `inputFile` to continue.

## <u>**mkvextract**</u>

* You can extract **all tracks, attachments, chapters, tags, cues, cue sheet, timecodes** from below cell.
* Also you can extract a **single track** by selecting `extractMode: Single Track` option.

## <u>**mkvpropedit**</u>

* You can edit **segment info, track info, chapters, attachments, tags** in a mkv file.
* If you want to **delete statistic tags** from tracks select `deleteTrackStatisticsTags`

## <u>**Matroska/WebM Tags**</u>

* Enter **mkv file's path** in `mkvFile`.
* If you want to delete `Title` type **"delete"** in `Title`.
* If you want to add **multiple values**, separate tags by a **comma** and a **space**.
> `Eg: Artist: Artist1, Artist2, Artist3`
* You can add **tags** using a **text document**. Text document's content must be as formatted as below.
> `Tag name 1: Tag value 1, Tag value 2, Tag value 3`<br>
> `Tag name 2: Tag value 1, Tag value 2, Tag value 3`<br>
* Explainations are available while running the cell.
