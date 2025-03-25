# Aosora talk block UDL
Simple syntax highlighting for Aosora's talk blocks in Notepad++.

![image](https://github.com/user-attachments/assets/4195f25b-79a3-4a78-8bed-8d74f01dd024)


**Important: this works best for talk blocks only, and doesn't properly support function blocks and other code.** I think it will work best when used for files primarily made up of talk blocks (aitalk, bootend, etc.).

This UDL helps with the problem of apostrophes causing portions of text to be highlighted awkwardly. It focuses on SakuraScript tags instead, dimming them for you so that you can more easily read the words you've written around the tags. Additionally, it can highlight various keywords and Aosora-specific syntax used in talk blocks.

One other note: I added a couple of function names to the keywords list that I think may see common use, but that you also may want to customize. They aren't built in names, I just think they're handy and wanted to use it as an example. The following are what I included:

```
RandomTalk
BootTalk
CloseTalk
```

Feel free to delete or customize these as you wish.


## Recommendation for code highlighting
For code highlighting in files that contain function blocks, I would recommend Notepad++'s built in JavaScript highlighting, with some additional keywords added. I have some notes in [this guide](https://ukagaka.zichqec.com/guide/notepad_tips_to_improve_your_ghost_dev_experience#syntax_highlighting) about how you can add your own keywords. (The guide currently focuses on YAYA, but the same principles apply, just choose JavaScript instead of C.)

The following are the keywords I've added for use with Aosora, under INSTRUCTION WORD.

```
talk function word for while if else break continue
return local const true false try catch finally throw class member
init new print
```

v1.0.0
