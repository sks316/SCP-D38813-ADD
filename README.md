![Image of SCP-D38813 game running on Playdate gaming device](https://media-cdn.play.date/media/games/292403/Playdate-Catalog-art-web-feature_9qGdY9i.png)

# SCP-D38813-ADD

Welcome Researcher! This repository contains additional files submitted by the research community that are compatible with the Playdate game SCP-D38813. Don't know what that is? See these links to the [Playdate Catalog](https://play.date/games/292403/) and [Itch.io](https://subpixel.itch.io/scp-d38813) pages for reference.

For instructions on how to add these to the game, please see the [Auxiliary Document Protocol](https://subpixel.itch.io/scp-d38813/devlog/713958/new-feature-scp-d38813-auxiliary-document-protocol) article on itch.

## I want to contribute

Delightful! There are no real rules to creating an aux SCP-D38813 document, a game full of violent disturbing stories, but we have one Golden Guideline: this repo will not tolerate behavior hostile to actual real world folks. Everyone else is welcome!

## Formatting 

Aux documents are just plain text files, saved as ASCII or UTF-8. The title of the text file will be used in game as the title of the article.

There are a few optional built in delimiters that produce the blocks of content and formatting you see in the built in documents, note that they all begin with this odd Unicode character:

```
▞Wiki
▞Author The Researchers
▞Class Keter

▞ Special Containment Procedures
The object in SCP-REDACTED must be kept... 
```

* The `▞Wiki` tag indicates this article is from the SCP wiki proper, and formats the correct attribution link. Omit this for non SCP articles, to get a different format for the author box at the end of a decyphered article.
* The `▞Author` is inserted into the Author box after decyphering.
* The `▞Class` tag denotes the SCP class.
* `▞ Special Containment Procedures` denotes the main article is starting.
* Any line beginning with the special character, followed by a space and then some text will render that text as a heading, e.g. `▞ Horticultural Concerns`

There are also a few special case formats that cause changes in presentation:
* Lines beginning with a star and space `* Like this` will be formatted as a bullet list
* Lines beginning with text and a colon `Dr.Researcher: Oh is that so?` will be formatted like a transcript of spoken dialog. Note this does not support spaces in the name prior to the colon.

## Tips

A nice Aux article to share could have any content that you think would be fun for other folks to decypher. A good length is probably around 1000 words. The terminal in game can support up to 2048 *lines* at maximum, anything over that is truncated. 

Try to use the title to give your reader any hints they'll need to get started. If you're not an SCP article, that lifehack of looking for `SCP-` as your entry point disappears! Be brief though, there's not a lot of space on that article select screen. The ideal title might be a phrase that sets the right topic, containing a word that's conspicuously  actually in the article.


## Submission

If you're familiar with git, then by all means send a pull request here. If not, come join the discussion at the [Playdate Squad Discord](https://discord.com/channels/675983554655551509/1193323726087929857), and someone can help you out.
