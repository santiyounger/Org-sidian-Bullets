> This project stopped working with the latest Obsidian updates
If you have any ideas to make it work again, please reach out to me, or create a pull request. In the meantime this project will go on standby :(

# What Is This All About?
The purpose of this code is to make headers look like org-mode bullet points, this is inspired by [org-bullets for org-mode](https://github.com/sabof/org-bullets).


This is what it looks like in Obsidian after adding the simple version code: `org-sidian.css`

<img src="https://i.imgur.com/J9i7vlp.png" title="source: imgur.com" />

>   Theme Used Reverie: Santi Younger (Available in the community themes)

> You can also find [Reverie on Github](https://github.com/santiyounger/Reverie-Obsidian-Theme).

This css code is meant to replace the hashtag symbol # used for headers and change it to cool UTF-8 symbols.

> Side Note: Everything I’ll talk about is for edit mode

This is what it's doing:

    H1 - instead of # display ◉
    H2 - instead of ## display ✸
    H3 - instead of ### display ✿
    H4 - instead of #### display ◉
    H5 - instead of ##### display ✸
    H6 - instead of ###### display ✿

I come from using spacemacs and I love org-mode. I moved most of my workflow to obsidian (therefore markdown), but there’s one thing I really miss, which is org-bullet points (which adds cools symbols to headings).


---

# This Is What The Original Looks Like In Emacs / Spacemacs

  This screenshot is my from my Spacemacs set-up, with the original [org-bullets for org-mode](https://github.com/sabof/org-bullets).
  

<img src="https://i.imgur.com/H3cWk5s.png" title="source: imgur.com" />

---

# Built-in Indentation

There's a nice indentation with every heading (achieved through left margins in the code).

This allows for easier visualization of heading level.

It looks like this:

    ◉
     ○
      ✸
        ◉
         ○
          ✸



# Installation/Set-Up

If you know how to use obsidian snippets, you know what to do. 

If not, let me walk you thought it.

---

Download this code by pressing the green button called `Code` at the top right corner. 

> (if you are reading this on my website go to [Org-sidian GitHub's page](https://github.com/santiyounger/Org-sidian-Bullets) to see what I'm talking about)

Click on Download Zip

Once it’s in your downloads folder unzip it.

Choose either 

`org-sidian-color.css`

or

`org-sidian.css`

Check above to know which one you prefer.

## accessing .obsidian folder

All we need to do is access the hidden folder that Obsidian uses for storing themes and plug-ins.

This magical folder is called `.obsidian`

## Where Is The .obsidian Folder?

If you go to your file manager in your computer, to your obsidian vault, you will notice that there's no `.obsidian` folder.

> Side note: The term "vault" is nothing more than the folder Obsidian uses to read your files.

The reason why you can't see the folder `.obsidian` is because it's a hidden folder. (which happens whenever you put a `.` at the start of any file or folder in your computer)

>So the question is how do you unhide a hidden folder?

This is gonna chance depending on what operating system you use.

## Mac
It's pretty simple in mac, all you need to do is go to Finder find your Obsidian vault and press the following shortcut.

`⌘` + `⇧` + `.`
(command + shift + `.`)

> Side note: You can press the same key again to hide it.

## Windows
Taken from [windows support page](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-10-97fbc472-c603-9d90-91d0-1166d1d9f4b5)

> Open File Explorer from the taskbar. 
> 
Select View > Options > Change folder and search options.
>
Select the View tab and, in Advanced settings, select Show hidden files, folders, and drives and OK.

## Linux
In most file managers that I've used the shortcut is:

`ctrl` + `shift` + `h` 

but this may vary. I know for sure that one works for Thunar.

if you use Ranger (which you should) the shortcut is as smooth as pressing  `zh` 

but if you use Linux (you are awesome) you probably already know this stuff. So let's move on, and if you don't use Linux I don't know why you are reading this part.

## The Hidden Folder Is Now Unhidden
Now, you'll be able to see your hidden files. You'll now be able to see the `.obsidian` folder in your vault.

## Creating the Snippets Folder

go to your `.obsidian` folder and create a folder called `snippets`.

paste the `org-sidian.css` file in there.


## Turn on the snippet
Go to Obsidian, open settings > Appearance > scroll down to "CSS Snippets"  

here you should see the `org-sidian.css` file, now you can turn it on.

<img src="https://i.imgur.com/Xw3AS2J.png" title="source: imgur.com" />

If you don't see it reload it, by pressing the reload botton underneath CSS Snippets


<a href="https://imgur.com/Zh1TCGN"><img src="https://i.imgur.com/Zh1TCGN.png" title="source: imgur.com" /></a>


> Keep in mind that some obsidian theme's might not be compatible.

If you want to test it, do it with my [Obsidian Theme Reverie](https://github.com/santiyounger/Reverie-Obsidian-Theme), which should work without a problem.

This also works great with my other Theme [Wasp-Obsidian-Theme](https://github.com/santiyounger/Wasp-Obsidian-Theme) Both can be found in Obsidian's community themes.

---

# The Different Versions Of This Code

There are 2 different styles you can go for, one is `org-sidian.css` and the other is simply called `org-sidian.css`

What's the difference? you may ask, I'm glad you ask, let me tell you.


---

## Simple Version

### org-sidian.css

`org-sidian.css`

This one is simple without any added colors, it will adapt to your themes heading colors better.


## Colored Bullet Points Version

`org-sidian-color.css`

 This version has a yellow and red set-up. You can easily change it to your taste with hex codes.
This colored version is made to work great with my [Wasp-Obsidian-Theme](https://github.com/santiyounger/Wasp-Obsidian-Theme)  which can be found in Obsidian's community themes.


<img src="https://i.imgur.com/DPuUIOS.png" title="source: imgur.com" />

---

# Considerations

---
## Same heading sizes

This looks a lot better when all headings are the same size.
By default my theme [Reverie](https://github.com/santiyounger/Reverie-Obsidian-Theme) doesn't have same heading size, but it's fairly simple to change the code to make this possible.

Learn how to create same heading sizes from the obsidian forum:
[Make all headings same size- Obsidian Forum](https://forum.obsidian.md/t/make-all-headings-same-size-as-lvl4-heading/5962)


---

# Special Thanks

Special thanks to [death.au](https://forum.obsidian.md/t/hide-or-truncate-urls-in-editor-using-css/359/14). Thanks to [his code](https://forum.obsidian.md/t/hide-or-truncate-urls-in-editor-using-css/359/14) I was able to achieve this whole thing.


---

# Additional Possible Features

Org-mode also allows for a shortcut such as alt+→ to move headings quickly from h1 to h2 and so on. and alt+ ← to move from h2 to h1

This is something I’d like to turn into a request or if possible even develop as a plug in (perhaps as I get more advanced with JavaScript, it might be possible).


---

# Versions

## Version 2.0

Fixed bug that made some headings display symbols more than once in edit mode.

Now things work great in edit and preview mode.

## Version 1.1

Changed "heading 2" symbols from  "○" to "⭗" in preview mode.

## Version 1.0

Added code for preview mode.

## Version 0.1

Initial code, still to be tested with different themes and use cases.
