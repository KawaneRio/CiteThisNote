# CiteThisNote
CiteThisNote is a free Misskey Plugin that allows you to obtain all the necessary information you need to reference or "Cite" a note in a neat BibLaTex citation format.

## Version 2.1.4 Release!
The latest release of CiteThisNote with most of the bugs in v1.0.0 fixed!

- Support for notes with special MFMs like the codeblock
- Supports notes with however many files attached
- Supports notes with null text (for file reference)
- Lists the names of all the files attached to note
- Lists MD5 Hash of all the attached files
- Lists URLs of all attached files 
- Fixed urldate and date flip

## Installation
This is a Misskey Plugin that is meant to be installed from your Plugin settings.

1. From your instance, open ⚙`Settings` from the sidemenu. Go to 🔌`Plugins`. Then go to `Install Plugin`.
![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/6433da44-33db-4839-b5c7-0329771fa062)

1. Then paste the entire [CiteThisNote.misskeyplugin](https://github.com/KawaneRio/CiteThisNote/raw/main/CiteThisNote.misskeyplugin) in the textbox and click `Install`.
![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/8b78831c-e350-4066-b3ac-7419d7e81c58)

1. Reload the page (Misskey should reload automatically)

And CiteThisNote should be installed! Good job🎉

## Usage
Click on the Note menu ･･･ and you should see a `このノートを引用する` as your bottommost option.

![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/f9f3fdff-c9bc-4282-ac1a-f18a89111820)

When envoked, the Plugin will output a BibLaTeX citation formatted codeblock as a dialog.

![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/bf0d0a72-e8ac-40de-9531-6dd19f19116f)

Copy the text and paste it to your favorite BibLaTeX handler!

## Known Issues
As of v2.1.4 , some URLs does not parse correctly and may need to be checked manually.

## License

MIT-0

## Cite this Code

The following information may be useful for citing this work:

```
@software{kawanerio_citethisnote_1698928046,
	title = {{KawaneRio}/{CiteThisNote}},
	url = {https://github.com/KawaneRio/CiteThisNote},
	shorttitle = {{CiteThisNote}},
	abstract = {{CiteThisNote} is a free Misskey Plugin that allows you to obtain all the necessary information you need to reference or "Cite" a note in a neat {BibLaTex} citation format.},
	version = {v2.1.4},
	author = {{KawaneRio}},
	date = {2023-11-02},
}
```
