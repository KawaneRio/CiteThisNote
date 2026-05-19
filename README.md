# CiteThisNote
CiteThisNote is a free Misskey Plugin that allows you to obtain all the necessary information you need to reference or "Cite" a note in a neat BibLaTex citation format.

## Version 3.0.0 Release!
The latest release of CiteThisNote now entirely rewritten using [AiScript](https://aiscript-dev.github.io/ja/) [1.2.1](https://github.com/aiscript-dev/aiscript/releases/tag/1.2.1) !

- Support for the latest version of Misskey ([v13](https://github.com/misskey-dev/misskey/releases/tag/13.0.0)+)
- Almost an entire rewrite of the internal function; smarter escape sequences
- Now lists all the alternate texts of image files attached in notes and stores them in the comment

## Installation
This is a Misskey Plugin that is meant to be installed from your Plugin settings.

1. From your instance, open ⚙`Settings` from the sidemenu. Go to 🔌`Plugins`. Then go to `Install Plugin`.
![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/6433da44-33db-4839-b5c7-0329771fa062)

1. Then paste the entire [CiteThisNote.misskeyplugin](https://github.com/KawaneRio/CiteThisNote/raw/main/CiteThisNote.misskeyplugin) in the textbox and click `Install`.
![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/8b78831c-e350-4066-b3ac-7419d7e81c58)

1. Reload the page (Misskey should reload automatically)

And CiteThisNote should be installed! Good job🎉

## Usage
Go to a random note in your timeline (It can even be your own note!). Click on the Note menu ･･･ and you should see a `このノートを引用する` as your bottommost option.

![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/f9f3fdff-c9bc-4282-ac1a-f18a89111820)

When envoked, the Plugin will output a BibLaTeX citation formatted codeblock as a dialog.

![image](https://github.com/KawaneRio/CiteThisNote/assets/61252570/bf0d0a72-e8ac-40de-9531-6dd19f19116f)

Click on the right-top ⧉ icon of the codeblock to copy! Now, you may paste the text onto your favorite BibLaTeX handler! (I use [Zotero](https://www.zotero.org/) by the way)

## Issues?
Please open an issue request at https://github.com/KawaneRio/CiteThisNote/issues/new 

## License

MIT-0

## Cite this Code

The following information may be useful for citing this software:

```
@software{kawanerio_citethisnote,
	title = {{KawaneRio}/{CiteThisNote}},
	url = {https://github.com/KawaneRio/CiteThisNote},
	shorttitle = {{CiteThisNote}},
	abstract = {{CiteThisNote} is a free Misskey Plugin that allows you to obtain all the necessary information you need to reference or "Cite" a note in a neat {BibLaTex} citation format.},
	version = {v3.0.0},
	author = {{KawaneRio}},
	date = {2026-05-19},
}
```
