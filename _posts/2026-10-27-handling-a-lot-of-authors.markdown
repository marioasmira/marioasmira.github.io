---
layout: post
title:  "Handling a lot of authors when reading scientific articles"
date:   2026-10-27
categories: science article organization
---

Writing a PhD (and all kinds of other scientific work) requires a lot of time finding, reading, and organizing articles.
For me, the hardest part was keeping up pace with the amount of author names.
Each article I was reading had some four to six authors and the field of parental effects is relatively large; meaning there is not a ton of overlap and repeating authors.
It was hard for me to distinguish between the authors that have been working with parental effects for a long time and which authors were contributing temporarily.
Close to the end of the PhD, I came across [Obsidian](https://obsidian.md/).

Obsidian is a note taking app, but without a lot of the bells and whistles that other apps have (like OneNote and the like).
Instead, each note corresponds to a single text file (with a name like `TITLE.md`) which can be easily opened with other text editors.
However, the defining detail of Obsidian for me is the **"backlink"** feature.

Like in normal Markdown formats, you can link between files by using square brackets (`[like this]`).
In Obsidian, when you make a link (with `[[double brackets]]`) you don't necessarily create the target of the link, leaving it hanging.
In this way, as you write a note, you can create links to future ideas without having to make all the files immediately.
When you finally make this new note, you can see which previous notes link to the newly created one; this is the "backlink".
Alternatively, you can create all links immediately and, as you write new notes, you will recognize which terms you already wrote about.
For example, when writing notes about `git`, you can include a link to `[[Linus Torvalds]]` without worrying too much about it.
Then, 3 months later, when you write notes about `linux` and include the same link (and create the Mr. Torvalds note) you might be surprised he created both pieces of software.

![Obsidian backlink example](/assets/images/obsidian_backlink_example.png){:style="display:block; margin-left:auto; margin-right:auto"}

This detail in Obsidian, together with a plugin to import article details from [Zotero](https://www.zotero.org/), made reading, noting, and organizing ideas much easier.
When creating a new note for an article, I spent some additional seconds creating a note for each author.
In the future, each time I add a new article, I can see right away which authors I already read and which ones are new.
As shown in the image below, this makes it easy to recognizing familiar names in the field.
The note for Simon Gladman already existed when I created the note for the article so it has a highlighted color!

![Obsidian author example](/assets/images/obsidian_author_example.png)

One neat additional detail about this is that it will work across all types of notes.
If you happen to take notes on many different topics, you might be surprised to find people and details that go all over the place.
In my case, I was surprised to find that the author of a stoicism book I was reading, Massimo Pigliucci, was also the author of an evolutionary biology article I read for my thesis.
Small world, probably.
