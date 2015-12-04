# GM-Script-NOTEPAD++

## Notepad++ syntax highlighting

![](https://yeinlookatdatunicorn.net/user/pages/blog/test/notepadpp.png)

## How to Use?

You need to modify a file `userDefineLang.xml` in your Notepad++ program folder.  

1. Download the Markdown language definition file
     - **Zenburn Theme** : [userDefineLang.xml][zenburn_xml]
     - **Default Theme** : [userDefineLang.xml][default_xml]
2. Find out your Notepad++ program folder/directory.
3. There may be a file called `userDefineLang.xml`
     - If it does _not_ already exist, copy the XML file to the folder.
     - If it _does_ exist, you need to edit your xml file manually:
       - open the active `userDefineLang.xml` with a text editor.
       - Copy the contents of the Markdown definition file between the `<UserLang...></UserLang>` tags into the active `userDefineLang.xml`, at the end right before `</NotepadPlus>`.
       - Save `userDefineLang.xml`.
4. Restart Notepad++.


If you have questions feel free to ask me here Global Mapper Forum or send me an email at blog-at-yeinlookatdatunicorn.net
