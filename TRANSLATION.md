# Translation Guide

Thanks for your interest in translating this doc!

Before getting started, it is recommended to learn about Markdown and HTML in general to understand
what happening on [i18n/en_US.md](i18n/en_US.md).

You can learn Markdown from:

* [Learn Markdown](https://learn-markdown.github.io)
* [Writing on GitHub](https://docs.github.com/en/github/writing-on-github)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

...and HTML from:

* [HTML Tutorial by W3Schools](https://www.w3schools.com/html/default.asp)
* [HTML Tags Reference by W3Schools](https://www.w3schools.com/tags/default.asp)
* [HTML.com](https://html.com)

Then, we recommend you to use [Microsoft Visual Studio Code](https://code.visualstudio.com) as most
of configurations and plugins were set up there. 😔

## Index

* [Translation Guide](#translation-guide)
  * [Index](#index)
  * [tl;dr](#tldr)

## tl;dr

* You can not modify any content inside comment if it's splitted from paragraph.
* You can not modify content wrapped between `<!-- START: -->` and `<!-- END -->` unless stated
  otherwise in the comment.
* Format the document as if.
* Do not modify link aliases.
* You can modify slightly the document overall to accommodate local interpretation.
* Do not modify UTC time, but you can add description in local time and modify styling based on
  grammatical rule on the language.
  > **Example:**
  > | Locale | Culture Code | Time Notation |
  > | -----: | :----------: | :------------ |
  > | Original | `en_US` | 1:00 PM UTC/GMT+0 |
  > | Indonesia | `id_ID` | 13.00 UTC/GMT+0 (20.00 WIB) |
  > | Japanese | `ja_JP` | 午後13:00（UTC）、午後22:00（JST） |
* In any links that redirect to a page using foreign language, it is wise to describe what language
  used in the link.